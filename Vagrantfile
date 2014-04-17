# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define :dnsserver do |dnsserver|
    server1.vm.box = "precise32"
    server1.vm.network :private_network, ip: "10.11.1.100"
  end

  config.vm.define :asteriskpbx do |asteriskpbx|
    server2.vm.box = "precise32"
    server2.vm.network :private_network, ip: "10.11.1.101"
  end
end
