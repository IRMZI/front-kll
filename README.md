# front-kll

Site da Sul Coleta + Coopersul (Portão/RS). Versão inicial: página estática.

- `public/` — HTML e imagens
- `Dockerfile` + `nginx.conf` — nginx servindo na porta 3000 (deploy no Coolify)

Rodar local: `docker build -t front-kll . && docker run -p 3000:3000 front-kll`
