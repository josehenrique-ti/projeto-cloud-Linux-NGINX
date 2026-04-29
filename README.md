# Projeto Cloud Azure - Linux + NGINX

## Descrição
Este projeto tem como objetivo demonstrar, na prática, a implementação de uma infraestrutura em nuvem utilizando Microsoft Azure.

Foi criada uma máquina virtual Linux (Ubuntu), configurado acesso remoto via SSH, regras de segurança de rede (NSG) e implantado um servidor web com NGINX, realizando o deploy de uma aplicação HTML.

---

## Arquitetura

- Máquina Virtual: Ubuntu Linux
- IP Privado: 10.0.0.5
- IP Público: 52.156.109.93
- Rede: Azure Virtual Network (VNet)
- Servidor Web: NGINX

---

## Serviços Utilizados

- SSH (porta 22)
- HTTP (porta 80)
- NGINX (Web Server)
- Azure NSG (Firewall)

---

## Configurações Realizadas

- Criação da VM no Microsoft Azure  
- Configuração de acesso remoto via SSH  
- Liberação de portas no NSG (22 e 80)  
- Instalação e configuração do NGINX  
- Alteração do diretório root do servidor web  
- Deploy de página HTML personalizada  

---

## Segurança

- Controle de acesso via NSG  
- Liberação apenas das portas necessárias  
- Testes de conectividade e acesso externo  

---

## Desafios Encontrados

Durante o desenvolvimento do projeto, enfrentei desafios relacionados a:

- Liberação de portas no Azure (NSG)  
- Acesso remoto via SSH  
- Configuração correta do NGINX  
- Estruturação de diretórios no Linux  

Esses desafios contribuíram para consolidar conhecimentos práticos em redes, Linux e cloud computing.

---

## Resultados

- Servidor web funcional acessível via IP público  
- Ambiente configurado manualmente do zero  
- Estrutura pronta para expansão (novos serviços ou aplicações)  

---

## Autor

José Henrique  
