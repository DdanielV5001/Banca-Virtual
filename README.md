 🏦 Banca Virtual – Frontend

Proyecto académico desarrollado con **Angular (standalone)** que implementa un **login funcional** con una interfaz profesional tipo banca virtual.

El objetivo del proyecto es aplicar buenas prácticas de desarrollo frontend moderno, control de versiones con GitHub y correcta documentación para que el proyecto pueda ejecutarse en cualquier computador.

---

📌 Tecnologías utilizadas

- Angular (Standalone Components)
- TypeScript
- HTML5
- CSS3
- Node.js
- Angular CLI
- Git y GitHub

---

 🧩 Requisitos previos

Para ejecutar este proyecto en cualquier computador, se debe contar con los siguientes requisitos:

 1️⃣ Node.js (OBLIGATORIO)

- Versión recomendada: **Node.js 18 o superior**
- Descargar desde:  
  👉 https://nodejs.org

Verificar instalación:
```bash
node -v
npm -v

2️⃣ Angular CLI (OBLIGATORIO)

Instalar Angular CLI de forma global:

npm install -g @angular/cli


Verificar instalación:

ng version

3️⃣ Git (RECOMENDADO)

Para clonar el repositorio:

Descargar desde:
👉 https://git-scm.com

4️⃣ Editor de código (RECOMENDADO)

Visual Studio Code
👉 https://code.visualstudio.com

📥 Clonar el repositorio

Desde una terminal (Git Bash o terminal integrada de VS Code):

git clone https://github.com/DdanielV5001/Banca-Virtual.git


Ingresar a la carpeta del proyecto frontend:

cd Banca-Virtual/banca-virtual-frontend

📦 Instalación de dependencias

Una vez dentro del proyecto, ejecutar:

npm install


Este comando descargará todas las dependencias necesarias para ejecutar la aplicación.

▶️ Ejecutar el proyecto

Para iniciar el servidor de desarrollo de Angular:

ng serve


Si todo está correcto, la terminal mostrará algo similar a:

Local: http://localhost:4200/

🌐 Acceder a la aplicación

Abrir un navegador web y dirigirse a:

http://localhost:4200

🔐 Credenciales de prueba

El login utiliza validación simulada (fake login) con fines académicos:

Usuario: demo

Contraseña: 1234

⚠️ Problemas comunes y soluciones
❌ Error: ng: command not found

Angular CLI no está instalado.

Solución:

npm install -g @angular/cli

❌ Error de permisos en PowerShell (Windows)

Se recomienda usar:

Git Bash

Terminal integrada de Visual Studio Code

❌ Error de dependencias faltantes

Ejecutar nuevamente:

npm install