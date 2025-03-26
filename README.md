Mark85 Robot Express

Este repositório contém a aplicação web "mark85" a ser instalada para possibilitar executar os testes automatizados do projeto "mark85-robot-express".
Pré-requisitos

Certifique-se de que as seguintes ferramentas estão instaladas no seu sistema:

1. Git: Para clonar o repositório.
   - Download Git: https://git-scm.com/downloads
2. Node.js: Para rodar o servidor web.
   - Download Node.js: https://nodejs.org/

Configuração do Ambiente

1. ACESSAR O GIT BASH
   - Abra o terminal Git Bash no seu computador.

2. CRIAR E ACESSAR O DIRETÓRIO

   - Execute os comandos:
      - mkdir -p /c/QAx/apps/
      - cd /c/QAx/apps/

3. CLONAR O REPOSITÓRIO
   - Execute o comando:
      - git clone 

4. INSTALAR DEPENDÊNCIAS
   - Navegue até a pasta do projeto e instale os requisitos:
      - cd mark85-robot-express
      - pip install -r requirements.txt

5. EXECUTAR OS TESTES
    - Execute o comando:
       - robot -d ./logs ./tests
   
