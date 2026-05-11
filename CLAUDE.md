# CLAUDE.md — Contexto para Claude Code

## Quién soy
- Nombre: Gary
- Background: Python, Snowflake, Google Sheets, Apps Script, pipelines de datos
- Objetivo: Dominar Claude para construir y mantener una app propia
- Nivel: Developer con experiencia, nuevo en ecosistema Claude/AI

## Este repositorio
Repositorio de aprendizaje estructurado hacia la certificación CCA-F
(Claude Certified Architect – Foundations).

## Stack técnico
- Lenguaje principal: Python
- Datos: Snowflake, Google Sheets
- Automatización: Apps Script
- AI: Claude API (Anthropic)

## Estructura del proyecto
```
claude-learning/
├── CLAUDE.md              # Este archivo — contexto para Claude Code
├── README.md              # Descripción pública del repo
├── .env.example           # Variables de entorno de ejemplo
├── .gitignore             # Archivos excluidos del repo
├── mes-1-fundamentos/     # Prompts y ejercicios del mes 1
├── mes-2-api/             # Scripts con Claude API
├── mes-3-agentes/         # Agentes y MCP servers
├── mes-4-5-ccaf/          # Preparación certificación
└── app/                   # Aplicación principal
```

## Reglas permanentes
- NUNCA subir API Keys — usar siempre .env (está en .gitignore)
- Guardar prompts que funcionen en mes-X/prompts/
- Actualizar este archivo cuando haya decisiones de arquitectura importantes
- Cada hito importante tiene su commit documentado

## Decisiones de arquitectura
| Fecha | Decisión | Razón |
|-------|----------|-------|
| 2026-05-11 | Repo creado | Inicio del roadmap CCA-F |

## Estado del roadmap
- Inicio: 11 mayo 2026
- Meta: Certificación CCA-F
- Fase actual: Mes 1 — Fundamentos
