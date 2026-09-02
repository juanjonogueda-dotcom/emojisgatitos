# Colección de Gatitos

Una pequeña colección web de gatitos hechos con kaomoji, ASCII, braille y emoji.
Cada pieza se puede copiar con un clic, ampliar con doble clic y explorar sin
dependencias ni proceso de compilación.

## Uso local

Abre `index.html` directamente en el navegador o levanta un servidor estático:

```bash
python3 -m http.server 8000
```

Después visita `http://localhost:8000`.

## Interacciones

- **Clic** en un gatito para copiarlo.
- **Doble clic** o **Espacio** para ampliarlo.
- **Enter** sobre una tarjeta enfocada para copiarla.
- **Esc** para cerrar la vista ampliada.
- El botón **generar un gatito** crea combinaciones nuevas.

La interfaz respeta `prefers-reduced-motion` para quienes prefieren reducir las
animaciones.
