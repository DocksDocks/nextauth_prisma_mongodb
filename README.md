# NextAuth with MongoDB, Prisma and Google Provider project

## .env 

Configure the .env based on .env.example

## Prisma

generate prisma
```
npx prisma generate
```
and push the collections to your database
```
npx prisma db push
```

## Google 

google callback urls:
http://localhost:3000/api/auth/callback/google
http://localhost:3000/auth/callback/google

## Documentation used:

- [NextJS](https://nextjs.org/docs/getting-started/installation)

- [AuthJS (NextAuth)](https://authjs.dev/getting-started/installation?framework=Next.js)
  
- [AuthJS Google Provider](https://authjs.dev/getting-started/providers/google)
  
- [Google Cloud OAuth](https://console.cloud.google.com/apis/credentials)
  
- [AuthJS Prisma Adapter](https://authjs.dev/getting-started/adapters/prisma)
  
- [MongoDB](https://cloud.mongodb.com/)




Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

