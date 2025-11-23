This is a minimal reproduction for https://github.com/remix-run/react-router/issues/14587. The goal is to prerender a static site that can be served by a static file server (e.g. Apache) under a subdirectory, e.g. `example.com/test/`.

The default README has been renamed to `FRAMEWORK.md`. Other than that, the only files that have been changed are `vite.config.ts` and `react-router.config.ts`.

To reproduce, run

```
npm run build && vite preview
```

and then navigate to http://localhost:4173/test/
