# Desafio projeto Vagrant

![vagrant-logo_large](https://github.com/user-attachments/assets/5f3f4b28-1e5f-4aab-af42-0adf73e4015d)

 Desafio: Criar uma máquina virtual usando Vagrant com o sistema operacional Ubuntu 20.04, onfigurar a máquina com recursos específicos, sincronizar uma pasta local com a máquina virtual e versionar o projeto no GitHub.  

 ###

Para iniciar a máquina virtual utilize o comando:  
`vagrant up`

Após criar a máquina acesse via SSH utilizando o comando:  
`vagrabt ssh`

A pasta com nome "compartilhado" será compartilhada com a vm criada pelo Vagrantfile, assim todo arquivo que for colocado no host dentro dessa pasta, sera acessivel na vm no caminho:  
`/desafio-projeto-vagrant/compartilhado`
