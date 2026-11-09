# 📡 Morse Practice RU (Versión offline)

> **Gratis • Código abierto • Entrenador de código Morse en el navegador**  
> Soporte de alfabeto ruso + completamente offline (sin servidores externos). Instalable como PWA.

🇷🇺 [Русский (por defecto)](README.md) · 🇬🇧 [English](README-EN.md)

## 🚀 [PROBAR AHORA](https://agenticaijs.github.io/morse-practice-ru/)

> Sin instalación · Sin registro · 100 % gratis · **Funciona totalmente offline** después de la primera carga.
> Se puede instalar como PWA en la pantalla de inicio y abrir sin internet.

Este es un fork de [**ZP5DXS/morse-practice**](https://github.com/ZP5DXS/morse-practice) de Mathias Maidana (ZP5DXS).  
La interfaz original es inglés + español. Este fork añade interfaz en ruso y soporte del alfabeto Morse ruso.  
El proyecto original sigue bajo licencia MIT (ver [LICENSE](LICENSE)).

### Cambios en esta versión offline

- **Eliminadas / desactivadas** todas las funciones que requieren servidores de terceros:
  - Contadores globales de visitantes, países y horas de práctica
  - Botón y contador de “73”
  - Rankings semanales y por juego
  - Canal ON AIR (MQTT)
  - DUEL multijugador
  - Geolocalización por IP y API de estadísticas remota
- **Se mantiene** todo lo que funciona localmente en el navegador: oscilador CW, decodificador, llave vertical y paddles, curso Koch, Listen, Racer, juegos en modo individual, simulador de QSO local, lecciones personalizadas, progreso local (localStorage), temas.
- Añadidos botón **RU**, conmutador **A–Z ⇄ А–Я**, tabla de correspondencia Morse y decodificador de doble alfabeto.

### Uso del modo ruso

1. Abre el [entrenador](https://agenticaijs.github.io/morse-practice-ru/) — el idioma por defecto es el ruso.
2. Cambia el idioma con los botones **RU / EN / ES** en la cabecera.
3. Al seleccionar ruso, el alfabeto cambia automáticamente a **А–Я** (usa el conmutador **A–Z ⇄ А–Я** para volver al latino).
4. El botón **📋** muestra la tabla Latin ↔ Ruso.

### Qué sigue funcionando offline

- Sidetone CW, WPM, Farnsworth, ruido de banda
- Llave vertical y paddles (ratón, táctil, USB HID)
- Curso Koch, desafíos, práctica adaptativa, lecciones personalizadas
- Listen / head-copy
- Racer, Invaders, Battleship, Timing, Flappy (individual)
- Simulador local de QSO
- Estadísticas de errores y progreso locales
- Temas y recompensas que no requieren red

### Qué está desactivado

- Estadísticas y contadores globales  
- Botón “Send 73”  
- Leaderboards / rankings  
- ON AIR y DUEL en red  
- Cualquier llamada a `practice-api.zp5dxs.org` o brokers MQTT públicos  

El archivo `server-vps.js` se ha eliminado del repositorio — el frontend estático no necesita servidor.

---

## Créditos y licencia

MIT. Trabajo original © Mathias Maidana (ZP5DXS) — [ZP5DXS/morse-practice](https://github.com/ZP5DXS/morse-practice).  
Fork: [agenticaijs/morse-practice-ru](https://github.com/agenticaijs/morse-practice-ru).

73 y gracias al autor original.
