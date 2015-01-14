# Rails server playbook for Ansible

## Instalation

apt-get install ansible
ansible-galaxy install zzet.rbenv



##It installs:
- Fix timezones, locales
- Ruby 2.0
- PostgreSQL
- nginx
- create dirs for capistrano

## Run
Rename sample files
./play                               # playing main.yml on testing environment
./play production                    # playing main.yml on production environment

