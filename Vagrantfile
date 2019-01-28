Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "forwarded_port", guest: 80, host: 8086
  ####### Provision #######
  config.vm.provision "file", source: "secrets/", destination: "~/ubuntu/nginx-ssl"
  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "provision/app.yml"
    ansible.verbose = true
  end
end
