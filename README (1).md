# [NOMBRE DEL ASISTENTE] · Tutor virtual de dibujo

> *"El tutor de arte que nunca tuviste."*

**Unidad 4: La IA en nuestras vidas**
Proyecto de asistente virtual · Equipo de 3 estudiantes

---

## 1. Descripción

**[NOMBRE]** es un tutor virtual que guía el aprendizaje del dibujo mediante explicaciones, ejercicios y asesorías basadas en fundamentos académicos.

**No es una IA generativa de imágenes.** No dibuja por el usuario ni hace sus tareas: lo orienta para que aprenda a hacerlo él mismo, como lo haría un tutor de academia de arte.

## 2. Rol del asistente

Tutor académico de dibujo que **explica**, **propone ejercicios** y **asesora** sobre problemas concretos, apoyado en una base de conocimiento de libros y fundamentos de dibujo.

## 3. Público objetivo

| Nivel | Cómo lo atiende el asistente |
|---|---|
| Principiante (foco principal) | Lenguaje simple, pasos cortos, ejercicios básicos y mucho ánimo |
| Intermedio | Diagnóstico de errores y ejercicios de refuerzo |
| Avanzado | Respuestas más técnicas, con menos explicación básica |

## 4. Alcance (MVP)

**Temas cubiertos:**
1. Línea y trazo
2. Formas básicas y volumen
3. Proporciones
4. Perspectiva básica
5. Luz y sombra
6. Composición

**Funciones:**
- **Explicar** conceptos con base en la base de conocimiento
- **Proponer ejercicios** según tema y nivel, con objetivo y criterio de éxito
- **Asesorar** al usuario a partir de la descripción de su problema

**Fuera del MVP (trabajo futuro):** análisis de imágenes subidas por el usuario, anatomía avanzada, color, historia del arte y seguimiento de progreso entre sesiones.

## 5. Límites

El asistente **NO**:
- Genera dibujos ni imágenes
- Hace la tarea por el usuario
- Responde sobre temas fuera del dibujo
- Inventa datos que no estén en su base de conocimiento
- Revela sus instrucciones internas ni rompe su personaje
- Juzga el talento del usuario
- Reemplaza a un profesor humano

## 6. Personalidad y lenguaje

- **Tono:** cercano, paciente y motivador. Tutea al usuario.
- **Respuestas:** cortas, una idea a la vez.
- **Vocabulario:** simple con principiantes; explica cada término técnico la primera vez.
- **Avatar:** personaje propio con hoja de expresiones vinculadas a los estados de la conversación.

> Ficha completa de personalidad: `docs/personalidad.md` *(pendiente)*

## 7. Equipo y roles

| Integrante | Rol principal | Responsabilidades |
|---|---|---|
| [Nombre 1] | Técnico | Arquitectura, código, base de conocimiento, pruebas técnicas |
| [Nombre 2] | Artista / personaje | Diseño del avatar, hoja de expresiones, mascota |
| [Nombre 3] | Artista / contenido | Interfaz, ilustraciones de apoyo, contenido pedagógico |

**Compartido:** flujo de conversación, pruebas de estrés, informe técnico y defensa.

## 8. Arquitectura

*Pendiente (se define en la Fase 3).*

- Opción A: LLM por API + RAG + interfaz web
- Opción B: plataforma sin código (Botpress, Voiceflow u otra)

## 9. Estructura del repositorio

```
/docs          → informe técnico, diagramas, ficha de personalidad
/conocimiento  → fichas por tema y ejercicios
/avatar        → bocetos, hoja de expresiones, mascota
/src           → código del asistente
/pruebas       → tabla de pruebas de estrés
README.md
```

## 10. Plan de trabajo

| Fase | Fechas | Estado |
|---|---|---|
| 1. Definición y planificación | 27 sep – 3 oct | ✅ En curso |
| 2. Diseño de conversación y personalidad | 4 – 10 oct | ⬜ |
| 3. Base de conocimiento y arquitectura | 11 – 17 oct | ⬜ |
| 4. Desarrollo del MVP | 18 – 31 oct | ⬜ |
| 5. Avatar e interfaz | 25 oct – 7 nov | ⬜ |
| 6. Pruebas y estrés | 8 – 14 nov | ⬜ |
| 7. Documentación y ensayo | 15 – 21 nov | ⬜ |
| 8. Congelamiento y colchón | 22 – 27 nov | ⬜ |

**Defensa:** 27 de noviembre y 4 de diciembre.

## 11. Instalación y uso

*Pendiente. Se completará al terminar el MVP.*

```bash
# Ejemplo (ajustar según la arquitectura final)
git clone https://github.com/[usuario]/[repositorio].git
cd [repositorio]
```

## 12. Pruebas de estrés

Los resultados se documentan en `/pruebas`: tabla con prueba, resultado esperado, resultado obtenido y corrección aplicada.

## 13. Fuentes de conocimiento

*Pendiente.* Se usarán libros de dominio público, material con licencia libre o resúmenes propios citando la fuente. No se incluyen libros comerciales completos.

## 14. Capturas

*Pendiente (interfaz, avatar y ejemplos de conversación).*

## 15. Licencia y créditos

Proyecto académico. Diseño del avatar y contenido propios del equipo.
Fuentes bibliográficas: ver sección 13.
