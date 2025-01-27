# Vagrantfile para configurar uma VM Ubuntu 20.04
Vagrant.configure("2") do |config|
    # Define a box oficial do Ubuntu 20.04
    config.vm.box = "ubuntu/focal64"
  
    # Define o nome da máquina virtual
    config.vm.define "vm-desafio-vagrant" do |ubuntu_vm|
      ubuntu_vm.vm.hostname = "vm-desafio-vagrant"
  
      # Configuração de rede em modo bridge
      ubuntu_vm.vm.network "public_network"
  
      # Configuração de sincronização de pastas
      ubuntu_vm.vm.synced_folder "./compartilhado", "/desafio-projeto-vagrant/compartilhado"
  
      # Configuração de recursos
      ubuntu_vm.vm.provider "virtualbox" do |vb|
        vb.memory = "1024" # Memória RAM de 1 GB
        vb.cpus = 1        # 1 núcleo de CPU
      end
    end
  end