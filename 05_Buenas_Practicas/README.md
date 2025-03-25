# 🧠 05 - Buenas prácticas con Git y GitHub

En esta unidad vas a conocer recomendaciones clave para trabajar de manera profesional con Git y GitHub. Estas buenas prácticas te ayudarán a mantener tu código limpio, organizado y colaborativo.

---

## ✍️ Escribir mensajes de commit claros

Los mensajes de commit deben explicar **qué hiciste y por qué**. Algunas recomendaciones:

✅ Comenzar con un verbo en infinitivo:
- `Agregar sección de contacto`
- `Actualizar README con nuevas instrucciones`
- `Corregir error en formulario`

✅ Evitar mensajes vagos como `cambios varios` o `update`

---

## 📂 Usar .gitignore

El archivo `.gitignore` le indica a Git qué archivos **no debe seguir ni subir** al repositorio.

Ejemplos comunes:
```
# Archivos temporales
*.log
*.tmp
.DS_Store

# Entornos virtuales
venv/
node_modules/

# Configuraciones locales
.env
.idea/
```

Para generar `.gitignore` específicos según lenguaje: https://www.toptal.com/developers/gitignore

---

## 🏷 Crear etiquetas (tags) y versiones (releases)

Los **tags** sirven para marcar versiones estables del proyecto:
```bash
git tag v1.0.0
git push origin v1.0.0
```

En GitHub, podés ir a la pestaña **Releases** y crear una versión:
- Asignale un nombre (ej: `v1.0.0`)
- Agregá un resumen de los cambios

Ideal para: entregas, deploys, o entregas de proyectos educativos.

---

## 🐞 Usar Issues para organizar tareas

Los **Issues** te permiten documentar:
- Tareas pendientes
- Bugs o errores encontrados
- Ideas para el proyecto

Pueden usarse en proyectos colaborativos o para gestionar tu propio trabajo.

Además podés asignarlos, etiquetarlos y cerrarlos cuando se resuelven.

---

## 🗂 Estructura limpia del repositorio
- Separar archivos en carpetas temáticas (`docs/`, `src/`, `assets/`)
- Mantener actualizada la documentación (`README.md`, `CONTRIBUTING.md`)
- Borrar archivos innecesarios

---

## 🧪 Actividad práctica sugerida
1. Agregá un archivo `.gitignore` a tu proyecto
2. Creá un commit con mensaje claro
3. Usá `git tag` para marcar una versión del proyecto
4. Abrí un Issue en tu repositorio con una mejora pendiente

---

✅ ¡Aplicando estas prácticas vas a elevar la calidad de tus proyectos!
