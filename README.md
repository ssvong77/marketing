# 🎙️ Te Lo Cuento - Producción Pro

**Crea videos con visualizadores de audio, voz en off y música de fondo directamente desde tu navegador.**  
Sin servidores, sin marcas de agua, sin límites. Todo el procesamiento de audio y video se realiza localmente en tu dispositivo.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-FF9800?style=for-the-badge&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🌟 Características Principales

### 🎵 Edición y Mezcla de Audio Profesional
* **Marcado de Inicio Preciso:** Panel de preview con slider táctil y botones de salto (`-10s`, `-1s`, `+1s`, `+10s`) para saltar intros largas y marcar el punto exacto donde inicia la música.
* **Fade-in Automático (Pro):** Cuando tu voz termina, la música sube suavemente al 100% de volumen usando `linearRampToValueAtTime` de Web Audio API, garantizando transiciones matemáticamente perfectas y sin distorsión.
* **Fade-out Suave (Pro):** Cierre profesional con desvanecimiento nativo de audio en los últimos 3 segundos, sin "clicks" ni artifacts sonoros.
* **Limitador Integrado (Anti-Clipping):** Utiliza un `DynamicsCompressor` nativo para evitar que el audio sature o distorsione al subir el volumen al 100%.
* **Control de Duración:** Límites predefinidos para redes sociales (30s, 60s, **90s para WhatsApp**, 120s) o duración libre. La música se adapta automáticamente al video, sin cortar nunca tu voz.

### 🎨 Visualización y Video
* **Efectos Reactivos:** 4 efectos visuales (Barras, Onda Suave, Círculos, Partículas) que reaccionan en tiempo real a las frecuencias de tu voz.
* **Fondos Dinámicos:** Soporte para imágenes y videos en bucle con ajuste automático (*contain*) para cualquier resolución.
* **Formatos Múltiples:** Exporta en Horizontal (16:9 - YouTube/PC), Vertical (9:16 - TikTok/Reels/Shorts) o Automático.
* **Tiempo Extra:** Configura segundos adicionales al final del video para un cierre más natural.
* **Cierre Cinematográfico:** Cuando tu voz termina, los efectos se apagan y la música toma protagonismo con un fade-in al 100%, creando un final profesional estilo documental o programa de radio.

### ⚡ Rendimiento y Privacidad
* **100% Cliente (Client-Side):** Tus archivos de audio e imagen nunca se suben a ningún servidor. Todo se procesa en tu navegador.
* **Exportación Automática:** Genera y descarga el video final en formato `.webm` con un solo clic.
* **Audio sin Distorsión:** Las automatizaciones de volumen se ejecutan a nivel de hardware de audio, eliminando por completo cualquier ruido, pop o click en las transiciones.

---

## 🚀 Cómo usarlo

1. **Clona el repositorio** o descarga el archivo `index.html`.
2. Abre el archivo en un navegador moderno (Se recomienda **Google Chrome**, **Edge** o **Brave** para el mejor soporte de `MediaRecorder` y `Web Audio API`).
3. **Carga tus archivos:**
   * Un fondo (Imagen o Video).
   * Tu Audio Principal (Voz / Podcast).
   * Música de Fondo.
4. **Edita la música:** Usa el panel de preview para escuchar, navegar con el slider o botones de salto, y marcar el punto exacto donde quieres que inicie la canción.
5. **Configura:** Elige el efecto visual, la orientación, el tiempo extra y el límite de duración de la música.
6. **Exporta:** Haz clic en `💾 Exportar` y el video se descargará automáticamente al finalizar.

---

## 📋 Flujo de trabajo recomendado

### Para Estados de WhatsApp (máximo 90s):
