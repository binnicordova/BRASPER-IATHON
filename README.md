# BRASPER-IATHON

Repositorio paraguas del equipo **5.5** para IATHON Perú 2026. No duplica código: cada carpeta es un **submódulo** que apunta al repositorio público donde vive esa pieza.

> BRASPER: de un chat de WhatsApp a una operación de cambio PIX ⇄ PEN con seguimiento.

## Piezas

| Carpeta | Qué es | Repositorio |
|---|---|---|
| [`app/`](app) | App Expo (iOS, Android, web), asistente de IA con LangGraph + Gemma, Cloud Functions y reglas de Firebase (`aibrasper`) | [binnicordova/iathon-fintech](https://github.com/binnicordova/iathon-fintech) |
| [`web/`](web) | Sitio web y portal de transferencias sobre las Cloud Functions de BRASPER (Lovable) | [jordyalania/brasper-global-connect](https://github.com/jordyalania/brasper-global-connect) |
| [`backoffice/`](backoffice) | Backoffice (VIEW) para validar, exportar y revisar las operaciones | [Melani232000/the-view](https://github.com/Melani232000/the-view) |
| [`whatsapp-agent/`](whatsapp-agent) | Agente de WhatsApp de BRASPER | [davidrodriguez2712/iaton-proyecto](https://github.com/davidrodriguez2712/iaton-proyecto) |

## Clonar todo

```bash
git clone --recurse-submodules https://github.com/binnicordova/BRASPER-IATHON.git
```

Si ya clonaste sin submódulos:

```bash
git submodule update --init --recursive
```

## Actualizar al último commit de cada repo

```bash
git submodule update --remote
git add -A && git commit -m "chore: update submodules"
```

Este repositorio guarda un commit fijo de cada pieza; las carpetas no cambian solas cuando alguien hace push en los repos originales.

## Licencia

Ver [license](license). Cada submódulo conserva la suya.
