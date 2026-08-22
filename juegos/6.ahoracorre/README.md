# 💰 Ahorra y Corre

![Captura del juego](capturas/juego6.png)

---

## 📖 Descripción

**Ahorra y Corre** es un videojuego educativo de tipo "runner" infinito diseñado para enseñar a jóvenes de 18 a 25 años el valor del ahorro y la toma de decisiones financieras responsables. El jugador controla a un personaje que debe correr mientras recolecta monedas (ahorros) y esquiva obstáculos que representan gastos innecesarios (cafés, tarifas, compras impulsivas). El objetivo es alcanzar la meta de $2000 en ahorros, comenzando con $500.

**Objetivo del jugador:**  
Alcanzar los $2000 en ahorros esquivando gastos y recolectando monedas, sin gastar todo el dinero.

**Mecánica principal:**  
El jugador controla un personaje en movimiento automático hacia la derecha. Usa las teclas **↑ (arriba)** para saltar obstáculos en el suelo, y **↓ (abajo)** para agacharse y esquivar obstáculos aéreos. Las monedas aparecen en el camino y suman $100 cada una; los obstáculos restan $50. El juego aumenta su velocidad progresivamente.

---

## 🎮 Género

`Educativo` | `Runner` | `Arcade` | `Simulación financiera`

---

## 🎯 Controles

| Tecla | Acción |
|-------|--------|
| `↑ (Arriba)` | Saltar (para evitar gastos en el suelo) |
| `↓ (Abajo)` | Agacharse (para evitar gastos aéreos) |

> **Nota:** El juego está diseñado para jugarse con teclado. La velocidad aumenta automáticamente con el tiempo.

---

## ⚙️ Tecnología

- **Lenguaje:** HTML, CSS y JavaScript (vanilla)
- **Renderizado:** Canvas 2D
- **Assets:** Imágenes propias (fondo, jugador, moneda, obstáculo, meta)
- **Audio:** Música de fondo loop (formato MP3)
- **Alojamiento:** GitHub Pages (juego 100% en navegador)

---

## 📋 Características principales

| Característica | Estado |
|----------------|--------|
| Runner lateral infinito con control de salto y agacharse | ✅ |
| Sistema de ahorros ($500 inicial, meta $2000) | ✅ |
| Obstáculos de suelo (obligan a saltar) y aéreos (obligan a agacharse) | ✅ |
| Monedas que suman $100 al ser recolectadas | ✅ |
| Velocidad progresiva (aumenta cada 10 segundos) | ✅ |
| Barra de progreso visual hacia la meta | ✅ |
| Feedback visual (partículas, textos flotantes, temblor) | ✅ |
| Pantallas de inicio, game over (bancarrota) y victoria (meta alcanzada) | ✅ |
| Música de fondo ambiental | ✅ |
| Funciona en navegador web | ✅ |

---

## 📋 Game Design Document (GDD) - Resumen

| Componente | Descripción |
|------------|-------------|
| **Concepto / Premisa** | Un joven debe correr acumulando ahorros mientras evita gastos innecesarios. |
| **Género** | Runner educativo / Arcade financiero. |
| **Objetivo del jugador** | Alcanzar $2000 en ahorros comenzando con $500. |
| **Mecánica principal** | Saltar (↑) y agacharse (↓) para esquivar obstáculos; recolectar monedas automáticamente al pasar. |
| **Reglas** | Cada obstáculo resta $50; cada moneda suma $100; el juego termina si los ahorros llegan a $0 o si alcanzas $2000. |
| **Progresión** | La velocidad del juego aumenta cada 10 segundos, haciendo más difícil esquivar. |
| **Personajes** | Un personaje jugable sin diálogos ni historia. |
| **Arte / estilo visual** | Estilo plano con colores vivos y fondos urbanos; inspirado en juegos runner clásicos. |
| **Público objetivo** | Jóvenes de 18 a 25 años interesados en educación financiera. |
| **Condición de victoria** | Alcanzar $2000 en ahorros. |
| **Condición de derrota** | Los ahorros llegan a $0 (bancarrota). |

---

## 🤖 Uso de IA

Este videojuego fue desarrollado con asistencia de inteligencia artificial:

- **Generación del código base:** ChatGPT / QWEN 3.7 (estructura HTML, CSS y JavaScript con Canvas).
- **Diseño de la mecánica financiera:** La IA ayudó a definir el equilibrio entre monedas ($100) y penalizaciones (-$50), así como la meta de $2000.
- **Corrección de errores:** Se depuraron problemas de colisión, animación de agachado y gestión de partículas.
- **Generación de assets:** Las imágenes (fondo, jugador, moneda, obstáculo, meta) fueron creadas con herramientas de IA y editadas para el juego.
- **Contenido educativo:** Los mensajes de game over y victoria fueron diseñados para reforzar el aprendizaje financiero.

---

## 🧠 ¿Qué aprendí?

- **Diseño de juegos educativos con GDD:** Aprendí a estructurar un Game Design Document completo y a usarlo como guía para la programación.
- **Runner con dos mecánicas:** Implementar tanto salto como agachado en un mismo juego requiere manejo cuidadoso de colisiones y estados del personaje.
- **Sistema de progresión y balanceo:** Ajustar la velocidad, la frecuencia de spawn de obstáculos y monedas para mantener la dificultad justa y motivadora.
- **Feedback visual y sonoro:** Uso de partículas, textos flotantes, temblor de pantalla y música para enriquecer la experiencia del jugador.
- **Iteración con IA:** Refinar prompts para obtener mejoras específicas en la jugabilidad y la experiencia de usuario.

---

## 🔮 Mejoras futuras

- [ ] Agregar más tipos de obstáculos (gastos variados con diferentes penalizaciones).
- [ ] Incluir power-ups (ej. escudo temporal, multiplicador de monedas).
- [ ] Sistema de puntuación alta con almacenamiento local.
- [ ] Niveles con diferentes metas financieras (ej. $5000, $10000).
- [ ] Traducción a inglés para mayor alcance.
- [ ] Soporte para pantalla táctil (gestos de deslizar).

---

## ▶️ Cómo jugar

**Jugar online (recomendado):**  
👉 [**Jugar Ahorra y Corre**](https://DarkStar303.github.io/project-library-game-development/juegos/6.ahoracorre/ahorraycuerre.html)

**Descargar y jugar localmente:**  
1. Clona el repositorio o descarga los archivos.
2. Abre el archivo `ahorraycorre.html` en tu navegador favorito.
3. ¡Empieza a ahorrar y corre hacia la meta!

---
