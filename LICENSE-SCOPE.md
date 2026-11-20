# Alcance de la licencia de los paquetes portables HUBI

Ferced Labs autorizó el 19 de noviembre de 2026 la licencia MIT para la skill,
los manifests y el contrato exportado incluidos en los paquetes portables HUBI.
El texto aprobado está en `LICENSE`, con copyright de 2026 Ferced Labs.

En cada paquete, la concesión MIT se aplica exclusivamente a:

- `skills/hubi/SKILL.md`;
- `skills/hubi/references/contract.json`, como instantánea exportada;
- los manifests `.claude-plugin/plugin.json` y `.mcp.json` de Claude, o
  `plugin.json` y `mcp.json` de ChatGPT/Codex.

El aviso no concede una licencia sobre el resto del repositorio, el código del
hub, el firmware, el servicio alojado, las políticas de privacidad o términos,
los iconos, las marcas ni otros activos gráficos. Exportar el contrato no
extiende MIT al código fuente que lo genera. La licencia tampoco acredita
aprobación de políticas, registro de clientes OAuth o aceptación de plataformas.

El generador incorpora `LICENSE` desde `license.text` de la configuración y
declara `license.spdx` en los manifests. Para estos paquetes aprobados se usa
`MIT` y el texto exacto de `integrations/hubi/LICENSE`; también incluye este aviso
de alcance. La configuración de ejemplo queda incompleta deliberadamente:
requiere metadatos, icono y clientes reales antes de generar artefactos.
