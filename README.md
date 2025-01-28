# **Desafio: Provisionamento de VM com Vagrant**

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vagrant/vagrant-original.svg" height="30" alt="vagrant logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain.svg" height="30" alt="ubuntu logo" />
</div>

## **Descrição**
Este projeto tem como objetivo a criação e configuração de uma máquina virtual utilizando Vagrant com o sistema operacional Ubuntu 20.04. O desafio inclui configurar recursos específicos da máquina, sincronizar uma pasta local com a VM e versionar o projeto no GitHub.

---

## **Pré-requisitos**
Antes de iniciar, certifique-se de ter instalado:
- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/)
- Git Bash (para usuários Windows) ou Terminal no Linux/macOS

---

## **Passos para Execução**

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/williampaludo/vagrant-ubuntu.git
   cd vagrant-ubuntu
   ```

2. Inicie a máquina virtual com o comando:
   ```bash
   vagrant up
   ```

3. Após a criação da máquina, acesse-a via SSH:
   ```bash
   vagrant ssh
   ```

---

## **Sincronização de Pastas**
A pasta compartilhada chamada `compartilhado` será sincronizada entre o host e a VM. Qualquer arquivo adicionado a essa pasta no host estará acessível na VM no seguinte diretório:
```bash
/desafio-projeto-vagrant/compartilhado
```

---

## **Conclusão**
Este projeto demonstra a configuração básica de uma máquina virtual usando Vagrant, a sincronização de arquivos e a padronização de ambientes. Caso tenha dúvidas ou sugestões, sinta-se à vontade para contribuir ou abrir uma issue.

