# SWAPI Challenge

## Descripción

SWAPI Challenge es una SPA desarrollada como prueba para un proceso de selección. Consiste en explorar la API de Star Wars [SWAPI](https://swapi.py4e.com/)

## Funcionalidades

- **Listados de entidades**: Vemos listados de personajes, planetas, películas, especies, naves espaciales y vehículos.
- **Vistas de detalle**: Información detallada de cada entidad y enlaces a otros similares
- **Paginación**: Para mostrar la información por páginas asequibles.
- **Buscador**: Filtra las entidades en los listados.
- **Resumen**: Muestra el total de entradas listadas según los filtros aplicados.
- **Manejo de errores**: Tolerancia a fallos del servidor y tiempos de respuesta prolongados.

## Requisitos para ejecutar

- Node.js y npm.
- Google Chrome (última versión estable).

## Tecnologías Utilizadas

- JavaScript Vanilla (sin frameworks).
- Lodash (para utilidades).
- Prettier (para formateo de código).
- [Serve](https://www.npmjs.com/package/serve) (como servidor).

## Instalación

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/tu_usuario/swapi-challenge.git
2. **Instalar dependencias:**
    ```bash
    npm i
2. **Iniciar la aplicación:**
    ```bash
    npm start
3. **Navegar a la url:**
    bash
    http://localhost:5000

## Test

1. **Clonar el repositorio:**

```bash
   npm test
   ```
# Estructura del Proyecto

```plaintext
swapi-challenge/
│
├── src/
│   ├── index.html         # Project html
│   ├── main.js            # Main JavaScript logic
│   ├── main.test.js       # Tests
│   ├── styles.css         # Styles
│
├── .gitignore             # Git ignore file
├── README.md              # Project guide
├── package.json           # NPM config
├── jest.config.js         # Jest config
├── .prettierrc            # Prettier config
└── .prettierignore        # Prettier ignore file
