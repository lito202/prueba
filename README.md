# Proyecto: Procesamiento de Imágenes con OpenCV

Este proyecto toma una imagen de un circuito, detecta bordes, engrosa las líneas y las convierte en líneas blancas sobre fondo negro. Utiliza OpenCV y operaciones morfológicas como dilatación y cierre.

## Flujo del programa
1. Leer la imagen en escala de grises.
2. Detectar bordes usando Canny.
3. Engrosar las líneas con dilatación.
4. Rellenar huecos con cierre morfológico.
5. Invertir colores para generar la salida final.

## Entrada y Salida
- **Entrada:** Imagen en escala de grises (`.jpg`, `.png`).
- **Salida:** Imagen procesada con fondo negro y líneas blancas.# prueba
