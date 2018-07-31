# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
 config.vm.define "server" do |server|
        server.vm.box = "bento/centos-6.7"
        server.vm.hostname = "server"
        server.vm.network "private_network", ip:"192.168.60.60"

  end

 config.vm.define "client" do |client|
        client.vm.box = "centos/7"
        client.vm.hostname = "client"
        client.vm.network "private_network", ip:"192.168.70.70"

 end

end
