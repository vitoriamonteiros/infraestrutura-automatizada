# Desafio AWS CloudFormation - DIO

## Sobre o projeto
Neste desafio, meu objetivo foi implementar uma infraestrutura automatizada utilizando **AWS CloudFormation**, aplicando conceitos de **Infraestrutura como Código (IaC)**.  

A atividade me permitiu explorar a criação, configuração e gerenciamento de recursos na AWS de forma padronizada e replicável, simulando cenários reais de provisionamento de infraestrutura em nuvem. Trabalhei com **instâncias EC2**, **Security Groups**, **volumes EBS** e scripts de inicialização (UserData) para automatizar a configuração de servidores web.

---

## Objetivos de Aprendizagem
- Aplicar conceitos de CloudFormation em um ambiente prático.
- Criar templates em **YAML ou JSON** para automatizar recursos AWS.
- Documentar processos técnicos de forma clara e organizada.
- Entender e aplicar boas práticas de replicação, padronização e segurança na infraestrutura.
- Compartilhar o conhecimento usando **GitHub** como ferramenta de versionamento.

---

## Passo a Passo da Experiência

### 1. Preparação
- Configurei o **AWS CLI** e organizei o repositório no GitHub.
- Planejei os recursos da Stack:
  - Número de instâncias EC2.
  - Configurações de Security Groups.
  - Servidores web a serem configurados via UserData.

### 2. Criação do template CloudFormation
- Desenvolvi o arquivo YAML contendo:
  - Definição das instâncias EC2.
  - Configuração de Security Groups (entrada e saída).
  - Provisionamento de volumes EBS.
  - Scripts de inicialização (UserData) para instalar e configurar o servidor web automaticamente.
- Validei o template utilizando o **console da AWS** e o **CLI**, garantindo que não houvesse erros.

### 3. Deploy da Stack
- Criei a Stack pelo CloudFormation.
- Monitorei o progresso pelo console e logs.
- Testei o acesso às instâncias EC2 via SSH e verifiquei se o servidor web estava funcionando corretamente.

### 4. Aprendizados
- Compreendi a importância de organizar os recursos e gerenciar dependências no CloudFormation.
- Aprendi a reutilizar templates e aplicar versionamento para facilitar futuras atualizações.
- Percebi como a automação reduz o risco de erros manuais e acelera a replicação de ambientes.


--