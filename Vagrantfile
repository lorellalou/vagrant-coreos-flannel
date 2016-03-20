# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  
  config.vm.define "core01" do |config|
  	config.vm.provider :cloudstack do |cloudstack, override|
      cloudstack.api_key    = ENV['EXOSCALE_APIKEY']
      cloudstack.secret_key = ENV['EXOSCALE_SECRETKEY']
      
      cloudstack.host = "api.exoscale.ch"
      cloudstack.path = "/compute"
      cloudstack.port = "443"
      cloudstack.scheme = "https"
      cloudstack.template_id = "d2b76b81-d05e-4944-83cb-f5cef9c19ac1"
      cloudstack.network_id = "00304a04-c7ea-4e77-a786-18bc64347bf7"
      cloudstack.zone_id = "1128bd56-b4d9-4ac6-a7b9-c715b187ce11"
      cloudstack.network_type = "Basic"
      
      
      cloudstack.display_name = "core01"
      cloudstack.service_offering_name = "Tiny"
      cloudstack.security_group_names = ['default']
      cloudstack.keypair = "lrolaz@home"
      cloudstack.ssh_key = "~/.ssh/id_rsa"
      cloudstack.ssh_user = "core"
      
      cloudstack.user_data = File.read("user-data.config")
      override.vm.box = "dummy"
    end
  end
  
  config.vm.define "core02" do |config|
  	config.vm.provider :cloudstack do |cloudstack, override|
      cloudstack.api_key    = ENV['EXOSCALE_APIKEY']
      cloudstack.secret_key = ENV['EXOSCALE_SECRETKEY']
      
      cloudstack.host = "api.exoscale.ch"
      cloudstack.path = "/compute"
      cloudstack.port = "443"
      cloudstack.scheme = "https"
      cloudstack.template_id = "d2b76b81-d05e-4944-83cb-f5cef9c19ac1"
      cloudstack.network_id = "00304a04-c7ea-4e77-a786-18bc64347bf7"
      cloudstack.zone_id = "1128bd56-b4d9-4ac6-a7b9-c715b187ce11"
      cloudstack.network_type = "Basic"
      
      
      cloudstack.display_name = "core02"
      cloudstack.service_offering_name = "Tiny"
      cloudstack.security_group_names = ['default']
      cloudstack.keypair = "lrolaz@home"
      cloudstack.ssh_key = "~/.ssh/id_rsa"
      cloudstack.ssh_user = "core"
      
      cloudstack.user_data = File.read("user-data.config")
      override.vm.box = "dummy"
    end
  end
  
  config.vm.define "core03" do |config|
  	config.vm.provider :cloudstack do |cloudstack, override|
      cloudstack.api_key    = ENV['EXOSCALE_APIKEY']
      cloudstack.secret_key = ENV['EXOSCALE_SECRETKEY']
      
      cloudstack.host = "api.exoscale.ch"
      cloudstack.path = "/compute"
      cloudstack.port = "443"
      cloudstack.scheme = "https"
      cloudstack.template_id = "d2b76b81-d05e-4944-83cb-f5cef9c19ac1"
      cloudstack.network_id = "00304a04-c7ea-4e77-a786-18bc64347bf7"
      cloudstack.zone_id = "1128bd56-b4d9-4ac6-a7b9-c715b187ce11"
      cloudstack.network_type = "Basic"
      
      
      cloudstack.display_name = "core03"
      cloudstack.service_offering_name = "Tiny"
      cloudstack.security_group_names = ['default']
      cloudstack.keypair = "lrolaz@home"
      cloudstack.ssh_key = "~/.ssh/id_rsa"
      cloudstack.ssh_user = "core"
      
      cloudstack.user_data = File.read("user-data.config")
      override.vm.box = "dummy"
    end
  end    
 
   config.vm.define "core04" do |config|
  	config.vm.provider :cloudstack do |cloudstack, override|
      cloudstack.api_key    = ENV['EXOSCALE_APIKEY']
      cloudstack.secret_key = ENV['EXOSCALE_SECRETKEY']
      
      cloudstack.host = "api.exoscale.ch"
      cloudstack.path = "/compute"
      cloudstack.port = "443"
      cloudstack.scheme = "https"
      cloudstack.template_id = "d2b76b81-d05e-4944-83cb-f5cef9c19ac1"
      cloudstack.network_id = "00304a04-c7ea-4e77-a786-18bc64347bf7"
      cloudstack.zone_id = "1128bd56-b4d9-4ac6-a7b9-c715b187ce11"
      cloudstack.network_type = "Basic"
      
      
      cloudstack.display_name = "core04"
      cloudstack.service_offering_name = "Tiny"
      cloudstack.security_group_names = ['default']
      cloudstack.keypair = "lrolaz@home"
      cloudstack.ssh_key = "~/.ssh/id_rsa"
      cloudstack.ssh_user = "core"
      
      cloudstack.user_data = File.read("user-data.config")
      override.vm.box = "dummy"
    end
  end    
 
end
