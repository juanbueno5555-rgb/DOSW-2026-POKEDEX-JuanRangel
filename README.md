# ⚡ EVE — Pokédex Inteligente

**DOSW 2026 — Intersemestral**  
**Proyecto Individual · Juan David Rangel Jiménez**

---

## 🧬 ¿Qué es EVE?

EVE (Explorador Visual de Especies) es una Pokédex web con inteligencia artificial.  
Explorá, buscá y filtrá Pokémon, armá equipos competitivos y recibí recomendaciones del **Profesor Oak**.

> **Stack:** Spring Boot · React · PostgreSQL · Google OAuth 2.0  
> **Arquitectura:** MVC en capas · REST/JSON · UUID v4

---

## ⚡ Diferenciador: Radar ↔ Focus

EVE no es una Pokédex más. Introduce un sistema de visualización que ninguna otra tiene:

| Modo Radar | Modo Focus |
|---|---|
| Pokémon en órbita circular | Detalle completo al centro |
| Barrido animado en tiempo real | Stats, evoluciones y acciones |
| Ideal para explorar y descubrir | Ideal para consulta profunda |

---

## 🎯 Funcionalidades

| RF | Funcionalidad | Prioridad |
|---|---|---|
| RF-001 | Gestión de Usuarios — Login Google, Perfil, Admin CRUD | 🔴 Alta |
| RF-002 | Gestión de Pokémon — Admin CRUD con soft delete | 🔴 Alta |
| RF-003 | Consulta — Listar, Buscar, Detalle de Pokémon | 🔴 Alta |
| RF-004 | Filtrado — Tipo, región, generación, rareza y más | 🟡 Media |
| RF-005 | Favoritos — Marcar/desmarcar con toggle visual | 🟡 Media |
| RF-006 | Equipos — Hasta 6 Pokémon + Análisis Competitivo | 🟡 Media |
| RF-007 | Estadísticas — Ranking, popularidad, tasa de elección | 🟢 Baja |
| RF-008 | Profesor Oak — IA de recomendación de equipos | 🟡 Media |

---

## 🎨 Prototipo — 3 Versiones

### V1 · HTML Interactivo (Radar/Focus)
Prototipo funcional con datos reales de PokéAPI.

👉 [Abrir prototipo V1](prototipo/eve-prototipo-radar-focus.html)

### V2 · Light Theme

![EVE Light Theme](assets/version2.png)

### V3 · Dark Theme

![EVE Dark Theme](assets/version3.png)

---

## 🔗 Enlaces

| Recurso | Link |
|---|---|
| 📋 Tablero Jira | [EV-1 → EV-29](https://mail-team-bzjlcy7a.atlassian.net/browse/EV-1) |
| 📄 Requerimientos | [docs/analisis-requerimientos.md](docs/analisis-requerimientos.md) |
| 📝 Plantilla Oficial | [docs/analisis-requerimientos-eve.docx](docs/analisis-requerimientos-eve.docx) |
| 🎨 Manual de Identidad | [docs/manual-identidad-eve.md](docs/manual-identidad-eve.md) |
| 🖥️ Prototipo HTML | [prototipo/eve-prototipo-radar-focus.html](prototipo/eve-prototipo-radar-focus.html) |

---

## 🎨 Paleta EVE

| Color | Hex | Modo |
|---|---|---|
| Deep Void | `#0A0A14` | Dark |
| Cream | `#FEF9F0` | Light |
| Violeta EVE | `#6C5CE7` | Acento |
| Rojo Poké | `#E84C3D` | Acento |

---

<p align="center"><em>"EVE no es una Pokédex más. Es TU compañera de viaje."</em></p>