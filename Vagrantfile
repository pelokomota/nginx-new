Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu2004"
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
    end  

  config.vm.define "nginx" do |nginx|
    nginx.vm.network "private_network", ip: "172.17.177.150"
    end

end
