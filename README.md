# Desafio projeto Vagrant

<div align="left"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vagrant/vagrant-original.svg" height="30" alt="vagrant logo"  />  
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain.svg" height="30" alt="ubuntu logo"  />
</div>

 Desafio: Criar uma máquina virtual usando Vagrant com o sistema operacional Ubuntu 20.04, onfigurar a máquina com recursos específicos, sincronizar uma pasta local com a máquina virtual e versionar o projeto no GitHub.  

 ###

Para iniciar a máquina virtual utilize o comando:  
`vagrant up`

Após criar a máquina acesse via SSH utilizando o comando:  
`vagrant ssh`

A pasta com nome "compartilhado" será compartilhada com a vm criada pelo Vagrantfile, assim todo arquivo que for colocado no host dentro dessa pasta, sera acessivel na vm no caminho:  
`/desafio-projeto-vagrant/compartilhado`
