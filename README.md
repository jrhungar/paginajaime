# Buzón de sugerencias — Posada de fin de año (MRII)

Página donde el equipo de MRII propone y vota fecha y restaurante
para la cena de fin de año.

**Datos:** vienen de Supabase (tablas `fechas_propuestas` y
`lugares_propuestas`); nada se escribe a mano en el HTML.

**`.claude/agents/revisor-antes-de-publicar.md`:** un subagente que
revisa la página antes de publicar (llaves secretas, colores,
calidad del código) y solo reporta, nunca arregla nada.

**Para seguirle:**
1. Pide el cambio a Claude sobre este repositorio.
2. Revisa la vista previa que Netlify genera en la rama.
3. Di "haz pull y despliegue" para fusionar a `main` y publicar.

Las reglas completas están en `CLAUDE.md`.
