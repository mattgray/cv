# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provision "shell", inline: "apt-get update && apt-get install -y --no-install-recommends texlive texlive-latex-extra tex-gyre pandoc lmodern git-core"
end
