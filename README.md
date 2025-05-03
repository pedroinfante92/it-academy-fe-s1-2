# it-academy-fe-s1-2: Bootstrap & SASS

## Descripción del Proyecto

Este proyecto es una práctica diseñada para aprender y aplicar **SASS** y **Bootstrap 5** en el desarrollo de sitios web modernos y responsivos. Incluye ejemplos de componentes de Bootstrap personalizados con SASS, validación de formularios y diseño adaptativo.

El objetivo principal es comprender cómo funcionan los componentes de Bootstrap y cómo extenderlos o personalizarlos utilizando SASS.

## Tecnologías Utilizadas

- **Bootstrap 5**: Framework CSS para diseño responsivo y componentes reutilizables.
- **SASS**: Preprocesador CSS para escribir estilos más organizados y reutilizables.
- **HTML5**: Estructura del sitio web.
- **JavaScript (opcional)**: Para interactividad adicional.

---

## Estructura de Archivos

```plaintext
it-academy-fe-s1-2/
├── assets/
│   ├── css/                # Archivos CSS generados
│   ├── scss/               # Archivos SASS fuente
│   ├── img/                # Imágenes del proyecto
│   └── screenshots/        # Capturas de pantalla del proyecto
├── index.html              # Página principal
├── README.md               # Documentación del proyecto
└── styles_bootstrap.scss   # Estilos principales personalizados
```

## Instrucciones de Instalación

### Requisitos Previos
- Tener **Node.js** y **npm** instalados en tu sistema.
- Un navegador moderno con conexión a internet.

### Instalación

1. Clona este repositorio:
   ```bash
   git clone <URL-del-repositorio>
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd nombre-del-proyecto
   ```

3. Instala las dependencias necesarias (si usas un compilador de SASS como Dart Sass):
   ```bash
   npm install
   ```

---

## Compilación de SASS

Si deseas personalizar los estilos o trabajar con los archivos SASS, sigue estos pasos:

1. Asegúrate de tener SASS instalado globalmente:
   ```bash
   npm install -g sass
   ```

2. Compila los archivos SASS a CSS:
   ```bash
   sass src/scss:dist/css
   ```

3. Activa el modo de observación para compilar automáticamente cuando haya cambios:
   ```bash
   sass --watch src/scss:dist/css
   ```

---

## Uso del Proyecto

- Abre el archivo `index.html` en tu navegador:
  ```bash
  open index.html
  ```

- Explora las diferentes secciones y componentes del sitio.

---

## Recursos Adicionales

- [Documentación oficial de Bootstrap](https://getbootstrap.com/)
- [Guía de SASS](https://sass-lang.com/guide)