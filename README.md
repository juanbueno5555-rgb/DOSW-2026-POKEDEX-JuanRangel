# EVE — Pokedex Inteligente

**DOSW 2026 Intersemestral · Proyecto Individual**
**Estudiante:** Juan David Rangel Jimenez

---

## Descripcion

EVE (Explorador Visual de Especies) es una Pokedex web con asistente de IA. Permite explorar, buscar y filtrar Pokemon, crear equipos competitivos con analisis de fortalezas y debilidades, y recibir recomendaciones personalizadas del **Profesor Oak**.

### Stack
- **Backend:** Spring Boot + JPA + PostgreSQL
- **Frontend:** React
- **Autenticacion:** Google OAuth 2.0
- **APIs:** REST con JSON, UUID v4

### Diferenciador: Radar ↔ Focus
EVE introduce un sistema de visualizacion unico:
- **Modo Radar:** Pokemon en anillo circular con barrido animado
- **Modo Focus:** Detalle completo al centro con stats y acciones
- Ninguna otra Pokedex tiene este concepto

---

## Funcionalidades

| RF | Funcionalidad |
|---|---|
| RF-001 | Gestion de Usuarios (Login Google + Perfil + Admin CRUD) |
| RF-002 | Gestion de Pokemon (Admin CRUD) |
| RF-003 | Consulta de Pokemon (Listar, Buscar, Detalle) |
| RF-004 | Filtrado y Organizacion (tipo, region, generacion, rareza, etc.) |
| RF-005 | Gestion de Favoritos |
| RF-006 | Gestion de Equipos + Analisis Competitivo |
| RF-007 | Estadisticas de Uso (ranking, popularidad) |
| RF-008 | Asistente Profesor Oak (IA) |

---

## Prototipo

### V1: HTML Interactivo (Radar/Focus)
👉 [Abrir prototipo](prototipo/eve-prototipo-radar-focus.html)

### V2: Light Theme (OpenPencil)
![Version 2 - Light Theme](assets/version2.png)

### V3: Dark Theme (OpenPencil)
![Version 3 - Dark Theme](assets/version3.png)

---

## Enlaces

| Recurso | Enlace |
|---|---|
| 📋 **Tablero Jira** | [EV-1 al EV-29](https://mail-team-bzjlcy7a.atlassian.net/browse/EV-1) |
| 📄 **Requerimientos** | [docs/analisis-requerimientos.md](docs/analisis-requerimientos.md) |
| 🎨 **Manual de Identidad** | [docs/manual-identidad-eve.md](docs/manual-identidad-eve.md) |
| 🖥️ **Prototipo HTML** | [prototipo/eve-prototipo-radar-focus.html](prototipo/eve-prototipo-radar-focus.html) |

---

## Paleta EVE

| Color | Hex | Uso |
|---|---|---|
| Deep Void | `#0A0A14` | Dark mode |
| Cream | `#FEF9F0` | Light mode |
| EVE Violet | `#6C5CE7` | Acento principal |
| Pokemon Red | `#E84C3D` | Acento alternativo |

---

> **"EVE no es una Pokedex mas. Es TU companera de viaje."**
