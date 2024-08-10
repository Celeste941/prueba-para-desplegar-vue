# Vue Componentes - DatosRut
Este proyecto es una aplicación de Vue que muestra una cédula de identidad ficticia. El proyecto contiene dos componentes principales: App.vue y DatosRut.vue.

Estructura del Proyecto:
```
├── src
│   ├── assets
│   │   ├── chile_bandera.png
│   │   └── foto_elon.jpg
│   ├── components
│   │   └── DatosRut.vue
│   ├── App.vue
│   └── main.js
├── package.json
└── README.md
```

## Componentes
`App.vue`  
Es el componente principal de la aplicación. Este componente importa y utiliza el componente DatosRut para mostrar la cédula de identidad.

`DatosRut.vue`  
Este componente es responsable de mostrar los datos de una cédula de identidad ficticia. Incluye información como el nombre, apellido, nacionalidad, sexo, fecha de nacimiento, número de documento, fecha de emisión, fecha de vencimiento y la firma del titular.

## Estilos
Los estilos están definidos dentro del archivo DatosRut.

## Configuración del Proyecto
-Instalación de Dependencias  
Para instalar todas las dependencias necesarias para el proyecto, ejecuta el siguiente comando:
`npm install`

-Compilación: `npm run serve`

Este comando iniciará un servidor de desarrollo y podrás ver tu aplicación en el navegador, normalmente en `http://localhost:8080`.

### Personalizar Configuración
Para más información sobre cómo personalizar la configuración del proyecto, consulta la Referencia de Configuración.
See [Configuration Reference](https://cli.vuejs.org/config/).

