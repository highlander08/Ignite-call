
# Ignite-call

![ignite-call](https://github.com/highlander08/Ignite-call/assets/38596921/15b658db-fd64-4fdf-8f67-b6bad9e90b7d)


demo: https://ignite-call-weld.vercel.app/

instalar dependencias -> npm i @prisma/client e npm i prisma

# 1 - usar sqlite

npm run dev

obs: INICIAR O PRISMA NA MAQUINA
-npx prisma init --datasource-provider SQLite

obs: apaga as migrations que existe e roda novamente esse comando para rodar migrations e ver as mudanças no banco
ler schema e rodar migrate
- npx prisma migrate dev

ver banco - http://localhost:5555/
npx prisma studio

2 - usar mysql

npm run dev

obs: INICIAR O PRISMA NA MAQUINA
- npx prisma init --datasource-provider mysql



obs: apaga as migrations que existe e roda novamente esse comando para rodar migrations e ver as mudanças no banco
ler schema e rodar migrate
-  npx prisma migrate dev --name init
-  
-  ou tente isso se nao der certo
-  prisma migrate dev --create-only
-   npx prisma migrate dev 

subir banco no local com mysql
.env -> DATABASE_URL="mysql://root:@senha@localhost:3306/ignitecall"
docker run --name mysql -e MYSQL_ROOT_PASSWORD=@senha -p 3306:3306 mysql:latest


ver banco - http://localhost:5555/
npx prisma studio
















