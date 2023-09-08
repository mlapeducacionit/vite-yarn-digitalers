# Pasos para crear un proyecto VITE de JS con YARN

1. Crear el proyecto vite

```sh
yarn create vite .
```

2. Depedencias

```sh
yarn
```
3. Arranca el servidor de desarrollo

```sh
yarn dev
```

## Agrego Bootstrap al proyecto

```sh
yarn add bootstrap @popperjs/core
```
### Incomporando los script y estilos de bootstrap

```main.js
import * as bootstrap from 'bootstrap'
```

```style.css
@import 'bootstrap';
```