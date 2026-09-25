# 🎮 3 en Raya (Tic-Tac-Toe) - Edición Pro

Un juego interactivo y moderno de **3 en Raya (Tic-Tac-Toe)** desarrollado con **HTML5**, **Tailwind CSS** y **JavaScript Vanilla**. Diseñado con una interfaz limpia en modo oscuro, efectos de sonido sintetizados y soporte para partidas contra una Inteligencia Artificial imbatible.

🌐 **Demo en vivo:** [https://sensational-donut-cf3f0c.netlify.app](https://sensational-donut-cf3f0c.netlify.app)

---

## ✨ Características Principales

- 🎨 **Interfaz Moderna & Neón**:
  - Estilo oscuro (*Dark Mode*) con efectos de iluminación neón (Cyan para **X** y Rosa para **O**).
  - Animaciones de pulsación, pop-in para las fichas y resaltado de la línea ganadora.
  - Diseño 100% responsivo (funciona en móviles, tablets y ordenadores).

- 🕹️ **3 Modos de Juego**:
  - **2 Jugadores (Local)**: Modo clásico para jugar por turnos en el mismo dispositivo.
  - **IA Fácil**: Inteligencia artificial relajada para partidas casuales.
  - **IA Imbatible (Algoritmo Minimax)**: Inteligencia artificial que calcula el movimiento óptimo en cada turno. Es matemáticamente imposible ganarle (el mejor resultado es el empate).

- 🔊 **Efectos de Sonido Dinámicos**:
  - Sonidos generados en tiempo real mediante la **Web Audio API** (sin dependencias ni archivos de audio externos).
  - Incluye botón para silenciar/activar el audio.

- 🎉 **Celebración de Victoria**:
  - Efecto de lluvia de confeti en victorias mediante Canvas-Confetti.
  - Ventana modal con el resultado y botón de revancha rápida.

- 📊 **Marcador Persistente**:
  - Guarda el conteo de victorias de X, O y empates en el navegador mediante `localStorage`.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 Semántico**: Estructura accesible con soporte para navegación por teclado y lectores de pantalla.
- **Tailwind CSS**: Estilizado ágil con clases de utilidad y configuración personalizada de sombras y colores.
- **JavaScript (ES6+)**: Lógica del juego, implementación del algoritmo Minimax y manipulación dinámica del DOM.
- **Web Audio API**: Generación de frecuencias y envolventes de audio nativas.
- **FontAwesome**: Iconografía vectorial limpia.

---

## 🚀 Cómo Ejecutarlo Localmente

1. Clona este repositorio o descarga los archivos:
   ```bash
   git clone https://github.com/CarbonellLeonardo123/tic-tac-toe.git
   ```
2. Abre la carpeta del proyecto.
3. Haz doble clic en `index.html` para abrirlo directamente en tu navegador favorito (Chrome, Edge, Firefox, Safari).

---

Desarrollado como proyecto académico de programación web.
