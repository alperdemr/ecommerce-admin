This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Used Techs
```
DB:NeonDB
ORM:Prisma
Auth:Clerk
State Management:Zustand
```


## Clone the repository

```bash
git clone https://github.com/alperdemr/ecommerce-admin.git

```

## Install packages

```bash
npm install

```

## Create .env file

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

```

## Connect to NeonDB and Push Prisma

```bash
npx prisma generate
npx prisma db push
```
## Start the app
```bash
npm run dev
```


