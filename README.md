# Projeto DevOps com Vagrant

## Descrição

Este projeto apresenta uma estrutura DevOps para implantação de uma aplicação em maquinas virtuais usando Vagrant. O Vagrant é uma ferramenta de automação de provisionamento de máquinas virtuais, facilitando a criação e configuração de ambientes de desenvolvimento.

## Requisitos

- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) (ou outro provedor de VMs suportado pelo Vagrant)

# Como Usar
Clone este repositório:
- $ git clone https://github.com/seu-username/devops-vagrant.git
- $ cd devops-vagrant

Inicie as máquinas virtuais::
- $ vagrant up

Aguarde até que a configuração das máquinas virtuais seja concluída.

Acesse a aplicação em http://localhost:PORTA (substitua PORTA pela porta configurada na aplicação).

# Personalização

Configurações da Máquina Virtual: Você pode personalizar as configurações das máquinas virtuais no arquivo Vagrantfile. Consulte a documentação do Vagrant para mais informações.
