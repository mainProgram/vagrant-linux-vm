Vagrant.configure("2") do |config|

  config.vm.define "server" do |webserver|

    webserver.vm.box = "ubuntu/trusty64"

    webserver.vm.provider "virtualbox" do |vb|
      vb.gui = false
      vb.name = "linux-vm"
      vb.memory = "1024"
    end
  end
end