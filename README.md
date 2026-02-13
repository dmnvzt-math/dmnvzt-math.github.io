# Portfolio Web - Damián Alejandro Vizuete

Portfolio profesional minimalista y tecnológico creado para mostrar experiencia en Data Science, Business Intelligence y Analytics.

## 🚀 Características

- ✨ Diseño minimalista y moderno
- 📱 Completamente responsive (móvil, tablet, desktop)
- 🎨 Gradientes tecnológicos con colores azul/cyan
- ⚡ Animaciones suaves y efectos de scroll
- 📊 Secciones para experiencia, habilidades, educación y contacto
- 🌐 Optimizado para GitHub Pages

## 📋 Estructura del Proyecto

```
portfolio/
│
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interactividad
└── README.md           # Este archivo
```

## 🌐 Cómo publicar en GitHub Pages

### Opción 1: Usando GitHub Web (Más fácil)

1. **Crear una cuenta en GitHub** (si no tienes una)
   - Ve a https://github.com
   - Haz clic en "Sign Up" y completa el registro

2. **Crear un nuevo repositorio**
   - Haz clic en el botón "+" arriba a la derecha
   - Selecciona "New repository"
   - Nombre del repositorio: `tu-usuario.github.io` 
     (Por ejemplo: `alejovizuete.github.io`)
   - Marca como "Public"
   - NO inicialices con README
   - Haz clic en "Create repository"

3. **Subir tus archivos**
   - En la página del repositorio nuevo, haz clic en "uploading an existing file"
   - Arrastra los 3 archivos: `index.html`, `styles.css`, `script.js`
   - Escribe un mensaje como "Primer commit - Portfolio inicial"
   - Haz clic en "Commit changes"

4. **Activar GitHub Pages**
   - Ve a "Settings" en tu repositorio
   - En el menú lateral, haz clic en "Pages"
   - En "Source", selecciona "main" branch
   - Haz clic en "Save"
   - ¡Espera unos minutos y tu sitio estará en línea!

5. **Ver tu sitio**
   - Tu portfolio estará disponible en: `https://tu-usuario.github.io`
   - Ejemplo: `https://alejovizuete.github.io`

### Opción 2: Usando Git en la Terminal (Para usuarios avanzados)

```bash
# 1. Instalar Git (si no lo tienes)
# Windows: Descarga de https://git-scm.com
# Mac: brew install git
# Linux: sudo apt-get install git

# 2. Configurar Git (primera vez)
git config --global user.name "Tu Nombre"
git config --global user.email "tu-email@example.com"

# 3. Crear directorio y copiar archivos
mkdir portfolio
cd portfolio
# Copia los archivos index.html, styles.css, script.js a esta carpeta

# 4. Inicializar repositorio
git init
git add .
git commit -m "Primer commit - Portfolio inicial"

# 5. Conectar con GitHub
git remote add origin https://github.com/tu-usuario/tu-usuario.github.io.git
git branch -M main
git push -u origin main

# 6. El sitio estará disponible en https://tu-usuario.github.io
```

## 🎨 Personalización

### Cambiar colores
Edita las variables CSS en `styles.css`:

```css
:root {
    --primary-color: #0066ff;      /* Color principal */
    --secondary-color: #00d4ff;    /* Color secundario */
    /* ... otros colores */
}
```

### Agregar foto de perfil
1. Agrega tu foto al repositorio (nombre sugerido: `profile.jpg`)
2. En `index.html`, en la sección hero, agrega:
```html
<div class="hero-image">
    <img src="profile.jpg" alt="Damián Alejandro Vizuete">
</div>
```

### Agregar redes sociales
Agrega en la sección de contacto:
```html
<div class="social-links">
    <a href="https://linkedin.com/in/tu-perfil">LinkedIn</a>
    <a href="https://github.com/tu-usuario">GitHub</a>
</div>
```

## 📱 Secciones del Portfolio

1. **Hero** - Presentación principal con estadísticas
2. **Perfil** - Descripción profesional y highlights
3. **Experiencia** - Timeline con historial profesional
4. **Habilidades** - Skills técnicos con barras de progreso
5. **Educación** - Títulos académicos y certificaciones
6. **Contacto** - Información de contacto y referencias

## 🔧 Tecnologías Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (Vanilla JS)
- Google Fonts (Inter)

## 📝 Actualizaciones Futuras Recomendadas

- [ ] Agregar sección de proyectos con ejemplos de trabajo
- [ ] Incluir blog para artículos técnicos
- [ ] Agregar portfolio de visualizaciones de datos
- [ ] Integrar formulario de contacto funcional
- [ ] Agregar modo oscuro/claro
- [ ] Incluir casos de estudio detallados

## 🆘 Solución de Problemas

### El sitio no se ve bien en móvil
- Asegúrate de que el tag viewport esté en `index.html`
- Verifica que `styles.css` tenga las media queries

### Los estilos no se cargan
- Verifica que `styles.css` y `script.js` estén en el mismo directorio que `index.html`
- Limpia el caché del navegador (Ctrl+Shift+R)

### El sitio no aparece en GitHub Pages
- Espera 5-10 minutos después de activar Pages
- Verifica que el archivo se llame exactamente `index.html`
- Confirma que el repositorio sea público

## 📞 Contacto

**Damián Alejandro Vizuete Galeas**
- 📧 Email: alejo8vizuete@yahoo.com
- 📱 Teléfono: +593 99 276 9412
- 📍 Ubicación: San Pedro de Taboada, Ecuador

---

💡 **Tip**: Actualiza regularmente tu portfolio con nuevos proyectos y logros para mantenerlo fresco y relevante.

🚀 **Desarrollado con pasión por la ciencia de datos y el diseño web moderno**