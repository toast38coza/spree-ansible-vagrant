VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
    config.vm.box = "hashicorp/precise32"
    
    config.vm.network :public_network

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "spree.yml"
    end
end
