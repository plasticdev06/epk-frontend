# Eco Paper Kraft - Frontend (React)

¡Bienvenido al repositorio del Frontend de **Eco Paper Kraft**!  
Este proyecto es la interfaz visual de nuestro sitio web. No te preocupes si nunca has programado o no tienes ninguna herramienta instalada; aquí tienes la guía paso a paso para configurar tu computadora desde cero.

---

## Paso 1: Instalación de Herramientas (Solo se hace una vez)

Antes de empezar, necesitas instalar estas 3 herramientas básicas en tu equipo:

1. **Visual Studio Code (Editor de Código):**
   * Descárgalo e instálalo desde: [code.visualstudio.com](https://code.visualstudio.com/)
2. **Git (Control de Versiones):**
   * Descárgalo e instálalo desde: [git-scm.com](https://git-scm.com/)  
   *(En la instalación puedes darle a "Next" a todo por defecto).*
3. **Node.js (Entorno para ejecutar JavaScript):**
   * Descárgalo e instálalo desde: [nodejs.org](https://nodejs.org/) *(Elige la versión LTS)*.

---

## Paso 2: Configurar pnpm y Clonar el Proyecto

Abre la terminal de tu computadora (o la terminal integrada de Visual Studio Code) y sigue estos comandos:

### 1. Instalar pnpm
Usamos **pnpm** porque es más rápido, eficiente y seguro que el gestor tradicional:

`npm install -g pnpm`

### 2. Clonar el repositorio a tu equipo

`git clone https://github.com/plasticdev06/epk-frontend.git`

`cd epk-frontend`

### 3. Instalar los paquetes del proyecto

`pnpm install`

### 4. Encender la aplicación en tu máquina

`pnpm dev`

*(Haz Clic o copia el enlace que te aparezca en la terminal, ej: `http://localhost:5173`, para ver la app en tu navegador)*.

---

## Reglas (Git & GitHub)

Para mantener el código ordenado y evitar borrar el trabajo de los demás, **está prohibido subir cambios directo a la rama main**.

### Flujo diario:

1. **Crear una rama propia antes de escribir código:**
   
   `git checkout -b feature/nombre-de-tu-tarea`
   
   *Ejemplo:* `git checkout -b feature/EPK-1-pantalla-login`

2. **Guardar tus avances:**
   
   `git add .`
   
   `git commit -m "Explicacion corta de lo que hiciste"`

3. **Subir tu rama a GitHub:**
   
   `git push origin feature/nombre-de-tu-tarea`

4. **Solicitar revisión:**
   * Entra a GitHub y presiona el botón **"Compare & pull request"** para enviar tu cambio a revisión.
