# 📟 Calculadora de ResiDeus Cyberpunk

¡Saludos, corillo! 🇵🇷 Bienvenidos a la **Calculadora de ResiDeus**, una aplicación web progresiva (PWA) de estilo retro-futurista diseñada específicamente para resolver uno de los dilemas más grandes al salir a comer o janguear en Puerto Rico: **calcular el IVU, la propina y cuadrar el bendito serrucho de la cuenta sin trancarse.**

Desarrollada con un motor analítico optimizado para iOS (Safari/iPhone), esta interfaz combina una estética inspirada en terminales de fósforo verde, luces de neón parpadeantes y efectos de audio sintetizados mediante código nativo.

---

## 🚀 Características Clave (El Piquete)

- **📟 Pantalla LCD Dinámica:** Monitorea desgloses de IVU, propina y descuento en tiempo real con opacidades inteligentes de brillo completo (`opacity: 1`) que se iluminan al activar cada función.
- **🌌 Recibo Holográfico Proyectado:** En lugar de las alertas aburridas del navegador, la app proyecta un modal flotante con estilo CRT de vectores de neón, filtro de interferencia y desenfoque de cristal (`backdrop-filter: blur`) que cambia de color según el tema activo.
- **🪓 Motor de Serrucho Flexible:** Permite ingresar inputs libres (incluyendo `0` y `1`) con protección matemática contra división por cero tras bastidores.
- **⌨️ Teclado Numérico Liberado:** Soporte extendido de punto decimal (`.`) de hasta 4 caracteres tanto en **Descuento** como en **Propina** para procesar tasas exactas (ej. `11.5%` o `15.5%`).
- **💬 Animación Cyberpunk Orgánica:** La pantalla verde cuenta con una animación cíclica basada en CSS puro que simula el tipeado mecánico de tres puntos (`...`) mientras espera datos del usuario.
- **🎨 Selector de Temas Neón:** Cambia instantáneamente todo el ecosistema visual de la app rotando entre 4 paletas de color con el botón físico `TEMA`:
  - 🌟 *Cyberpunk* (Rosa Eléctrico & Violeta)
  - 🏆 *Retro Gold* (Ámbar & Piedra)
  - 📟 *Matrix* (Verde Fósforo de Terminal)
  - 🌅 *Sunset* (Naranja Quemado & Óxido)
- **🔊 Audio Sintetizado Nativo:** Sonidos retro de clics y confirmaciones generados matemáticamente mediante la *Web Audio API* (sin archivos pesados ni consumo de datos offline).

---

## 🛠️ Tecnologías Utilizadas

Para garantizar un rendimiento ultra ligero y capacidad de funcionamiento 100% offline (ideal para cuando no hay señal en el restaurante), el proyecto está construido con:

* **HTML5 Nativo:** Estructuración limpia y semántica del chasis físico.
* **CSS3 Avanzado:** Animaciones de vectores `@keyframes`, mallas 3D en perspectiva, efectos glitch y diseño responsive *Mobile-First*.
* **JavaScript Puro (Vanilla JS):** Motor analítico de cálculo, persistencia de memorias al conmutar menús y manipulación del DOM en tiempo real.
* **Web Audio API:** Generación de osciladores de sonido sintético en vivo.

---

## 📂 Estructura del Archivo Unificado

El proyecto está diseñado bajo la filosofía de "Single-File Architecture". Todo el sistema vive dentro de un único archivo de alto rendimiento:

```text
├── index.html       # Todo el HTML, CSS, lógicas de cálculo y audio
└── icon.jpg         # Icono de acceso directo en caché para iOS/iPhone
```

---

## 📱 Instalación en iPhone (PWA/Home Screen)

Para llevar la calculadora en tu celular como si fuera una aplicación nativa de la App Store:

1. Sube el archivo `index.html` y tu `icon.jpg` a tu hosting o servidor.
2. Abre la ruta en **Safari** desde tu iPhone.
3. Toca el botón de **Compartir** (el cuadrado con la flecha hacia arriba abajo en la pantalla).
4. Selecciona la opción **"Agregar a pantalla de inicio"** (Add to Home Screen).
5. ¡Listo! Ya tienes el acceso directo neón con pantalla completa e integración traslúcida en la barra de estado de iOS.

---

## 📝 Notas para Modificaciones Futuras

El código fuente está rigurosamente documentado mediante comentarios estructurados por bloques para facilitar cambios más adelante:
* **Audio:** Busca la función `reproducirSonido(tipo)` para alterar los tipos de osciladores (`sine`, `triangle`, `sawtooth`) y las frecuencias de hercios.
* **Colores de Neón:** Busca los selectores `body.theme-` en el CSS para alterar las intensidades de las sombras (`box-shadow`) y gradientes de fondo.
* **Mensajes:** Modifica la función `abrirHologramaRecibo()` si deseas reestructurar el diseño de impresión del texto del recibo copiado.

---

 Desarrollado con orgullo y piquete cyberpunk desde Puerto Rico. ¡Disfruta la app y que no te claven con el serrucho! 🇵🇷📟
