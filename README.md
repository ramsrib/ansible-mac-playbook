# ansible-mac-playbook

Ansible playbook to setup my development environment in mac

## Steps

$ ./setup.sh

ansible-playbook -i ./hosts extra-packages.yml

ansible-playbook -i ./hosts dotfiles.yml

## More steps

ansible-galaxy install -r requirements.yml

## Reference

Checkout the following repos:

- <https://github.com/geerlingguy/mac-dev-playbook>
- <https://github.com/geerlingguy/dotfiles>
- <https://github.com/geerlingguy/ansible-role-dotfiles>

## TODO

- Refactor the tasks and organized into separate modules
