This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

## Resources
https://www.youtube.com/watch?v=Zq5fmkH0T78&t=412s
https://authjs.dev/getting-started/installation
https://authjs.dev/getting-started/providers/github
https://authjs.dev/getting-started/authentication/oauth
https://github.com/settings/apps

https://ui.shadcn.com/docs/cli
https://www.sanity.io/
https://www.sanity.io/manage/personal/projects
https://www.sanity.io/docs/groq
https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering
https://react.dev/reference/react/useActionState 

`npx sanity@latest schema extract --path=./sanity/extract.json`
`npx sanity@latest typegen generate`
- update package.json: predev, prebuild, typegen, overrides, packagemanager

`npm i server-only`

- update nextconfig with ppr, dev indicators (buildactivity, buildactivityposition, appisrstatus)

`npm i next@canary`
`npm i markdown-it`
`npm i --save-dev @types/markdown-it`
`npm i @uiw/react-md-editor`

https://www.sanity.io/manage/personal/project/l0eyp1tv/api - add api token; update sanity env.ts
sanity/lib/write-client.ts

https://nextjs.org/docs/canary/app/api-reference/functions/unstable_after
- update nextconfig
ISR = incremental static regeneration

CACHE NEXTJS