# 📘 Guía de Inicio: GitHub + Jupyter para Aprendizaje "Learn by Doing"

Esta guía está pensada como un documento de consulta rápida para organizar tu estudio práctico usando GitHub, Jupyter y la terminal. Aquí aprenderás qué formatos se usan, cómo moverte entre carpetas, y cómo clonar y subir proyectos.

---

## 📁 Extensiones de archivo comunes

| Extensión | Significado | Usos típicos |
|-----------|-------------|--------------|
| `.md`     | Markdown    | Documentación, apuntes, README de repositorios |
| `.ipynb`  | Jupyter Notebook | Código Python interactivo + texto explicativo |
| `.py`     | Archivo de Python | Código puro (scripts o funciones reutilizables) |

---

## 🧭 Terminal vs Jupyter Notebook

| Acción | Terminal | Jupyter Notebook |
|--------|----------|------------------|
| Navegar por carpetas | ✅ | ❌ |
| Clonar repositorio Git | ✅ | ❌ |
| Ejecutar código paso a paso | ❌ | ✅ |
| Instalar librerías (pip) | ✅ | ❌ |
| Escribir apuntes + probar código | ❌ | ✅ |
| Subir cambios a GitHub | ✅ | ❌ |

---

## 💻 Comandos básicos de terminal

### 🔹 Navegación

```bash
pwd                 # Mostrar en qué carpeta estás
ls                  # Ver contenido de la carpeta actual
cd nombre_carpeta   # Entrar a una carpeta
cd ..               # Subir una carpeta
```

### 🔹 Gestión de entornos y librerías

```bash
pip install nombre_paquete      # Instalar librería
conda install nombre_paquete    # (si usas Anaconda)
sudo pip install nombre_paquete # Si necesitas permisos especiales (Mac/Linux)
```

---

## 🔧 Git y GitHub: flujo básico

### 1. Clonar un repositorio

```bash
git clone https://github.com/usuario/repositorio.git
```

### 2. Ver estado del proyecto

```bash
git status
```

### 3. Añadir cambios (archivos nuevos o modificados)

```bash
git add .
```

### 4. Crear un commit (guardado con mensaje)

```bash
git commit -m "Añadir notas de álgebra"
```

### 5. Subir los cambios a GitHub

```bash
git push origin main
```

### 6. Descargar cambios desde GitHub (si trabajas desde varios equipos)

```bash
git pull origin main
```

---

## 📌 Recomendaciones

- Trabaja **en local** con Jupyter para probar, escribir, y experimentar.
- Usa **Git y GitHub** para guardar y compartir tu progreso.
- Mantén un archivo README.md en cada carpeta con un resumen de lo que contiene.
- Si ves que un archivo tiene extensión `.ipynb`, ábrelo con Jupyter.
- Si tiene `.py`, puedes abrirlo con VSCode o en el mismo Jupyter (como script).
- Si tiene `.md`, puedes leerlo directamente desde GitHub o cualquier editor.

---

Este archivo crecerá contigo. Cada vez que aprendas algo importante sobre Git, la terminal o Jupyter, anótalo aquí.
