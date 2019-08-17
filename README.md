## ansible-role-snap

Installs snap and a list of user specified packages

### Usage

add the following variable:
```
snap_packages:
  - name: helm
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
  name: ansible-role-snap
```
