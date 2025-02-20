## 1. ¿Cuál es el propósito de CSS?
CSS (Cascading Style Sheets) es un lenguaje que se utiliza para dar estilo y diseño a las páginas web. Controla aspectos como colores, fuentes, márgenes, posicionamiento y disposición visual, separando el contenido (HTML) de la presentación.

---

## 2. ¿Qué analogía NO técnica usarías para explicar la responsabilidad de HTML vs. CSS?
HTML es como el esqueleto de una casa, proporcionando la estructura básica (paredes, habitaciones, puertas), mientras que CSS es como la decoración y pintura, encargándose de cómo se ve la casa (colores, muebles, diseño).

---

## 3. ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
1. **CSS en línea**: Directamente en el atributo `style` de un elemento HTML.
   ```
   <p style="color: red;">Texto en rojo</p>
2. **CSS interno**: Dentro de una etiqueta `<style>` en el `<head>` del archivo HTML.
    ```
    <head>
        ...
        <style>
            p {
                color: red;
            }
        </style>
    </head>
3. **CSS externo**: En un archivo separado con la extension `.css` enlazado en una etiqueta `<link>` en el archivo html.
    
    ```
    HtML:
        
    <link rel="stylesheet" href="styles.css">
    
    CSS:

    p {
        color: red;
    }

Escribe un ejemplo de una regla CSS que daria texto rojo a todos los elementos de `<p>`.
```
CSS:
p {
    color: Red
}
