# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname
  }
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## Usman's Notes:

- http://localhost:5173/
- https://www.youtube.com/watch?v=_W3R2VwRyF4&list=PL6QREj8te1P6wX9m5KnicnDVEucbOPsqR | Time stamp: 41:50
- Next project: https://www.youtube.com/watch?v=0fYi8SGA20k&list=PL6QREj8te1P6wX9m5KnicnDVEucbOPsqR&index=3

Tools:

- reactJS : https://react.dev/
- appwrite : https://cloud.appwrite.io - Login using GitHub
- Vite : https://vitejs.dev/ - Frontend Tooling
- tailwindcss : https://tailwindcss.com/
- shadcn : https://ui.shadcn.com/ - React component library
