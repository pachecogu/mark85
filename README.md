Mark85 Robot Express

Este repositório contém a aplicação web "mark85" a ser instalada para possibilitar executar os testes automatizados do projeto "mark85-robot-express".
Pré-requisitos

Certifique-se de que as seguintes ferramentas estão instaladas no seu sistema:

1. Git: Para clonar o repositório.
   - Download Git: https://git-scm.com/downloads
2. Node.js: Para rodar o servidor web.
   - Download Node.js: https://nodejs.org/

Configuração do Ambiente

ACESSAR O GIT BASH

Abra o terminal Git Bash no seu computador.
CRIAR E ACESSAR O DIRETÓRIO

Execute os comandos:
mkdir -p /c/QAx/projects/
cd /c/QAx/projects/
CLONAR O REPOSITÓRIO

Execute o comando:
git clone https://github.com/pachecogu/mark85-robot-express.git
INSTALAR DEPENDÊNCIAS

Navegue até a pasta do projeto e instale os requisitos:
cd mark85-robot-express
pip install -r requirements.txt
EXECUTAR OS TESTES

Execute o comando:
robot -d ./logs ./tests
