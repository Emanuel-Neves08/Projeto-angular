# Projeto Angular

Este é um projeto web desenvolvido com **Angular** no frontend e **Node.js** no backend. A aplicação demonstra integração entre frontend e backend, consumo de APIs REST e uma interface responsiva, utilizando tecnologias modernas.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- Node.js (versão 18.x ou superior)
- Angular CLI (versão ^19.2.6)
- npm (vem junto com o Node.js)

## Instalação

Clone o repositório e instale as dependências:

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DA_PASTA>
npm install
```

## Rodando a aplicação

### 1. Iniciar o servidor da API (backend)

Execute o comando abaixo para iniciar o backend:

```bash
npm run api
```

O servidor da API estará disponível em: `http://localhost:3001`

Caso a porta 3001 já esteja em uso, verifique qual processo está utilizando com:

```bash
netstat -ano | findstr :3001
```

E finalize o processo caso necessário.

### 2. Iniciar o frontend Angular

Em outro terminal (mesma pasta do projeto), rode:

```bash
npm start
```

O frontend Angular estará disponível em: `http://localhost:4200`

## Estrutura do Projeto

O projeto é organizado da seguinte forma:

- **Frontend**: Aplicação Angular com interface responsiva
- **Backend**: API REST desenvolvida em Node.js
- **Integração**: Comunicação entre frontend e backend via HTTP

## Tecnologias Utilizadas

- **Frontend**: Angular 19.2.6
- **Backend**: Node.js
- **Gerenciador de Pacotes**: npm
- **Arquitetura**: REST API

## Portas Utilizadas

- Frontend Angular: `http://localhost:4200`
- Backend API: `http://localhost:3001`

## Comandos Úteis

- `npm install` - Instala as dependências do projeto
- `npm start` - Inicia o frontend Angular
- `npm run api` - Inicia o servidor backend
- `netstat -ano | findstr :3001` - Verifica processos na porta 3001