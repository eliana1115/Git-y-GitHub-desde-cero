# 🤝 04 - Trabajo colaborativo con Git y GitHub

En esta unidad vas a aprender a trabajar en equipo utilizando Git y GitHub. Veremos cómo crear ramas (branches), hacer merges, resolver conflictos y colaborar de forma organizada.

---

## 🌿 ¿Qué es una rama (branch)?

Una rama es una versión paralela de tu proyecto. Se usa para trabajar en nuevas funcionalidades sin afectar la versión principal (`main`). Luego, los cambios se pueden unir (merge).

---

## 🌱 Crear y cambiar de rama

### Crear una nueva rama y moverse a ella:
```bash
git checkout -b nueva-funcionalidad
```

### Volver a la rama principal:
```bash
git checkout main
```

### Ver todas las ramas:
```bash
git branch
```

---

## 🔀 Unir ramas (merge)

Cuando terminás de trabajar en tu rama, podés integrarla con la rama principal.

### Paso a paso:
```bash
git checkout main           # Volvés a la rama principal
git merge nueva-funcionalidad  # Unís los cambios
```

Si todo sale bien, se unen automáticamente. Si hay líneas modificadas en ambas ramas, puede aparecer un **conflicto**.

---

## ⚠️ Cómo resolver conflictos

Cuando Git no puede unir dos archivos automáticamente:

1. Git marca el archivo con secciones tipo:
```
<<<<<<< HEAD
versión en main
=======
versión en rama secundaria
>>>>>>> nueva-funcionalidad
```

2. Editá el archivo para dejar la versión correcta
3. Guardá y luego hacé:
```bash
git add archivo.txt
git commit -m "Resuelvo conflicto"
```

---

## 🔗 Subir ramas a GitHub
```bash
git push origin nueva-funcionalidad
```

GitHub te permitirá crear un **Pull Request**, revisar los cambios y discutirlos con tu equipo antes de unirlos.

---

## 🧪 Actividad práctica sugerida
1. Creá una rama llamada `mejora-estilo`
2. Cambiá el `README.md` agregando una línea nueva
3. Comiteá y mergeá con `main`
4. Simulá un conflicto: modificá la misma línea en dos ramas y resolvélo

---

## 🛠 Recomendaciones para trabajar en equipo
- Cada funcionalidad importante debe ir en su propia rama
- Nombrar las ramas de forma clara (ej: `fix-login`, `feature-contacto`)
- Usar mensajes de commit descriptivos
- Revisar los cambios antes de hacer merge

---

✅ ¡Ahora ya podés trabajar de forma profesional en equipo con Git y GitHub!
