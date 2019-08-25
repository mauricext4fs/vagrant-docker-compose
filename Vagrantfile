Vagrant.configure("2") do |config|
  config.vm.box = "mauricext4fs/centos"
  config.vm.provision "shell", path: "provision.sh"
  config.vm.synced_folder '.', '/home/vagrant/sync', disabled: true
  config.ssh.forward_agent = true
end
