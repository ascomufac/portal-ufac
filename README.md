<div align="center"><img alt="logo" src="https://raw.githubusercontent.com/plonegovbr/plonegovbr.portal/main/docs/logo.png" width="150" /></div>

<h1 align="center">PortalBrasil</h1>

Projeto de desenvolvimento do Portal Brasil

## Instalação

Clone este repositório

```bash
git clone git@github.com:plonegovbr/portal-brasil.git
```

Instale as dependências 

```bash
make install
```

## Inicie os servidores

Build do projeto

```bash
cd frontend
```

```bash
docker build . -t myfrontend:latest -f Dockerfile
```

Inicie o docker compose para rodar 

```bash
sudo docker compose up -d
```

## Pacotes em desenvolvimento

### Backend

Edite o arquivo `backend/mx.ini` e adicione / edite os pacotes e rode `make install-backend` novamente.

### Frontend

Edite o arquivo `frontend/mrs.developer.json` e adicione / edite os pacotes e rode `make install-frontend` novamente.
