# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "mdiazn80/kali-arm64"
  config.vm.box_version = "2023.3"

  config.vm.synced_folder "./data", "/vagrant", SharedFoldersEnableSymlinksCreate: false

  config.vm.provider "vmware_desktop" do |vm|
    vm.gui = false
    vm.cpus = 4
    vm.memory = "4096"
  end
end
