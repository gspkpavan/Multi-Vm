# _*_ mode: ruby _*_
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
	config.vm.box = "centos/7"
	config.vm.network "private_network", ip: "192.168.30.25"
	config.vm.hostname = "server"
	
config.vm.define "client" do |client|
	client.vm.box = "ubuntu/trusty64"
	client.vm.network "private_network", ip: "10.20.30.15"
	client.vm.hostname = "client"
	
end
end
