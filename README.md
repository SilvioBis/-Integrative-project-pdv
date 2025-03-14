# PDV - Ponto de Venda

Este é um sistema de Ponto de Venda (PDV) desenvolvido com Node.js (backend), React.js (frontend) e PostgreSQL (banco de dados).

## Pré-requisitos

- Node.js (v18 ou superior)
- npm (v9 ou superior)
- PostgreSQL (v14 ou superior)

1. Instalação do Node.js e npm
O Node.js é necessário para executar o backend (Node.js + Express.js) e o frontend (React.js).

No Ubuntu:
Abra o terminal.

Instale o Node.js e o npm:

sudo apt update
sudo apt install nodejs npm

Verifique a instalação:
node -v
npm -v

No Windows:
Baixe o instalador do Node.js no site oficial: https://nodejs.org/.

Siga as instruções do instalador.

Verifique a instalação no Prompt de Comando:

node -v
npm -v

Instalação do PostgreSQL
O PostgreSQL será o banco de dados do projeto.

No Ubuntu:
Instale o PostgreSQL:

sudo apt update
sudo apt install postgresql postgresql-contrib

Inicie o serviço do PostgreSQL:

sudo service postgresql start