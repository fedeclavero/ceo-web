# CEO-Web

Orquestador multi-agente para desarrollo web completo. Usa un modelo empresarial jerarquico: CEO -> Gerentes -> Ingenieros especializados.

## Instalacion

```bash
npx skills add fedeclavero/ceo-web
```

## Que hace

Construye sitios web completos delegando cada aspecto a un ingeniero especializado:

- **Gerente de Planificacion** — convierte requisitos en un plan de accion
- **Gerente de Revision** — auditoria final de calidad, seguridad y diseno
- **Ingeniero de Despliegue** — investiga restricciones de la plataforma
- **Ingeniero Creativo** — define diseno, colores, tipografia, mood
- **Ingeniero de Assets** — busca y descarga imagenes, SVGs, fuentes
- **Ingeniero Frontend** — construye HTML/CSS/JS vanilla
- **Ingeniero Adaptativo** — responsive, dark/light mode, cross-browser
- **Ingeniero Backend** — funcionalidad, APIs, logica
- **Ingeniero SEO** — metatags, schema.org, optimizacion GEO

## Flujo de trabajo

```
Humano -> CEO -> Gerente de Planificacion -> Ingenieros (secuencial)
                  -> Gerente de Revision -> CEO (prueba) -> Humano
                  ^--- iteraciones (max 4) ---|
```

## Requisitos previos

Algunos ingenieros necesitan skills adicionales. Si al ejecutar un ingeniero falta alguna, el CEO te lo indicara con el enlace para instalarla:

| Ingeniero | Skills requeridas |
|-----------|------------------|
| Planificacion | `brainstorming`, `writing-plans` |
| Creativo | `frontend-design`, `web-design-guidelines`, `ui-ux-pro-max` |
| Assets | `agent-browser` |
| Frontend | `frontend-design`, `web-design-guidelines`, `ui-ux-pro-max` |
| Adaptativo | `adapt` |
| Despliegue | `cloudflare` |
| SEO | `seo-geo`, `seo-audit` |
