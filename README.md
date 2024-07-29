<div style="display: flex; justify-content: space-between;">
  <p align="center">
    <a href="https://react.dev/" target="blank"><img src="public/react.svg" width="200" alt="React Logo"/></a>
  </p>
  
  <p align="center">
    <a href="https://vitejs.dev/" target="blank"><img src="public/vite.svg" width="200" alt="Vite Logo"/></a>
  </p>

  <p align="center">
    <a href="https://www.typescriptlang.org/" target="blank"><img src="public/typescript.svg" width="200" alt="TypeScript Logo"/></a>
  </p>
</div>

# Cotizador de Criptomonedas - React + Vite + TypeScript + API

Aplicación creada con [React](https://react.dev/), [Vite](https://vitejs.dev/), [TypeScript](https://www.typescriptlang.org/), [ZOD](https://zod.dev/) y [Zustand](https://www.npmjs.com/package/zustand) como manejador global de estado, la cual es una aplicación para Cotizar diferentes tipos de Criptomonedas (las 20 con mayor margen de transacciones y las de mayor valor) en diferentes monedas en tiempo real, solo tienes que seleccionar el tipo de moneda que deseas y la criptomoneda a cotizar, y la aplicación realizará una consulta a la API de [CryptoCompare](https://www.cryptocompare.com), mostrando la información solicitada, la APP cuenta con notificaciones personalizadas y uso de Spinners.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. Formularios.
2. Validaciones.
3. useState.
4. useEffect.
5. useMemo.
6. CSS Modules.
7. Hooks personalizados.
8. [Axios](https://www.npmjs.com/package/axios).
9. [Zod](https://www.npmjs.com/package/zod).
10. [Zustand](https://www.npmjs.com/package/zustand).
11. Uso de Spinners ([Spinkit](https://tobiasahlin.com/spinkit/)).
12. Y más.


## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
