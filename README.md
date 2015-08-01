# ansible-pyenv-centos6

## Example Playbook

```
- hosts: test01
  user: username
  roles:
    - { role: yuhiwa.venv}
```

## インストール後例

```
virtualenv --python=/usr/bin/python2.7 py27

deactivate py27
workon py27
```


CentOS6 to CentOS6 only
Python2.7 only


