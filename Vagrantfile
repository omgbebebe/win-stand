# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.require_plugin "vagrant-reload"

Vagrant.configure("2") do |config|
  config.vm.box = "universalvishwa/windows-2008-r2-standard-x64"

  config.vm.hostname = "windc"
  config.vm.communicator = "winrm"

  config.vm.provision :reload

end