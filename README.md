# Rails server playbook for Ansible

## Installation
For Ubuntu

apt-get install ansible



##It installs:
- Fix timezones, locales
- Create deploy user with keys
- Ruby 2.2 from brightbox repo
- PostgreSQL 9.3
- nginx
- create dirs for capistrano
- crete database.yml

## Run
Rename sample files

Put developers keys in files/keys/developers.pub and play

./play  			playing main.yml on testing environment

./play production	playing main.yml on production environment



