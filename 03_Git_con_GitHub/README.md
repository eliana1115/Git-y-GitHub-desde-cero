# 🔄 03 - Conectando Git con GitHub

En esta unidad vas a aprender cómo vincular tu proyecto local de Git con un repositorio remoto en GitHub. Esto te permitirá sincronizar los cambios, trabajar desde diferentes dispositivos y colaborar con otros.

---

## 🌐 ¿Qué es un repositorio remoto?

Un repositorio remoto es una copia de tu proyecto que está almacenada en la nube (por ejemplo, en GitHub). Podés subirle cambios desde tu máquina, descargar versiones actualizadas y compartirlo fácilmente con otras personas.

---

## 🔁 Flujo general para conectar Git y GitHub

### Paso 1: Crear un repositorio en GitHub (vacío)
- Nombre: `proyecto-demo`
- No marques “Initialize with README” (así lo conectás desde cero)

### Paso 2: Crear o usar un repositorio local
```bash
mkdir proyecto-demo
cd proyecto-demo
git init
echo "# Proyecto Demo" > README.md
git add .
git commit -m "Primer commit"
```

### Paso 3: Vincular con GitHub
```bash
git remote add origin https://github.com/tuusuario/proyecto-demo.git
git branch -M main
git push -u origin main
```

✅ ¡Listo! Tu repositorio local está ahora conectado al remoto.

---

## 🧰 Comandos clave del flujo diario

### Subir cambios:
```bash
git add .
git commit -m "Agrego nuevas secciones"
git push
```

### Bajar cambios del repositorio:
```bash
git pull origin main
```

> ⚠️ Siempre hacé `git pull` antes de comenzar a trabajar para evitar conflictos.

---

## 🔍 Verificar conexión y configuración
```bash
git remote -v
```
Esto te muestra el link con el que está vinculado tu repositorio local.

---

## 🧪 Actividad práctica sugerida
1. Creá un repositorio local con al menos un archivo (`README.md`)
2. Subí el proyecto a GitHub utilizando `git remote add`
3. Hacé un nuevo cambio local, comitealo y empujalo (`git push`)
4. Verificá que aparezca en la web

---

## 💬 Tips adicionales
- Usá commits frecuentes y descriptivos
- No subas archivos innecesarios (usá `.gitignore`)
- Podés subir múltiples archivos o carpetas con `git add .`

---

✅ ¡Ahora ya sabés conectar tu entorno local con GitHub y sincronizar tu trabajo! En la siguiente unidad aprenderás
