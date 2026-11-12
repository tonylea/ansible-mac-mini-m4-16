# ansible-mac-mini-m4-16

Configures mac-mini-m4-16.
Run by hand on mac-mini-m4-16, against itself.

## First run

```sh
brew install ansible
git clone git@github.com:tonylea/ansible-mac-mini-m4-16.git
cd ansible-mac-mini-m4-16
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml
```

## Later runs

```sh
git pull
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml
```
