# -*- mode: ruby -*-
# vi: set ft=ruby : 


# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.define "centos7vm1" do |centos7vm1|
    centos7vm1.vm.box = "centos/7"
    centos7vm1.vm.hostname = "vm1"
    centos7vm1.vm.network "forwarded_port" , host: 8080, guest:80, auto_correct: true
end
end
  
Vagrant.configure("2") do |config|

  config.vm.define "centos7vm2" do |centos7vm2|
    centos7vm2.vm.box = "centos/7"
    centos7vm2.vm.hostname = "vm2"
    centos7vm2.vm.network "forwarded_port" , host: 3030, guest:80, auto_correct: true


end
end
  
  #config.vm.box = "centos/7"
  #config.vm.network "forwarded_port", guest: 80, host: 1235
  #config.vm.network "forwarded_port", guest: 80, host: 1234
   
