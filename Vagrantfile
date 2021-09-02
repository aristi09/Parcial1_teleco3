Vagrant.configure("2") do |config|
config.vm.define :servidor do |servidor|
servidor.vm.box = "bento/centos-7.9"
servidor.vm.network "forwarded_port" , guest: 80, host: 8080
servidor.vm.network :private_network, ip: "192.168.50.3"
servidor.vm.hostname = "servidor"
end
end
