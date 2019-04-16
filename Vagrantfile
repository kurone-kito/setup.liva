# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "fedora/29-atomic-host"
  config.vm.box_check_update = true
  config.vm.provider 'virtualbox' do |vb|
    vb.cpus = 2
    vb.linked_clone = true
    vb.memory = '4096'
    vb.name = 'Test for LIVA'
  end
end
