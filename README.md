# Agente de investigación para Codex

Archivos para descargar e instalar el agente `evidence_researcher`, que sintetiza literatura científica con fuentes verificables y comunica resultados, desacuerdos y límites.

## Descargar

En GitHub, usa **Code → Download ZIP**, o clona este repositorio.

## Instalar

1. Copia [`agents/evidence-researcher.toml`](agents/evidence-researcher.toml) a la carpeta `agents` de tu configuración de Codex (en Windows, normalmente `%USERPROFILE%\.codex\agents\`).
2. Copia la carpeta [`skills/evidence-research-synthesis`](skills/evidence-research-synthesis) a tu directorio de skills (por ejemplo, `%USERPROFILE%\.agents\skills\`).
3. Abre una sesión nueva de Codex y selecciona el agente `evidence_researcher` para una tarea de investigación.

El archivo del agente usa `gpt-5.6-terra` con esfuerzo `xhigh`. Ajusta esos valores si tu instalación no ofrece ese modelo o nivel. El agente menciona `paper-search`, `deep-research` y otras skills complementarias; las usa solo cuando están instaladas. La síntesis principal está incluida aquí.

## Archivos

- `agents/evidence-researcher.toml`: configuración del agente.
- `skills/evidence-research-synthesis/SKILL.md`: método de síntesis de evidencia.

No incluye papers, documentos personales, credenciales ni resultados de investigaciones anteriores.
