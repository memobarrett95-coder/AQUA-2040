# AQUA 2040 — archivos 3D

Coloca en esta carpeta estos dos archivos para activar el visor 3D y la realidad aumentada:

- `AQUA_2040.glb` — modelo 3D para navegador y Android/Scene Viewer.
- `AQUA_2040.usdz` — modelo para Apple Quick Look / realidad aumentada en iPhone y iPad.

Los nombres deben coincidir exactamente.

## Archivos originales de Meshy

Puedes renombrar tus archivos así:

- `Meshy_AI_Aqua_2040_0906002457_texture.glb` → `AQUA_2040.glb`
- `Meshy_AI_Aqua_2040_0906002657_texture.usdz` → `AQUA_2040.usdz`

Después de subirlos a esta carpeta, GitHub Pages los servirá desde `/assets/` y el componente `model-viewer` de la página podrá cargarlos.

> Nota: los archivos 3D de alta resolución pueden superar los límites prácticos de una carga normal de GitHub. Si GitHub rechaza el archivo por tamaño, conviene publicar una versión optimizada del GLB y utilizar Git LFS o un CDN para el archivo pesado.
