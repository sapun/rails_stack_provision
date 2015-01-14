# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  
  config.vm.define "web" do |web|
    web.vm.hostname = "web-1.dev.local"
    web.vm.box = "ubuntu/trusty64"
    web.vm.network "private_network", ip: "192.168.22.10"
  end
  config.vm.define "db" do |db|
    db.vm.hostname = "db-1.dev.local"
    db.vm.box = "ubuntu/trusty64"
    db.vm.network "private_network", ip: "192.168.22.12"
  end
end
