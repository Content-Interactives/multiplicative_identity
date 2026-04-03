# Multiplicative Identity

React + Vite applet showing multiplicative identity: multiplying by one preserves value. Interaction and feedback are implemented in `MultiplicativeIdentity.jsx`.

**Live site:** [https://content-interactives.github.io/multiplicative_identity](https://content-interactives.github.io/multiplicative_identity)

Curriculum alignment and placement: [Standards.md](Standards.md).

---

## Stack

| Layer | Notes |
|--------|--------|
| Build | Vite 6, `@vitejs/plugin-react` |
| UI | React 19 |
| Styling | Tailwind 3 |
| Icons | lucide-react |
| Deploy | `gh-pages -d dist`; `predeploy` runs `vite build` |

---

## Layout

```
vite.config.js          # base: '/multiplicative_identity/'
src/
  main.jsx → App.jsx → components/MultiplicativeIdentity.jsx
  components/ui/
```

---

## `vite.config.js`

`base: '/multiplicative_identity/'` must match the GitHub Pages repository path.

---

## Scripts

| Command | Purpose |
|---------|---------|
| `npm run dev` | Vite dev server |
| `npm run build` | Production build → `dist/` |
| `npm run preview` | Preview production build |
| `npm run lint` | ESLint |
| `npm run deploy` | Build and push `dist/` to `gh-pages` |

---

## Embedding

Uses shared layout wrappers; see `MultiplicativeIdentity.jsx` for dimensions.
