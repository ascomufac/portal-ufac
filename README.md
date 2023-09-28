<div align="center"><img alt="logo" src="https://raw.githubusercontent.com/plonegovbr/plonegovbr.portal/main/docs/logo.png" width="150" /></div>

<h1 align="center">PortalBrasil</h1>
Projeto de FrontEnd do Portal da UFAC

## Como atualizar

Clone este repositório

```bash
git clone https://github.com/ascomufac/portal-ufac.git
```

Instale as dependências 

```bash
make install
```

volta a pasta raiz
```bash
cd ..
``` 
## Notas

Gerar imagem do frontend

```bash
sudo docker build . -t veridianobarroso/front-ufac:latest -f Dockerfile
```
```bash
sudo docker image push veridianobarroso/front-ufac
```
