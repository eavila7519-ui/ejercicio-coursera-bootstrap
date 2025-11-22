# Proyecto Bootstrap 4 - Ejercicio Coursera

Este es un proyecto de ejemplo para el curso "Diseñando páginas web con Bootstrap 4" de Coursera.

## Requisitos Previos

Para ejecutar este proyecto necesitas tener instalado:
- Node.js y NPM
- Git

## Instalación

1. Clona este repositorio o descarga los archivos
2. Abre una terminal en la carpeta del proyecto
3. Ejecuta el siguiente comando para instalar las dependencias:

```bash
npm install
```

Esto instalará:
- Bootstrap 4.6.2
- jQuery 3.6.4
- Popper.js 1.16.1
- lite-server 2.6.1

## Ejecutar el Proyecto

Para iniciar el servidor de desarrollo, ejecuta:

```bash
npm run dev
```

Esto iniciará lite-server y abrirá automáticamente tu navegador en http://localhost:3000

## Estructura del Proyecto

```
.
├── index.html          # Página principal
├── styles.css          # Estilos personalizados
├── package.json        # Configuración de NPM y script dev
├── .gitignore         # Archivos ignorados por Git
└── node_modules/      # Dependencias (ignorado por Git)
```

## Características Implementadas

✅ **Archivo .gitignore** - Evita seguimiento de node_modules
✅ **Script dev** - Inicializa lite-server con `npm run dev`
✅ **Referencias a Bootstrap, jQuery y Popper** - Desde node_modules
✅ **Jumbotron** - Con título del proyecto
✅ **Container con 3 párrafos** - Características del producto
✅ **Lista de productos** - Con sistema de grillas (filas y columnas)
✅ **Sistema responsive** - Adaptable a todos los tamaños de pantalla
✅ **Grillas con Flexbox** - Implementado con d-flex
✅ **Footer** - Con información del comercio y redes sociales
✅ **Componente Address** - Para dirección comercial
✅ **CSS con estilos replicables** - Clase .product-card para todos los productos
✅ **Clases de alineación** - text-left, text-center, text-right en footer

## Tecnologías Utilizadas

- HTML5
- CSS3
- Bootstrap 4.6.2
- jQuery 3.6.4
- Popper.js 1.16.1
- NPM
- lite-server

## Comandos Git

Inicializar repositorio:
```bash
git init
```

Agregar archivos:
```bash
git add .
```

Hacer commit:
```bash
git commit -m "Initial commit: Proyecto Bootstrap 4 completo"
```

Conectar con repositorio remoto (Bitbucket):
```bash
git remote add origin <URL_DE_TU_REPOSITORIO>
git push -u origin master
```

## Autor

Proyecto desarrollado para el curso de Coursera - Diseñando páginas web con Bootstrap 4

## Licencia

ISC
