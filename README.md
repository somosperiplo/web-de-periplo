# Web Periplo - Instrucciones de publicación

Esta es tu web completa de Periplo, diseñada con estilo minimalista blanco y negro.

## 📁 Contenido

- `index.html` - Página principal
- `manifiesto.html` - Página del manifiesto completo
- `eventos.html` - Página de eventos
- `area-economia.html` - Área: Economía y vivienda
- `area-estado.html` - Área: Estado y administración
- `area-vida.html` - Área: Vida y dignidad
- `area-cultura.html` - Área: Cultura
- `style.css` - Estilos (minimalista blanco y negro)
- `script.js` - JavaScript para menú móvil y formulario
- `images/` - Carpeta con imágenes

## 🚀 Cómo publicar en GitHub Pages (100% GRATIS)

### Paso 1: Crear cuenta en GitHub

1. Ve a [github.com](https://github.com)
2. Haz clic en "Sign up"
3. Crea tu cuenta (es gratis)

### Paso 2: Crear un nuevo repositorio

1. Una vez dentro, haz clic en el botón verde "New" (o "+")
2. Nombre del repositorio: `periplo-web` (o el que prefieras)
3. Marca como **Public**
4. NO marques "Add a README file"
5. Haz clic en "Create repository"

### Paso 3: Subir los archivos

**Opción A - Subida directa (más fácil):**

1. En la página de tu nuevo repositorio, verás "uploading an existing file"
2. Haz clic ahí
3. Arrastra TODOS los archivos de esta carpeta (HTML, CSS, JS, carpeta images)
4. Escribe un mensaje como "Primera versión de la web"
5. Haz clic en "Commit changes"

**Opción B - Usando GitHub Desktop (recomendado si vas a hacer cambios):**

1. Descarga [GitHub Desktop](https://desktop.github.com/)
2. Instálalo e inicia sesión
3. File → Add local repository
4. Selecciona esta carpeta
5. Haz commit y push

### Paso 4: Activar GitHub Pages

1. En tu repositorio, ve a "Settings" (arriba)
2. En el menú izquierdo, haz clic en "Pages"
3. En "Source", selecciona "main" branch
4. Haz clic en "Save"
5. ¡Listo! Tu web estará en: `https://tu-usuario.github.io/periplo-web`

**⏱️ Tiempo:** La primera vez puede tardar 2-5 minutos en aparecer.

## 🎨 Personalización

### Cambiar colores

Abre `style.css` y modifica estas variables al inicio:

```css
:root {
    --negro: #000000;
    --blanco: #FFFFFF;
    --gris-claro: #F5F5F5;
    --gris-medio: #666666;
    --gris-oscuro: #1A1A1A;
}
```

### Cambiar textos

- Página principal: Edita `index.html`
- Manifiesto: Edita `manifiesto.html`
- Eventos: Edita `eventos.html`
- Áreas: Edita `area-economia.html`, `area-estado.html`, `area-vida.html`, `area-cultura.html`

### Añadir más eventos

Abre `eventos.html` y copia/pega el bloque `<div class="evento-card">` para añadir más eventos.

## 📧 Configurar el formulario de contacto

El formulario actualmente solo muestra un mensaje de confirmación. Para que envíe emails reales:

### Opción 1: Formspree (gratis, más fácil)

1. Ve a [formspree.io](https://formspree.io)
2. Crea una cuenta gratuita
3. Crea un nuevo formulario
4. Te darán un código que debes pegar en el `<form>` de `index.html`

### Opción 2: EmailJS (gratis)

1. Ve a [emailjs.com](https://www.emailjs.com/)
2. Crea cuenta y configura tu servicio de email
3. Sigue sus instrucciones para integrar con el formulario

## 🔧 Soporte técnico

Si necesitas ayuda:

1. **Problemas con GitHub:** [docs.github.com/pages](https://docs.github.com/pages)
2. **Tutoriales:** Busca en YouTube "GitHub Pages tutorial"
3. **Comunidad:** [stackoverflow.com](https://stackoverflow.com)

## ✅ Checklist de publicación

- [ ] Crear cuenta en GitHub
- [ ] Crear nuevo repositorio
- [ ] Subir todos los archivos
- [ ] Activar GitHub Pages en Settings
- [ ] Esperar 2-5 minutos
- [ ] Visitar tu URL: `https://tu-usuario.github.io/periplo-web`
- [ ] Configurar formulario de contacto (opcional)
- [ ] ¡Compartir con el mundo!

## 📱 Responsive

La web está completamente adaptada para móviles. El menú se convierte en hamburguesa automáticamente en pantallas pequeñas.

## 🎯 Dominio propio (opcional)

Si quieres usar un dominio propio (ej: `periplo.org`):

1. Compra un dominio en Namecheap, GoDaddy, etc. (~10€/año)
2. En Settings → Pages → Custom domain
3. Ingresa tu dominio
4. Configura los DNS según las instrucciones

## 🔄 Actualizar la web

Para hacer cambios:

1. Modifica los archivos localmente
2. Sube los cambios a GitHub (drag & drop o GitHub Desktop)
3. Los cambios aparecerán en 1-2 minutos

---

**¡Tu web está lista! 🎉**

Cualquier duda, revisa la documentación de GitHub Pages o busca tutoriales en YouTube.
