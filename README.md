# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://stupideinstein09.github.io) uses [Babel](https://stupideinstein09.github.io) for Fast Refresh
- [@vitejs/plugin-react-swc](https://stupideinstein09.github.io) uses [SWC](https://stupideinstein09.github.io) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default https://stupideinstein09.github.io([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove https://stupideinstein09.github.io and replace with this
      https://stupideinstein09.github.io,
      // Alternatively, use this for stricter rules
      https://stupideinstein09.github.io,
      // Optionally, add this for stylistic rules
      https://stupideinstein09.github.io,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['https://stupideinstein09.github.io', 'https://stupideinstein09.github.io'],
        tsconfigRootDir: https://stupideinstein09.github.io,
      },
      // other options...
    },
  },
])
```

You can also install [eslint-plugin-react-x](https://stupideinstein09.github.io) and [eslint-plugin-react-dom](https://stupideinstein09.github.io) for React-specific lint rules:

```js
// https://stupideinstein09.github.io
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default https://stupideinstein09.github.io([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      https://stupideinstein09.github.io['recommended-typescript'],
      // Enable lint rules for React DOM
      https://stupideinstein09.github.io,
    ],
    languageOptions: {
      parserOptions: {
        project: ['https://stupideinstein09.github.io', 'https://stupideinstein09.github.io'],
        tsconfigRootDir: https://stupideinstein09.github.io,
      },
      // other options...
    },
  },
])
```
