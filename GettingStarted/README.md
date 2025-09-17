# Getting Started

## VS Code Extension

Install the official VS Code extension: `Prisma`. This provides syntax highlighting, auto-completion, and other essential features.

## General steps for a new project

Read [here](https://www.prisma.io/docs/getting-started) for the getting started info with Prisma. Select your prefered database and follow the steps.

With PostgreSQL it should be:

- `npm install prisma --save-dev` - assuming you already have package.json and TypeScript ready. Otherwise run the full commands from the docs.
- `npx prisma init --datasource-provider postgresql --output ../generated/prisma` - creates the initial Prisma setup. This will create a `prisma` folder and a `.env` file.

You now have a ready-to-use Prisma setup!
