Vagrant.configure("2") do |config|

  config.vm.define "web" do |web|
    web.vm.box = "debian/bookworm64"
    web.vm.hostname = "web.sistema.test"
    web.vm.network "private_network", ip: "192.168.57.10"
    web.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
      vb.name = "web"
    end
  end

end