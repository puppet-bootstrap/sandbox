# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"

  config.vm.provision "shell", inline: <<-SHELL
    yum -y install http://yum.puppet.com/puppet5/puppet-release-el-7.noarch.rpm
    yum -y install puppet-agent
  SHELL
end
