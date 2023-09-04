# Turborepo starter

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `admin`: another [Next.js](https://nextjs.org/) app with [Tailwind CSS](https://tailwindcss.com/) (includes `packages/ui`)
- `api`: a [Nest.js](https://nestjs.com/) app
- `ui`: a stub React component library with [Shadcn UI](https://ui.shadcn.com/) and [Phosphor icons](https://phosphoricons.com/)
- `eslint-config-custom`: custom `eslint` configurations
- `tsconfig`: `tsconfig.json`s used throughout the monorepo
- `tailwind-config`: a shared `tailwind.config.js` for all apps and packages
- `prettier-config-custom`: a shared `prettier.config.js` for all apps and packages

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Building packages/ui

This example is setup to build `packages/ui` and output the transpiled source and compiled styles to `dist/`.

### Exporting only ShadCN UI components

If you want to export only ShadCN UI components, you can simply copy paste the `packages/ui` folder to your monorepo and adjust the the `tailwind.config.ts` to your needs.

### Utilities

This Turborepo has some additional tools already setup for you:

- [Tailwind CSS](https://tailwindcss.com/) for styles
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting
