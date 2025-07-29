# Portafolio de Yuraima García

## Introducción
Este informe detalla los ajustes realizados al portafolio de Yuraima García, específicamente la implementación de estilos CSS mediante un archivo externo (`style.css`), siguiendo los requisitos establecidos en la evaluación del módulo 2. Se describen a continuación las clases aplicadas y su respectiva explicación.

## Estilos Aplicados

### Encabezado
```css
header {
    background-color: #6A0DAD; /* Morado */
    color: white;
    text-align: center;
    padding: 20px;
    border-bottom: 3px solid #333;
}
```
**Descripción**: Se aplica un fondo morado al encabezado, con texto blanco centrado. Además, se define un margen interno de 20 píxeles y un borde inferior de 3 píxeles, lo que proporciona un diseño distintivo y atractivo.

### Imagen del Encabezado
```css
header img {
    height: 200px;
    border-radius: 200px;
    border: 3px solid white;
    margin-top: 15px;
}
```
**Descripción**: Esta clase se asocia a la imagen del encabezado, dándole una altura de 200 píxeles, bordes redondeados y un borde blanco. Además, se añade un margen superior de 15 píxeles para separarla adecuadamente.

### Sección "Sobre mí"
```css
#sobre-mi {
    background-color: white;
    padding: 20px;
    margin: 20px;
    border-radius: 5px;
    box-shadow: 2px 5px rgba(0, 0, 0, 0.1);
}
```
**Descripción**: Aplica un fondo blanco a la sección "Sobre mí" con márgenes de 20 píxeles. El borde redondeado y la sombra suave ayudan a destacar esta sección, dándole un efecto de elevación.

### Datos de Interés
```css
.datos-interes {
    font-weight: bold;
    color: #555;
    background-color: #e6e6e6; /* Gris claro */
    padding: 10px;
    border-left: 4px solid #6A0DAD; /* Morado */
}
```
**Descripción**: Esta clase resalta un párrafo específico con un fondo gris claro, texto en negrita y un borde izquierdo morado. Este estilo añade énfasis a la información crucial.

### Lista de Habilidades
```css
#habilidades ul {
    list-style-type: square;
    padding-left: 25px;
}

#habilidades li {
    margin-bottom: 8px;
    color: #444;
}
```
**Descripción**: Los estilos aplicados a la lista de habilidades utilizan cuadraditos en lugar de puntos para los ítems. Además, se define un espaciado entre cada habilidad, mejorando la presentación visual.

### Efecto Hover en Enlaces de Contacto
```css
#contacto a:hover {
    text-decoration: underline;
}
```
**Descripción**: Se establece un efecto hover que añade una subrayado a los enlaces de contacto al pasar el ratón sobre ellos, mejorando la experiencia del usuario.

## Dificultades y Aprendizajes
- **Facilidades**: La estructuración de estilos fue directa gracias a la claridad en el HTML y la lógica de los selectores CSS.
- **Dificultades**: Ajustar los estilos responsivos fue un desafío; sin embargo, esta experiencia proporcionó una comprensión más profunda de diseño web adaptable.
