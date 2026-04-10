# 🚀 Quick Setup para Nuevos Proyectos

Copia esta configuración a cualquier nuevo proyecto en 2 minutos.

## Opción 1: Copiar Archivos (Más rápido)

```bash
# En tu nuevo proyecto
cd mi-nuevo-proyecto

# Copiar desde boda-fiesta
cp -r ~/boda-fiesta/.claude .
cp ~/boda-fiesta/CLAUDE.md .
cp ~/boda-fiesta/settings.json .

# Instalar dependencias
npm install superpowers n8n-mcp browser-use claude-mem ui-ux-pro-max-skill everything-claude-code

# Commit y push
git add .
git commit -m "Setup: 7 Claude Code agents and skills"
git push origin main
```

## Opción 2: Clonar como Template (Recomendado)

```bash
# Clonar boda-fiesta como base
git clone https://github.com/Christian2002909/boda-fiesta.git mi-nuevo-proyecto
cd mi-nuevo-proyecto

# Cambiar el remote a tu nuevo repo
git remote set-url origin https://github.com/tu-usuario/mi-nuevo-proyecto.git

# Push inicial
git push -u origin main
```

---

## Qué se instala automáticamente:

✅ **Superpowers** - Framework agentico (Research→Spec→Plan→Test→Build)  
✅ **n8n-MCP** - Automatizaciones backend  
✅ **Claude-mem** - Memoria persistente  
✅ **UI/UX Pro Max** - Diseño inteligente  
✅ **Browser-use** - Control de navegador  
✅ **Everything-Claude-Code** - Sistema completo  
✅ **claude-token-efficient** - Optimización tokens (63% menos)

---

## Después de Setup:

1. **Verificar que todo funciona:**
   ```bash
   npm install  # Asegurar que todas las dependencias se instalan
   ```

2. **Empezar a usar:**
   - Los agentes se activarán automáticamente según lo que pidas
   - La configuración en CLAUDE.md se aplica a todas tus respuestas
   - Claude-mem guardará contexto automáticamente

3. **Personalizar (opcional):**
   - Editar `settings.json` para ajustar configuraciones específicas del proyecto
   - Editar `.claude/agents/*.json` para habilitar/deshabilitar agentes
   - Editar `CLAUDE.md` para agregar reglas específicas de tu proyecto

---

## Estructura Final:

```
mi-nuevo-proyecto/
├── .claude/
│   ├── agents/          (7 agentes configurados)
│   ├── memory/          (contexto persistente)
│   ├── hooks/           (automatizaciones)
│   └── README.md
├── CLAUDE.md            (reglas de optimización)
├── settings.json        (configuración global)
└── ... (tu código)
```

---

## Tips:

- **Una vez instalado, olvídate de la configuración** - Todo funciona automáticamente
- **Los agentes se adaptan a lo que pidas** - No necesitas activarlos manualmente
- **Reutiliza en todos tus proyectos** - La configuración es universal
- **Actualiza los MCPs cuando sea necesario** - `npm update`

¡Listo! Ahora tienes un setup profesional en cualquier proyecto. 🎯
