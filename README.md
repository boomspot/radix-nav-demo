# Next.js 15 Project with Radix Navigation

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app), featuring a custom Radix Navigation menu implementation with SCSS styling.

## Features

- Next.js 15
- Radix UI Navigation Menu with SCSS modules
- Development branch showing how to set navigation menu items open by default
- [Geist](https://vercel.com/font) font integration

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

## Development Notes

### Navigation Menu

The project includes a custom Radix Navigation menu implementation located in `src/components/RadixNavigation.jsx` with styles in `src/styles/radixnav.module.scss`.

### Development Branch

Check out the `menu-default-open` branch to see how to configure the Radix Navigation menu to be open by default during development:

```bash
git checkout menu-default-open
```

This can be particularly useful during the development phase when working on menu styling and content.

## Learn More

To learn more about Next.js and Radix UI, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Radix UI Documentation](https://www.radix-ui.com/docs/primitives/overview/introduction) - learn about Radix UI components
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
