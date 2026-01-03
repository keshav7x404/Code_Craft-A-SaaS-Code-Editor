<h1 align="center">✨ SaaS Code Editor - Next.js 15 ✨</h1>

![Demo App](/public/screenshot-for-readme.png)

[Watch Full Tutorial on Youtube](https://youtu.be/fGkRQgf6Scw)

Highlights:

- 🚀 Tech stack: Next.js 15 + Convex + Clerk + TypeScript
- 💻 Online IDE with multi-language support (10 languages)
- 🎨 Customizable experience with 5 VSCode themes
- ✨ Smart output handling with Success & Error states
- 💎 Flexible pricing with Free & Pro plans
- 🤝 Community-driven code sharing system
- 🔍 Advanced filtering & search capabilities
- 👤 Personal profile with execution history tracking
- 📊 Comprehensive statistics dashboard
- ⚙️ Customizable font size controls
- 🔗 Webhook integration support
- 🌟 Professional deployment walkthrough

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

### Add these env to Convex Dashboard

```js
CLERK_WEBHOOK_SECRET=
LEMON_SQUEEZY_WEBHOOK_SECRET=
```

### Run the app

```shell
npm run dev
```
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
