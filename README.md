# Skeleton Vike

This is an example project to showcase/test if Vike is a suitable option for our agnostic sandbox environments.

Structure:

```
├── package.json
├── pnpm-lock.yaml
├── README.md
├── src
|  ├── components
|  |  └── Counter.tsx
|  └── pages
|     ├── +config.ts
|     └── index
|        └── +Page.tsx
├── tsconfig.json
└── vite.config.ts
```

Notes:
- `src/components` - Our library, this could also be `src/lib` if we want, Vike has no opinion on this.
- `src/pages` - Our routes, this `pages` directory is mandatory for Vike to recognize, it can be placed anywhere though, Vike will just traverse our project and look for a `pages` folder.