Vagrant.configure("2") do |config|
    config.vm.define "master" do |master|
      master.vm.box = "ubuntu/focal64"
      master.vm.hostname = "master"
      master.vm.network "private_network", ip: "192.168.56.41"
    end
  
    config.vm.define "slave" do |slave|
      slave.vm.box = "ubuntu/focal64"
      slave.vm.hostname = "slave"
      slave.vm.network "private_network", ip: "192.168.56.42"
    end
  end
  
