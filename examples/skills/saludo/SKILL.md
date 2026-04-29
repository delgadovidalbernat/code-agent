---
name: saludo
description: Saluda al usuario con un mensaje personalizado
user-invocable: true
author: delgadovidalbernat
tags:
  - ejemplo
  - comando
  - demo
---

# Comando: /saludo

Cuando el usuario invoque `/saludo [nombre]`, responde con:
**"¡Hola, [nombre]! Este es tu comando personalizado."**

Si no se proporciona un nombre, usa **"usuario"** como valor por defecto.

---
## Ejemplo de uso
- `/saludo` → "¡Hola, usuario! Este es tu comando personalizado."
- `/saludo Ana` → "¡Hola, Ana! Este es tu comando personalizado."

---
## Cómo instalar
1. Copia esta carpeta (`saludo`) a:
   - `~/.vibe/skills/` (para uso global)
   - o `.vibe/skills/` en tu proyecto (para uso local).
2. Reinicia Vibe CLI o ejecuta `/reload` para cargar el comando.
3. Prueba el comando escribiendo `/saludo` o `/saludo TuNombre`.
