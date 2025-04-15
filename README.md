# 🧪 aestheticlab – Shopify Theme for Clothing Brand

Bienvenido a **aestheticlab**, un tema personalizado de Shopify desarrollado con Liquid, HTML, CSS y JavaScript. Esta plantilla está diseñada específicamente para una marca de ropa moderna y minimalista, ofreciendo una base sólida para crear una experiencia de compra visualmente atractiva y funcional.

## 🛠️ Tecnologías usadas

- [Shopify Liquid](https://shopify.dev/docs/api/liquid) – Motor de plantillas
- HTML5 & CSS3 – Estructura y estilo
- JavaScript – Comportamiento dinámico
- Shopify CLI – Desarrollo local y despliegue

## 📂 Estructura del proyecto

```
my-shopify-theme/
├── assets/
│   ├── styles.css
│   ├── scripts.js
│   └── al_logo.png
├── config/
│   └── settings_schema.json
├── layout/
│   └── theme.liquid
├── sections/
├── snippets/
├── templates/
│   ├── index.liquid
│   ├── product.liquid
│   └── collection.liquid
```

## 🚀 Cómo usar esta plantilla

### 1. Clonar el repositorio

```bash
git clone https://github.com/amsteradri/aestheticlab.git
cd aestheticlab
```

### 2. Instalar dependencias (si usas herramientas como Shopify CLI)

Asegúrate de tener Node.js y Shopify CLI instalados:

```bash
npm install -g @shopify/cli @shopify/theme
```

### 3. Servir el tema en desarrollo

```bash
shopify login --store your-store-name.myshopify.com
shopify theme serve
```

Esto abrirá una vista previa local sincronizada con tu tienda de desarrollo.

## 🎨 Personalización

Puedes editar los archivos .liquid y los estilos en styles.css para adaptar el diseño a tu marca. El logo se encuentra en assets/al_logo.png, y puede ser reemplazado por uno propio manteniendo el mismo nombre o ajustando la ruta en theme.liquid.

## 🧪 Vista previa de la plantilla

(Asegúrate de subir una captura de pantalla del diseño principal y llamarla preview.png)

## 🧍 Sobre el autor

Desarrollado por @amsteradri, con ❤️ por el diseño limpio y estético aplicado al ecommerce de moda.
