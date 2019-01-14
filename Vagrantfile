config.vm.define "master" do |master|    
        master.vm.box = "centos/7"
        master.vm.network "private_network", type: "dhcp"
        master.vm.provider :virtualbox do |vb|
        	vb.customize ["modifyvm", :id, "--memory", 2048]
        	vb.customize ["modifyvm", :id, "--cpus", 2]
        end
    end
    config.vm.define "slave1" do |slave1|    
        slave1.vm.box = "centos/7"
        slave1.vm.network "private_network", type: "dhcp"
        slave1.vm.provider :virtualbox do |vb|
        	vb.customize ["modifyvm", :id, "--memory", 2048]
        	vb.customize ["modifyvm", :id, "--cpus", 2]
        end
    end
	config.vm.define "slave2" do |slave2|    
        slave2.vm.box = "centos/7"
        slave2.vm.network "private_network", type: "dhcp"
        slave2.vm.provider :virtualbox do |vb|
        	vb.customize ["modifyvm", :id, "--memory", 2048]
        	vb.customize ["modifyvm", :id, "--cpus", 2]
        end
    end
end
