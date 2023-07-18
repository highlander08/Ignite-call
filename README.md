💻 About
Application that connects your calendar and allows people to book appointments in their free time. The Design System was used creating in the previous project.

 Authenticated routes in Next.js.
 Authentication with Next Auth.
 Validation with zod.
 Integration with Google Calendar
 Integration with Design System
Although there are few features, concepts such as:

States
State immutability
Lists and keys in ReactJS
Properties
Componentization

🛠 Tech Stack
This project was developed with the following technologies:

React
Next
Next-Auth
Next-seo
Nookies
React-hook-form
Zod
TypeScript
Stitches
Phosphor-react
Radix-u
Axios
Prisma
@ignite-ui-exo/react
React-query
Dayjs
Googleapis

🔖 Layout
You can view the layout of the project via the link below:

Layout Web



# Ignite-call


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
















