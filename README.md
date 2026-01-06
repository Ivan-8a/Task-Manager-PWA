https://pwa-react-todolist.vercel.app/
# 📝 PWA React TodoList

Una aplicación de gestión de tareas progresiva, rápida e instalable, construida con el ecosistema moderno de React.

## 🚀 Características Principales (Key Features)

Este proyecto demuestra la implementación de capacidades nativas en la web:

* **PWA (Progressive Web App):**
    * Funciona **sin conexión** (Offline-first) gracias a la configuración personalizada de Service Workers (`sw.js`).
    * **Instalable** en dispositivos móviles y escritorio (simula una app nativa).
* **Gestión de Estado:** Manejo eficiente del estado de las tareas (CRUD: Crear, Leer, Actualizar, Borrar).
* **Persistencia de Datos:** Uso de `localStorage` para guardar las tareas del usuario entre sesiones.

## 🛠️ Stack Tecnológico

* **Frontend:** React 18+
* **Build Tool:** Vite (para tiempos de carga y construcción optimizados).
* **PWA Core:** Service Worker API + Web App Manifest.
* **Calidad de Código:** ESLint.

## 🧠 Desafíos Técnicos y Aprendizajes


1.  **Ciclo de vida del Service Worker:** Aprendí a manejar la caché de archivos estáticos para que la app cargue instantáneamente incluso sin red.
2.  **Optimización de Assets:** Configuración de iconos y meta-tags para cumplir con los estándares de instalación de PWA (Lighthouse audit).

## 📦 Instalación y Despliegue

```bash
npm install
npm run dev
