# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
  # The most common configuration options are documented and commented below.
  # For a complete reference, please see the online documentation at
  # https://docs.vagrantup.com.

  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://atlas.hashicorp.com/search.
  #config.vm.box = "base"



  config.vm.define :"redis1" do |redis1|
    redis1.vm.box = "bento/centos-7.1"
    redis1.vm.hostname = "redis1"
    redis1.vm.network "private_network", ip: "192.168.1.5"
    redis1.vm.provision :shell, path: "install_redis.sh", args:["redis1", "7000"]

    #web_config.vm.share_folder "SERVER", "/SERVER", SERVER_PATH
    #web_config.vm.share_folder "DATA", "/DEVELOPMENT", DEVELOPMENT_PATH
    #web_config.vm.forward_port 22, 2222
    #web_config.vm.forward_port 80, 4567
    # redis1_config.vm.network :hostonly, "192.168.0.100"
    #web_config.vm.customize ["modifyvm", :id, "--memory", 512]

    # apache.vm.provider "virtualbox" do |v|
    #     v.customize [ "modifyvm", :id, "--cpus", "1" ]
    #     v.customize [ "modifyvm", :id, "--memory", "600" ]
    # end
  end


  config.vm.define :"redis2" do |redis2|
    redis2.vm.box = "bento/centos-7.1"
    redis2.vm.hostname = "redis2"
    redis2.vm.network "private_network", ip: "192.168.1.6"
    redis2.vm.provision :shell, path: "install_redis.sh", args:["redis2","7001"]

    #web_config.vm.share_folder "SERVER", "/SERVER", SERVER_PATH
    #web_config.vm.share_folder "DATA", "/DEVELOPMENT", DEVELOPMENT_PATH
    #web_config.vm.forward_port 22, 2222
    #web_config.vm.forward_port 80, 4567
    # redis2_config.vm.network :hostonly, "192.168.0.100"
    #web_config.vm.customize ["modifyvm", :id, "--memory", 512]

    # apache.vm.provider "virtualbox" do |v|
    #     v.customize [ "modifyvm", :id, "--cpus", "1" ]
    #     v.customize [ "modifyvm", :id, "--memory", "600" ]
    # end
  end


  config.vm.define :"redis3" do |redis3|
    redis3.vm.box = "bento/centos-7.1"
    redis3.vm.hostname = "redis3"
    redis3.vm.network "private_network", ip: "192.168.1.7"
    redis3.vm.provision :shell, path: "install_redis.sh", args:["redis3","7002"]

    #web_config.vm.share_folder "SERVER", "/SERVER", SERVER_PATH
    #web_config.vm.share_folder "DATA", "/DEVELOPMENT", DEVELOPMENT_PATH
    #web_config.vm.forward_port 22, 2222
    #web_config.vm.forward_port 80, 4567
    # redis3_config.vm.network :hostonly, "192.168.0.100"
    #web_config.vm.customize ["modifyvm", :id, "--memory", 512]

    # apache.vm.provider "virtualbox" do |v|
    #     v.customize [ "modifyvm", :id, "--cpus", "1" ]
    #     v.customize [ "modifyvm", :id, "--memory", "600" ]
    # end
  end


  config.vm.define :"redis4" do |redis4|
    redis4.vm.box = "bento/centos-7.1"
    redis4.vm.hostname = "redis4"
    redis4.vm.network "private_network", ip: "192.168.1.8"
    redis4.vm.provision :shell, path: "install_redis.sh", args:["redis4","7003"]

    #web_config.vm.share_folder "SERVER", "/SERVER", SERVER_PATH
    #web_config.vm.share_folder "DATA", "/DEVELOPMENT", DEVELOPMENT_PATH
    #web_config.vm.forward_port 22, 2222
    #web_config.vm.forward_port 80, 4567
    # redis4_config.vm.network :hostonly, "192.168.0.100"
    #web_config.vm.customize ["modifyvm", :id, "--memory", 512]

    # apache.vm.provider "virtualbox" do |v|
    #     v.customize [ "modifyvm", :id, "--cpus", "1" ]
    #     v.customize [ "modifyvm", :id, "--memory", "600" ]
    # end
  end



  config.vm.define :"redis5" do |redis5|
    redis5.vm.box = "bento/centos-7.1"
    redis5.vm.hostname = "redis5"
    redis5.vm.network "private_network", ip: "192.168.1.9"
    redis5.vm.provision :shell, path: "install_redis.sh", args:["redis5","7004"]

    #web_config.vm.share_folder "SERVER", "/SERVER", SERVER_PATH
    #web_config.vm.share_folder "DATA", "/DEVELOPMENT", DEVELOPMENT_PATH
    #web_config.vm.forward_port 22, 2222
    #web_config.vm.forward_port 80, 4567
    # redis5_config.vm.network :hostonly, "192.168.0.100"
    #web_config.vm.customize ["modifyvm", :id, "--memory", 512]

    # apache.vm.provider "virtualbox" do |v|
    #     v.customize [ "modifyvm", :id, "--cpus", "1" ]
    #     v.customize [ "modifyvm", :id, "--memory", "600" ]
    # end
  end


  config.vm.define :"redis6" do |redis6|
    redis6.vm.box = "bento/centos-7.1"
    redis6.vm.hostname = "redis6"
    redis6.vm.network "private_network", ip: "192.168.1.10"
    redis6.vm.provision :shell, path: "install_redis.sh", args:["redis6","7005"]

    #web_config.vm.share_folder "SERVER", "/SERVER", SERVER_PATH
    #web_config.vm.share_folder "DATA", "/DEVELOPMENT", DEVELOPMENT_PATH
    #web_config.vm.forward_port 22, 2222
    #web_config.vm.forward_port 80, 4567
    # redis6_config.vm.network :hostonly, "192.168.0.100"
    #web_config.vm.customize ["modifyvm", :id, "--memory", 512]

    # apache.vm.provider "virtualbox" do |v|
    #     v.customize [ "modifyvm", :id, "--cpus", "1" ]
    #     v.customize [ "modifyvm", :id, "--memory", "600" ]
    # end
  end




  config.vm.box = "bento/centos-7.1"
  # Disable automatic box update checking. If you disable this, then
  # boxes will only be checked for updates when the user runs
  # `vagrant box outdated`. This is not recommended.
  # config.vm.box_check_update = false

  # Create a forwarded port mapping which allows access to a specific port
  # within the machine from a port on the host machine. In the example below,
  # accessing "localhost:8080" will access port 80 on the guest machine.
  # config.vm.network "forwarded_port", guest: 80, host: 8080

  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  # config.vm.network "private_network", ip: "192.168.33.10"

  # Create a public network, which generally matched to bridged network.
  # Bridged networks make the machine appear as another physical device on
  # your network.
  # config.vm.network "public_network"

  # Share an additional folder to the guest VM. The first argument is
  # the path on the host to the actual folder. The second argument is
  # the path on the guest to mount the folder. And the optional third
  # argument is a set of non-required options.
  # config.vm.synced_folder "../data", "/vagrant_data"

  # Provider-specific configuration so you can fine-tune various
  # backing providers for Vagrant. These expose provider-specific options.
  # Example for VirtualBox:
  #
  # config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  # end
  #
  # View the documentation for the provider you are using for more
  # information on available options.

  # Define a Vagrant Push strategy for pushing to Atlas. Other push strategies
  # such as FTP and Heroku are also available. See the documentation at
  # https://docs.vagrantup.com/v2/push/atlas.html for more information.
  # config.push.define "atlas" do |push|
  #   push.app = "YOUR_ATLAS_USERNAME/YOUR_APPLICATION_NAME"
  # end

  # Enable provisioning with a shell script. Additional provisioners such as
  # Puppet, Chef, Ansible, Salt, and Docker are also available. Please see the
  # documentation for more information about their specific syntax and use.
  # config.vm.provision "shell", inline: <<-SHELL
  #   sudo apt-get update
  #   sudo apt-get install -y apache2
  # SHELL
end
