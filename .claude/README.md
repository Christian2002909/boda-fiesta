# Claude Code - Advanced Configuration

Este directorio contiene la configuración completa de agentes, skills y optimizaciones para Claude Code.

## Estructura

```
.claude/
├── agents/              # Configuración de todos los agentes y skills
│   ├── n8n-mcp.json
│   ├── claude-mem.json
│   ├── ui-ux-pro-max.json
│   ├── browser-use.json
│   ├── everything-claude-code.json
│   └── claude-token-efficient.json
├── memory/             # Almacenamiento de contexto persistente (claude-mem)
├── hooks/              # Hooks automáticos para eventos
└── README.md          # Este archivo
```

## Agentes Instalados

### 1. **n8n-MCP** - Automatizaciones Backend
- Integración con n8n workflows
- Validación de automatizaciones
- Testing de procesos backend

### 2. **Claude-mem** - Memoria Persistente
- Contexto entre sesiones
- Almacenamiento de preferencias
- Aprendizaje del codebase

### 3. **UI/UX Pro Max** - Diseño Inteligente
- Patrones profesionales de UI/UX
- Sistemas de color y tipografía
- Animaciones y diseño multi-plataforma

### 4. **Browser-use** - Control de Navegador
- Automatización web real
- Interacción con formularios
- Captura de pantallas
- Ejecución de tests

### 5. **Everything-Claude-Code** - Sistema Completo
- Optimización de performance
- Manejo mejorado de contexto
- Skills preinstaladas
- Mejoras de seguridad

### 6. **claude-token-efficient** - Optimización de Tokens
- Reducción ~63% en uso de tokens
- Configuración en CLAUDE.md
- Respuestas más concisas

## Configuración Principal

Ver `../settings.json` para configuración global y `../CLAUDE.md` para reglas de respuesta.

## Activar/Desactivar Agentes

Edita el archivo JSON correspondiente en `agents/` y cambia `"enabled": false` si necesitas desactivar uno.

## Instalación de Dependencias

Para instalar todos los MCPs y skills:

```bash
npm install n8n-mcp browser-use claude-mem ui-ux-pro-max-skill everything-claude-code
```

## Actualización

Los agentes se mantenienen actualizados automáticamente según su configuración en settings.json.
