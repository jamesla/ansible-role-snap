## ansible-role-tmux

![status](https://travis-ci.org/jamesla/ansible-role-snap.svg?branch=master)

Builds and installs tmux from the master branch rather than from apt which can be out of date on older distributions.

### Usage

add the following variable:
```
snap_packages:
  - name: hel
    use_classic: true
```
playbook.yml:
```
- { role: ansible-role-snap }
```

requirements.yml:
```
- src: https://github.com/jamesla/ansible-role-snap.git
  version: master
  name: ansible-role-tmux
```
