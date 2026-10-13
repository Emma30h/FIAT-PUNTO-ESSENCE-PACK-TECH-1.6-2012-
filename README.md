# FIAT-PUNTO-ESSENCE-PACK-TECH-1.6-2012-

Página interactiva para vender un Fiat Punto Essence Pack Tech 1.6 16V 2012 (Córdoba Capital).

El comprador puede:

- **Exterior:** arrastrar la foto para rodear el auto por 6 ángulos.
- **Interior:** recorrer puesto de manejo, butacas, habitáculo y asiento trasero.
- **Detalles:** ver motor, equipo de GNC y auxilio.
- **Puntos interactivos:** tocar los puntos ámbar para ver el detalle real (kilometraje, techo solar, GNC, llantas, etc.).
- **Contacto:** escribir por WhatsApp desde la misma página.

Es HTML, CSS y JavaScript puro, sin dependencias ni paso de compilación. Funciona en celular, tablet y computadora.

## Estructura

```
index.html   La página completa (estilos y script incluidos)
img/         Fotos del auto, con corrección de luz y color
```

## Verlo en tu computadora

Abrí `index.html` en el navegador.

## Publicarlo con GitHub Pages

1. En el repositorio, entrá a **Settings → Pages**.
2. En **Source** elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. Guardá. En un par de minutos queda online en
   `https://emma30h.github.io/FIAT-PUNTO-ESSENCE-PACK-TECH-1.6-2012-/`

## Cambiar fotos o textos

- Las fotos se definen en el objeto `MODES` dentro del `<script>` de `index.html`. Cada vista tiene su imagen, su tamaño y sus puntos (`hs`: posición x/y en % y la clave del detalle).
- Los textos de cada punto están en el objeto `D`.
- El número de WhatsApp aparece en la sección de contacto y en el botón "Copiar número".
