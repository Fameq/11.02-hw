Vagrant.configure("2") do |config|
config.vm.define "master" do |master|
  master.vm.box = "ubuntu/bionic64"
  master.vm.hostname = "master"
  master.vm.network "public_network", ip: "10.10.10.10"
  master.vm.provider "virtualbox" do |vb|
      vb.memory = 2048
      vb.cpus = 2
  end
end
end

