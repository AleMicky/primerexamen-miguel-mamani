# primerexamen-miguel-mamani

## Miguel Alejandro Mamani Viilegas

## Segundo Semestre

## Paralelo A

## Primer Examen

## Desarrollo de pagina web Mamaco


##  Accesibilidad (a11y)

1. **Skip Link**  
   - Un enlace invisible al inicio (`Saltar al contenido principal`) que permite a usuarios de teclado y lectores de pantalla ir directo al `<main>`.

2. **Foco visible**  
   - Estilos para que `a` y `button` muestren un borde destacado (`outline`) al recibir foco vía teclado.

3. **Alternativa para imágenes**  
   - En lugar de `<img>`, se usan `<div class="thumb">` como placeholders.  
   - Cada uno lleva `role="img"` y un `aria-label` descriptivo para que los lectores de pantalla entiendan el contenido.

4. **Uso prudente de `aria-*`**  
   - Se utilizó solo cuando fue necesario:  
     - `aria-label` en el link de marca “MANACO”.  
     - `role="img"` y `aria-label` en los placeholders `.thumb`.

5. **Jerarquía oculta para navegación**  
   - Se usaron encabezados secundarios (`h2` con clase `sr-only`) para identificar la navegación y encabezado principal sin añadir ruido visual.
