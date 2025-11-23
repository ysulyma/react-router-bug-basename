This is a minimal reproduction of a bug in React Router related to prerendering with `basename`.

The default README has been renamed to `FRAMEWORK.md`. Other than that, the only files that have been changed are `vite.config.ts` and `react-router.config.ts`.

To reproduce, run

```
npm run build && vite preview
```

and then navigate to http://localhost:4173/test/
