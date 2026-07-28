# Modulador de Voz

App web simple que cambia tu voz a grave o aguda en tiempo real usando el micrófono (Web Audio API vía Tone.js).

## Uso local
Abre `index.html` en un navegador (Chrome/Edge/Firefox), da permiso de micrófono, y usa los botones o el slider.

## Deploy en Vercel

**Opción 1 — CLI:**
```
npm i -g vercel
cd voice-modulator
vercel
```

**Opción 2 — Dashboard:**
1. Sube esta carpeta a un repo de GitHub.
2. En vercel.com → "Add New Project" → importa el repo.
3. Framework preset: "Other". No requiere build command.
4. Deploy.

Nota: el micrófono requiere HTTPS (Vercel lo da por defecto) o `localhost`.
