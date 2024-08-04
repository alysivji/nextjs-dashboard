# Next.js App -- Dashboard

[course](https://nextjs.org/learn)

## Getting Started

```console
pnpm i
pnpm run dev
```

Left off here --
https://nextjs.org/learn/dashboard-app/setting-up-your-database

## Notes

- Folder structure
  - /app: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
  - /app/lib: Contains functions used in your application, such as reusable utility functions and data fetching functions.
  - /app/ui: Contains all the UI components for your application, such as cards, tables, and forms.
  - /public: Contains all the static assets for your application, such as images.
  - Config Files: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app.
- styling
  - app/ui/global.css -- global styles
    - add this at top level tsx
  - [clsx](https://www.npmjs.com/package/clsx) library lets us toggle class names easily

## Further Reading

- ORMS
  - [prisma](https://www.prisma.io/)
  - [drizzle](https://orm.drizzle.team/)
