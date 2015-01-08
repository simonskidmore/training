Vagrant.configure(2) do |config|
config.vm.box = "landregistry/ubuntu"

config.vm.provision :shell, path: "provision.sh"
config.vm.network "forwarded_port", guest: 5000, host: 5000
config.vm.network "private_network", :ip => "172.16.42.43"
end