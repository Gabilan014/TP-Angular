# 🏎️ Proyecto Final Angular — TP Angular

Este repositorio contiene un proyecto desarrollado con **Angular**, utilizando componentes, servicios, estilos personalizados y gestión de datos.

## 🚀 Requisitos previos

Antes de ejecutar el proyecto asegurate de tener instalado:

| Herramienta | Versión recomendada | Instalación |
|-------------|----------------------|--------------|
| Node.js     | 18.x o superior      | https://nodejs.org/ |
| Angular CLI | 17.x o superior      | `npm install -g @angular/cli` |
| Git         | Última versión       | https://git-scm.com/downloads |

---

## 📥 Cómo clonar y levantar el proyecto

### ✅ 1. Clonar el repositorio

Abrí la terminal (PowerShell, CMD o VS Code Terminal) y ejecutá:


git clone https://github.com/Gabilan014/TP-Angular.git

Entrar a la carpeta del proyecto:

cd TP-Angular

✅ 2. Instalar dependencias

Ejecutá:

npm install


Esto descargará todas las dependencias definidas en package.json.

✅ 3. Ejecutar el proyecto

Para iniciar la app en modo desarrollo:

ng serve -o


-o abre automáticamente el navegador.

La aplicación se ejecutará aquí:

➡️ http://localhost:4200/

📂 Estructura del proyecto
📦 TP-Angular
 ┣ 📂 src
 ┃ ┣ 📂 app
 ┃ ┣ 📂 assets
 ┃ ┃ ┗ 📂 img  ← imágenes usadas en el proyecto
 ┃ ┗ index.html
 ┗ angular.json


Las imágenes se deben colocar en:

src/assets/img/


Y se referencian así:

img src="assets/img/imagen.png"

🎨 Estilos y diseño

El proyecto utiliza:

Estilos personalizados CSS

Animaciones suaves

Temática visual minimalista / glassmorphism / Red Bull Racing (opcional)

💡 Sugerencias

Usá git status para verificar los cambios antes de hacer commit.

Para agregar todos los cambios:

git add .
git commit -m "Actualización del proyecto Angular"
git push


