# 🎁 06 - Extras útiles en GitHub

En esta última unidad vas a descubrir herramientas y recursos adicionales que podés aplicar para enriquecer tus proyectos, destacarte en tu perfil y mejorar la presentación de tus repositorios en GitHub.

---

## 🖼 Agregar imágenes y banners en el `README.md`

Podés mostrar imágenes directamente en tu README con Markdown:
```markdown
![Texto alternativo](https://ruta.com/imagen.jpg)
```

Si subís una imagen a tu repositorio:
```markdown
![Banner](https://github.com/usuario/repositorio/blob/main/Images/banner.png?raw=true)
```

También podés hacerla **clickeable**:
```markdown
[![Texto](https://ruta.com/banner.png)](https://github.com/usuario/repositorio)
```

Ideal para usar banners, íconos o infografías.

---

## 🌐 GitHub Pages (para publicar sitios)

GitHub Pages permite **publicar sitios web directamente desde tu repositorio**. Ideal para CVs, portafolios, documentación o proyectos con HTML.

### Cómo activarlo:
1. Ir a **Settings > Pages**
2. Seleccionar rama `main` y carpeta `/docs` (o `/root` si está en la raíz)
3. Guardar y copiar el enlace generado

💡 También podés subir tu sitio hecho en HTML o con generadores estáticos como Jekyll.

---

## 🧩 Crear una carpeta `/docs` con una web básica
```html
<!-- /docs/index.html -->
<html>
<head><title>Mi sitio</title></head>
<body>
  <h1>Bienvenido a mi sitio en GitHub Pages</h1>
</body>
</html>
```

Subila y GitHub la mostrará como página web.

---

## 🛠 Otros recursos útiles para GitHub

### 📄 Licencias
Podés incluir un archivo `LICENSE` para indicar cómo se puede usar tu código. Recomendado: MIT, Apache 2.0 o Creative Commons.

### 👥 Colaboradores
Agregá un archivo `CONTRIBUTING.md` para explicar cómo otros pueden colaborar en tu proyecto.

### 📊 Shields y badges
Visualizá el estado del proyecto con insignias:
```markdown
![GitHub repo size](https://img.shields.io/github/repo-size/usuario/repositorio)
```
Buscá más en: https://shields.io/

---

## 🧪 Actividad práctica sugerida
1. Subí un banner a tu repositorio y agregalo al `README.md`
2. Activá GitHub Pages y creá una página básica en `/docs`
3. Agregá una licencia y una insignia de tamaño del repo

---

✅ ¡Felicitaciones! Completaste todo el curso. Ya podés crear, gestionar y compartir proyectos profesionales en GitHub.
