Vagrant.configure("2") do |config|
  config.hostmanager.enabled = true 
  config.hostmanager.manage_host = true
  
### Ansible Host vm-1 ###
  config.vm.define "vm01" do |vm01|
    vm01.vm.box = "ubuntu/bionic64"
    vm01.vm.hostname = "vm01"
	vm01.vm.network "private_network", ip: "192.168.56.50"
  end
  
# ### Ansible Client vm-2 ###
#    config.vm.define "vm02" do |vm02|
#     vm02.vm.box = "geerlingguy/centos7"
#     vm02.vm.hostname = "vm02"
#     vm02.vm.network "private_network", ip: "192.168.56.51"
# 	vm02.vm.provider "virtualbox" do |vb|
#      vb.memory = "1024"
# 	 end
#    end
   
# ### Ansible Client vm-3 ####
#   config.vm.define "vm03" do |vm03|
#     vm03.vm.box = "geerlingguy/centos7"
# 	  vm03.vm.hostname = "vm03"
#     vm03.vm.network "private_network", ip: "192.168.56.52"
#   end 
 end
