VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.synced_folder(
    "#{ENV["GOPATH"]}/bin/pgit-xc/snapshot", "/home/vagrant/snapshot")
end
