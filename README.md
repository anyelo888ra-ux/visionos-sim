# 🥽 visionOS Web Simulator

[![Status Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/anyelo888ra-ux/visionos-sim)
[![Platform WebAssembly](https://img.shields.io/badge/Platform-WebAssembly%20%7C%20Browser-blue.svg)](https://github.com/anyelo888ra-ux/visionos-sim)
[![License MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**visionOS Web Simulator** es una experiencia interactiva y ligera construida 100% para la web que emula la interfaz, el diseño de cristal (*glassmorphism*) y el sistema de interacción espacial de los **Apple Vision Pro**, optimizada especialmente para ordenadores de escritorio.

---

## 🔥 Características Principales

- 🖐️ **Hand Tracking en Vivo:** Utiliza **MediaPipe Hands** mediante la webcam para detectar los puntos de tus dedos en tiempo real (60 FPS) y navegar de manera espacial.
- 🖱️ **Modo Mouse Fallback (Fake Hand):** Si no tienes cámara o decides no dar permisos, una mano virtual interactiva controlada por el cursor del mouse toma el control con total fluidez.
- 🤏 **Gesto de Pinza (Pinch Gesture):** Simula clics espaciales calculando la distancia exacta entre el dedo índice y el pulgar.
- 🍏 **Sincronización Apple ID / Dispositivos:** Integración para conectar tu iPhone o iPad como trackpad o dispositivo de control remoto.
- ✨ **Interfaz Espacial (Glassmorphism):** Ventanas flotantes translúcidas con efectos de desenfoque avanzados inspirados en visionOS.

---

## ⚡ Inicio Rápido

1. Clona el repositorio o abre el archivo `index.html` directamente en tu navegador web (se recomienda Google Chrome o navegadores basados en Chromium con soporte para WebRTC/MediaPipe).
2. Otorga permisos de cámara si deseas probar el *Hand Tracking* con los dedos, o deniégalos para usar el modo de mano virtual con el mouse.
3. ¡Disfruta de la interfaz espacial y explora las aplicaciones flotantes!

---

## 📂 Estructura del Proyecto

```text
visionos-sim/
├── index.html        # Simulador completo (UI, MediaPipe Hands y lógica espacial)
├── LICENSE           # Licencia MIT de código abierto
└── README.md         # Documentación oficial del proyecto

```

---

## 🤝 Contribuir

¡Las contribuciones son totalmente bienvenidas! Si quieres proponer mejoras en los gestos, nuevas apps flotantes, optimizar el rendimiento o añadir animaciones 3D:

1. Haz un **Fork** del proyecto.
2. Crea una rama para tu característica (`git checkout -b feature/nueva-app`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadida nueva app flotante'`).
4. Sube la rama (`git push origin feature/nueva-app`).
5. Abre un **Pull Request**.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.
