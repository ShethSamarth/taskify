# Taskify (Trello Clone)

This is a repository for Fullstack Trello Clone: Next.js 14, React, Server Actions, TailwindCSS, ShadCN UI, Stripe.

Key Features:

- Clerk Authentication
- Clerk Organization
- Board creation
- Unsplash API for random beautiful cover images
- Activity log for entire organization
- Board rename and delete
- List creation
- List rename, delete, drag & drop reorder and copy
- Card creation
- Card description, rename, delete, drag & drop reorder and copy
- Card activity log
- Board limit for every organization
- Stripe subscription for each organization to unlock unlimited boards
- Landing page
- MongoDB
- Prisma ORM
- ShadcnUI & TailwindCSS
- Full mobile responsiveness

# Final Version

To visit the website, [click here.](https://taskify-ss.vercel.app)

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/taskify.git
```

### Install packages

```shell
npm install
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_APP_URL=
```

### Setup prisma

```shell
npx prisma db push
```

### Start the app

```shell
npm run dev
```
