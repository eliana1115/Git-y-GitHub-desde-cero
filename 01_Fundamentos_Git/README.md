# 🧱 01 - Fundamentos de Git

Bienvenido a la primera unidad del curso. En esta sección aprenderás los conceptos esenciales de Git, cómo instalarlo y cómo comenzar a trabajar con tus primeros comandos en tu entorno local.

---

## 🧠 ¿Qué es Git?

Git es un **sistema de control de versiones distribuido**, utilizado para registrar los cambios en archivos a lo largo del tiempo. Es ampliamente usado en desarrollo de software, pero también es útil para cualquier proyecto que requiera control de versiones.

### Ventajas de usar Git:
- Guarda historial de cambios
- Permite trabajar en equipo
- Restaura versiones anteriores fácilmente
- Trabaja sin conexión (repositorio local)

---

## ⚙️ Instalación de Git

### Windows
1. Descargar desde: https://git-scm.com
2. Ejecutar el instalador y dejar las opciones por defecto

### macOS
```bash
brew install git
```

### Linux (Debian/Ubuntu)
```bash
sudo apt update
sudo apt install git
```

---

## 🔧 Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tucorreo@example.com"
git config --global init.defaultBranch main
```

---

## 🧪 Tu primer repositorio Git
```bash
mkdir mi_proyecto
cd mi_proyecto
git init
```
Esto crea un repositorio vacío en la carpeta actual.

---

## 🔄 Flujo básico de trabajo con Git

### 1. Verificar el estado del repositorio
```bash
git status
```

### 2. Agregar archivos al área de preparación (staging)
```bash
git add archivo.txt
```
O todos los archivos:
```bash
git add .
```

### 3. Confirmar los cambios (commit)
```bash
git commit -m "Mensaje descriptivo del cambio"
```

### 4. Ver historial de commits
```bash
git log
```

---

## 🧹 Limpiar el proyecto

### Eliminar archivo del control de versiones (pero no del disco)
```bash
git rm --cached archivo.txt
```

### Ignorar archivos (crear `.gitignore`)
```
node_modules/
*.log
.env
```

---

## 📝 Actividad práctica sugerida
1. Instalá Git y configurá tu usuario
2. Creá una carpeta con `git init`
3. Agregá un archivo de texto y hacé varios commits con distintos mensajes
4. Visualizá los cambios con `git log`

---

✅ ¡Ahora estás listo para pasar al módulo 2 y comenzar a trabajar con GitHub!
