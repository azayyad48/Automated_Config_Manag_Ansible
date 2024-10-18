Vagrant.configure("2") do |config|
  config.vm.define "webserver" do |web|
    web.vm.box = "ubuntu/bionic64"
    web.vm.hostname = "webserver"
    web.vm.network "private_network", type: "dhcp"
  end

  config.vm.define "dbserver" do |db|
    db.vm.box = "ubuntu/bionic64"
    db.vm.hostname = "dbserver"
    db.vm.network "private_network", type: "dhcp"
  end
end
