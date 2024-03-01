# 02 Bases de Node

## Descripción

Practica de Node.js y Testing con Jest

## Instalación

Para instalar y utilizar esta aplicación, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias utilizando npm:

bash
```npm install```


## Ejecución

Para ejecutar la aplicación, utiliza el siguiente comando:

bash
```npm run dev```

## Testing

Pasos para configurar Jest con TypeScript, en Node

Documentación oficial sobre Jest https://jestjs.io/docs/getting-started

# Instalaciones de desarrollo (super test es útil para probar Express)

npm install -D jest @types/jest ts-jest supertest

# Crear archivo de configuración de Jest

```npx jest --init```

# En el archivo jest.config.js configurar

```preset: 'ts-jest',```

testEnvironment: "jest-environment-node",

// Opcional - The paths to modules that run some code to configure or set up the testing environment before each test

// setupFiles: ['dotenv/config'],

# Crear scripts en el package.json

"test": "jest",
"test:watch": "jest --watch",
"test:coverage": "jest --coverage",,
