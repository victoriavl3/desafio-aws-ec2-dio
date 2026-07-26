# Desafio de Projeto: Criação e Uso de Instâncias EC2 com AMI customizada

Este repositório contém o planejamento, documentação e os artefatos do desafio de projeto desenvolvido durante o curso na DIO. O objetivo principal é compreender na prática o funcionamento, criação e aplicação de imagens AMI no Amazon EC2.

## 📋 Objetivo do Projeto
O escopo deste projeto consiste em realizar a criação de uma instância EC2 na AWS utilizando o sistema operacional Windows Server. Após a inicialização e validação da máquina virtual, o objetivo é efuatr a captura dessa configuração através de uma Amazon Machine Image (AMI) personalizada e validar a criação de uma nova instância a partir da imagem gerada.

## 🚀 Tecnologias Planejadas
* **AWS (Amazon Web Services)**
* **Amazon EC2 (Elastic Compute Cloud)**
* **Amazon Machine Image (AMI)**
* **Microsoft Windows Server**

## 🛠️ Escopo Técnico do Laboratório

### 1. Planejamento da Instância Inicial
* Seleção da AMI oficial da Microsoft para Windows Server (elegível para o nível gratuito).
* Configuração do tipo de instância (t2.micro) e definição do armazenamento padrão para o Windows Server.
* Configuração do Security Group garantindo a liberação da porta RDP (3389) para posterior acesso remoto.

### 2. Geração da AMI Customizada
* Interrupção da instância inicial após o primeiro boot para garantir a integridade do volume.
* Criação de uma nova imagem AMI personalizada a partir da máquina Windows configurada.

### 3. Validação do Processo
* Inicialização de uma nova instância EC2 utilizando a AMI customizada criada.
* Teste de replicação para garantir que o modelo Windows foi gerado corretamente.

## 📸 Evidências (A serem adicionadas após a execução)
* Os prints das telas da AWS serão armazenados na pasta `/images` assim que o laboratório for executado no console da AWS.

## 👤 Autor
* Victoria Camilly
