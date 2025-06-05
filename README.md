Gestor de turnos - Salon de belleza

es una proyecto web simple para dar solucion a un problema de turnos en un salon de belleza este fue desarrollado en **JavaScript puro (vanilla JS)** que permite a los usuarios **reservar y cancelar turnos** en un salon de belleza.

Este sistema almacena los datos localmente en el navegador utilizando `localStorage`, por lo que no necesita base de datos ni servidor. Ideal como MVP (Producto Mínimo Viable) para una presentación facil y demostrativa y de forma rapida

---

## 🚀 Funcionalidades

- 🕒 Lista de turnos disponibles.
- 🧍‍♂️ Ingreso del nombre del cliente.
- ✅ Reserva de turnos.
- ❌ Cancelación de turnos reservados.
- 💾 Persistencia de reservas con `localStorage`.

---

## 🧑‍💻 Tecnologías usadas

- HTML5
- CSS3
- JavaScript (vanilla)

---

## 🗂 Estructura del proyecto

```bash
📁 Reserva-de-Turnos/
├── index.html     # Página principal con todo el código (HTML + CSS + JS)
├── README.md      # Documentación del proyecto

Como usarla
git clone https://github.com/Daga1984/Reserva-de-Turnos.git

cd Reserva-de-Turnos
start index.html   # En Windows
# o
open index.html    # En macOS

Flujo de trabajo con Git Flow (simplificado)
Este proyecto implementa una estructura básica de Git Flow:

main: versión estable.

develop: versión en desarrollo.

feature/*: funcionalidades específicas (ej: feature/agregar-campo-nombre).

Puedes seguir este flujo para mantener una buena organización durante el desarrollo.

Mejoras futuras (ideas)
Login de cliente con autenticación básica.

Backend en Node.js con base de datos (MongoDB o SQLite).

Responsive design y mejoras visuales (usando TailwindCSS o Bootstrap).

Panel de administración para ver todos los turnos reservados.




