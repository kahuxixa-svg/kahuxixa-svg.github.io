# Fotos del portafolio

Coloca aquí tus fotos y aparecerán AUTOMÁTICAMENTE en la página (si un archivo
no existe, su espacio se oculta solo — no queda ningún hueco roto).

| Carpeta | Qué poner | Archivos que busca la página |
|---|---|---|
| `robuz/` | Fotos de tu robot (el vehículo, el brazo, la electrónica, en acción) | `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg` |
| `mediall/` | Capturas de pantalla de la app Mediall | `1.jpg`, `2.jpg`, `3.jpg` |
| `hukazeos/` | Capturas de HuKazeos OS (app o panel) | `1.jpg`, `2.jpg`, `3.jpg` |

Consejos:
- Usa JPG (o renombra tus PNG a .jpg… mejor: convierte). Tamaño ideal ~1200px de ancho.
- Para capturas del teléfono: `adb exec-out screencap -p > captura.png` con el
  teléfono conectado, o comparte las capturas por WhatsApp/Drive y guárdalas aquí.

Después de agregar fotos:
```bash
cd ~/Documentos/hxas-portfolio
git add -A && git commit -m "Fotos" && git push
```
(La página se actualiza sola en ~1 minuto.)
