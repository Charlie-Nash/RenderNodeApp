# 🌐 Landing Page Profesional con Node.js y Render

Este proyecto es una **landing page moderna y responsiva**, construida con **Node.js** y **Express.js**, diseñada para ser publicada fácilmente en [Render.com](https://render.com).

## 🚀 Demo en vivo

➡️ *(Agrega aquí la URL que Render te proporciona después del despliegue)*

## 📦 Tecnologías utilizadas

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- HTML5 + CSS3 (Diseño responsivo y moderno)
- Render.com para el despliegue en la nube

## 📁 Estructura del proyecto

```
mi-landing-render/
│
├── index.js               # Servidor Express
├── package.json           # Dependencias y scripts
└── public/                # Archivos públicos estáticos
    ├── index.html         # Landing page
    ├── css/
    │   └── style.css      # Estilos personalizados
    └── img/
        └── hero.jpg       # Imagen decorativa
```

## ⚙️ Instalación y ejecución local

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/mi-landing-render.git
   cd mi-landing-render
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Ejecuta el servidor:
   ```bash
   npm start
   ```

4. Abre tu navegador en:
   ```
   http://localhost:3000
   ```

## ☁️ Despliegue en Render.com

1. Crea una cuenta en [https://render.com](https://render.com)
2. Crea un nuevo **Web Service** desde tu repositorio de GitHub
3. Configura:
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Environment**: Node
4. ¡Render se encargará del resto!

## ✨ Captura de pantalla

![Vista previa de la landing page](public/img/hero.jpg)

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Eres libre de usarlo, modificarlo y adaptarlo según tus necesidades.