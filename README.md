# Instalación de NPM
Instalar dependencias de npm
> npm install --save-dev @types/node nodemon ts-node typescript

Compilar archivos de TS a JS
> npx tsc --init --rootDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowjs true --noImplicitAny true

# Ejecuciones
Ejecutar todo
> npm run start

Ejecutar un script en concreto
> npm run _script_

# Tipos de variables
- any: Cualquier tipo de dato.
- string: Cadena de texto.
- number: Valores numéricos.
- boolean: Valores verdadero o false.
- void: Para funciones que no devuelve ningún valor.
- null: Representa la ausencia de un valor.
- undefined: Representa la ausencia de un valor.

> var error: boolean = false;

** Si no definimos un tipo a la variable, será de tipo any.

## Otros tipos de variable
- array: Listado de datos.
- tuple: Listado de datos con un número fijo de elementos.
- object: Listado de variables.
- enum: Conjuntos de constantes.
- interface: Define una estructura para objetos.
- type: Crea un alias para un tipo de dato.
