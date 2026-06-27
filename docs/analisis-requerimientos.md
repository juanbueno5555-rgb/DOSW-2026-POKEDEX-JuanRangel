# DOSW - Pokédex - Análisis de Requerimientos

**Proyecto:** DOSW-2026-POKEDEX-JuanRangel
**Estudiante:** Juan David Rangel Jiménez
**Fecha:** 24/06/2026

---

## Requerimientos Funcionales (18 RFs)

### RF-001: Inicio de sesión con Gmail
El usuario debe poder autenticarse usando Google OAuth 2.0.

### RF-002: Crear perfil de usuario
Al autenticarse por primera vez, se crea perfil con username único.

### RF-003: Listar Pokémon
Listado paginado de todos los Pokémon.

### RF-004: Buscar Pokémon
Búsqueda por nombre o número de Pokédex.

### RF-005: Consultar detalle de Pokémon
Ver información completa: stats, evoluciones, habilidades.

### RF-006: Filtrar Pokémon
Filtros por tipo, región, generación, habilidad, mega evolución.

### RF-007: Guardar Pokémon favoritos
Marcar/desmarcar Pokémon como favoritos.

### RF-008: Crear equipo Pokémon
Equipos de hasta 6 Pokémon.

### RF-009: Visualizar equipo competitivo
Análisis de fortalezas, debilidades y balance de tipos.

### RF-010: Ver estadísticas de Pokémon
Ranking de consultas, tasa de elección en equipos.

### RF-011: CRUD de Pokémon (Admin)
Administrador crea, lee, actualiza y elimina Pokémon.

### RF-012: Administrar perfiles de usuarios (Admin)
Ver, desactivar, cambiar rol de usuarios.

### RF-013: Asistente Profesor Oak
Recomendaciones de Pokémon basadas en tipos y debilidades.

## Requerimientos No Funcionales (5 RNFs)

### RNF-001: Rendimiento
Respuesta < 3s para 95% de solicitudes.

### RNF-002: Seguridad
HTTPS, JWT con expiración, datos sensibles protegidos.

### RNF-003: Compatibilidad móvil
Diseño responsive para mobile, tablet y desktop.

### RNF-004: API REST
Endpoints REST con JSON.

### RNF-005: Mantenibilidad
Arquitectura en capas (Controller → Service → Repository).

## Reglas de Negocio

- RN-01: Login exclusivo con Google OAuth 2.0
- RN-02: Solo admin crea/modifica/elimina Pokémon
- RN-03: Equipo máximo 6 Pokémon
- RN-04: Usuario puede tener 1+ equipos
- RN-05: Número Pokédex único por Pokémon

---
*Documento completo en docs/analisis-requerimientos-eve.docx (plantilla oficial DOSW)*