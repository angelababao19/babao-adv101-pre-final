This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/pages/api-reference/create-next-app).

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

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/pages/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn-pages-router) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/pages/building-your-application/deploying) for more details.

---

## To-Do App (this project)

This workspace now contains a simple client-side To-Do application at `src/pages/index.js` with these features:

- Create tasks
- Update/edit tasks
- Delete tasks
- Mark tasks complete / incomplete
- Filter by **To Do** and **Completed** tabs
- Search tasks by text
- Local persistence using `localStorage`

### Run locally

Use one of the package manager scripts:

```powershell
npm install
npm run dev
# then open http://localhost:3000
```

### Deploy to Vercel

1. If you don't have the Vercel CLI, install it (optional):

```powershell
npm i -g vercel
```

2. From the repo root run:

```powershell
vercel login
vercel
```

Follow the interactive prompts; Vercel will detect this is a Next.js app and deploy it.

Alternatively, use the Vercel dashboard: connect your GitHub repository and deploy the `main` branch.

After deployment, your app will be live on a Vercel URL. Any changes pushed to the connected branch will trigger automatic redeploys.

