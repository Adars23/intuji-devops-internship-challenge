Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64" # Ubuntu 20.04 box
  config.vm.network "private_network", ip: "192.168.56.66" # Private network with DHCP

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024" # Set memory size to 1GB
    vb.cpus = 2 # Set number of CPUs to 2
  end

  config.vm.provision "shell", inline: <<-SHELL
    # Update the system and install necessary packages
    sudo apt-get remove docker docker-engine docker.io
    sudo apt-get update
    sudo apt-get install docker.io -y  # Add your required packages here

    # Additional setup commands can go here
  SHELL
end
