# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = 'ubuntu/trusty64'
  config.vm.define 'graphite' do |host|
    config.vm.box = 'ubuntu/trusty64'
    host.vm.network 'private_network', ip: '192.168.105.100'
    host.vm.hostname = "graphite.lh"
  end
end
