# 🥽 visionOS Web Simulator & Spatial Ecosystem

<p align="center">
  <img src="banner.svg" alt="visionOS Web Simulator Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/anyelo888ra-ux/visionos-sim"><img src="https://img.shields.io/badge/Status-Active-brightgreen.svg" alt="Status"></a>
  <a href="https://visionos-sim.vercel.app/"><img src="https://img.shields.io/badge/Web-Live--Demo-38bdf8.svg" alt="Live Demo"></a>
  <a href="https://github.com/anyelo888ra-ux/visionos-sim/releases"><img src="https://img.shields.io/badge/Android-APK%20Release-emerald.svg" alt="Android APK"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License"></a>
</p>

**visionOS Web Simulator** es una experiencia web interactiva de alto rendimiento que recrea el entorno espacial, la estética de cristal (*glassmorphism*) y el sistema de interacción táctil/gestual de los **Apple Vision Pro**. 

Permite ser controlado por webcam (MediaPipe Hands), mouse, control remoto nativo desde Android (*visionOS Controller APK*) o mediante comandos de chat en vivo de Twitch.

---

## 🔥 Características Principales

- 🖐️ **Hand Tracking 60 FPS:** Navegación espacial por webcam detectando puntos de articulación manuales mediante **MediaPipe Hands**.
- 📱 **Controlador Android Nativo (APK):** App en Kotlin/Jetpack Compose con trackpad multitáctil, corona digital interactiva, biometría y comunicación por IP local o USB.
- 🎮 **Chat Use visionOS (Twitch Control):** Conexión IRC directa para que tus espectadores de Twitch jueguen y controlen las ventanas con comandos (`!youtube`, `!snake`, `!notes`, `!up`, `!down`, etc.).
- 🐍 **Snake Arcade Pro:** Minijuego espacial integrado controlable por teclado, gestos o comandos del chat.
- 🌐 **Sincronización IP Dinámica:** Enlace flexible por red Wi-Fi LAN o depuración ADB USB sin IPs estáticas hardcodeadas.
- ✨ **Glassmorphism Avanzado:** Ventanas flotantes arrastrabiles con desenfoque de fondo en tiempo real (*backdrop-filter*).

---

## ⚡ Inicio Rápido

1. Visita la versión en vivo en [visionos-sim.vercel.app](https://visionos-sim.vercel.app/) o descarga este repositorio.
2. Descarga e instala la app de Android desde las [GitHub Releases](https://github.com/anyelo888ra-ux/visionos-sim/releases).
3. Conecta ambos dispositivos a la misma red Wi-Fi e introduce la IP de tu PC para sincronizar el control remoto.

---

## 📂 Estructura del Proyecto

```text
visionos-sim/
├── index.html        # Simulador web completo (UI, MediaPipe, Twitch IRC y Snake)
├── favicon.svg       # Icono espacial del ecosistema
├── banner.svg        # Banner gráfico promocional para Twitter, Discord y OpenGraph
├── LICENSE           # Licencia MIT de código abierto
└── README.md         # Documentación oficial del proyecto
```

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Para agregar nuevas apps o gestos:

1. Haz un **Fork** del repositorio.
2. Crea una rama para tu mejora (`git checkout -b feature/nueva-app`).
3. Guarda tus cambios (`git commit -m 'Añadida nueva app espacial'`).
4. Sube la rama (`git push origin feature/nueva-app`).
5. Abre un **Pull Request**.

---

## 📄 Licencia

Distribución bajo Licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.