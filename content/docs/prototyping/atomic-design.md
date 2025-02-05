---
weight: 700
title: "Atomic Design"
description: "Atomic Design es una metodología para crear sistemas de diseño escalables y modulares. Esta metodología desglosa las interfaces en cinco niveles distintos: Átomos, Moléculas, Organismos, Plantillas, Páginas."
aliases:
    - ../guides/prototyping/atomic-design
author: "Angelo Ortiz Vega"
icon: "search"
date: "2025-02-01T18:38:29-06:00"
lastmod: "2025-02-01T18:38:29-06:00"
draft: false
toc: true
images: []
---

![atomic-design-cover](https://res.cloudinary.com/dek4evg4t/image/upload/v1738735439/ux-arc/atomic-design-intro.png)


## ¿Qué es Atomic Design?

Atomic Design es una metodología para crear sistemas de diseño escalables y modulares. Esta metodología desglosa las interfaces en cinco niveles distintos: Átomos, Moléculas, Organismos, Plantillas, Páginas.

Cada nivel contribuye a la creación de interfaces coherentes y reutilizables, facilitando el desarrollo y mantenimiento de productos digitales.

## Niveles del Atomic Design

### Átomos

Los átomos son los bloques fundamentales de cualquier sistema de diseño. En el contexto de interfaces web, los átomos incluyen:

- Etiquetas de formulario (label)
- Campos de entrada (input)
- Botones (button)
- Paletas de colores
- Tipografías
- Animaciones

Estos elementos, aunque básicos por sí solos, sirven como referencia para establecer estilos globales dentro de una biblioteca de diseño.

![atomic-design-cover](https://bradfrost.com/wp-content/uploads/2013/06/atoms.jpg)

Referencia de la imagen: https://bradfrost.com/blog/post/atomic-web-design/


### Moléculas

Las moléculas surgen de la combinación de átomos, formando pequeños componentes funcionales. Algunos ejemplos son:

- Un campo de búsqueda (etiqueta + campo de entrada + botón de envío)
- Un botón con icono y texto
- Este nivel permite reutilizar elementos y promueve el principio de "hacer una cosa y hacerla bien".


![atomic-design-cover](https://bradfrost.com/wp-content/uploads/2013/06/molecule.jpg)

Referencia de la imagen: https://bradfrost.com/blog/post/atomic-web-design/

### Organismos

Los organismos combinan varias moléculas para formar secciones más complejas de la interfaz, como:

- Un encabezado con logo, menú de navegación y barra de búsqueda
- Un grid de productos con imágenes, títulos y precios

Aquí, el diseño empieza a tomar forma y se vuelve visualmente significativo para los usuarios y clientes.


![atomic-design-cover](https://bradfrost.com/wp-content/uploads/2013/06/organism2.jpg)

Referencia de la imagen: https://bradfrost.com/blog/post/atomic-web-design/


### Plantillas

Las plantillas organizan organismos en estructuras definidas, estableciendo la disposición de los elementos en una página sin enfocarse en contenido específico. Se utilizan como:

- Wireframes en HTML
- Bases para la composición visual del diseño

![atomic-design-cover](https://bradfrost.com/wp-content/uploads/2013/06/template1.jpg)

Referencia de la imagen: https://bradfrost.com/blog/post/atomic-web-design/


### Páginas

Las páginas son instancias específicas de una plantilla con contenido real. En este nivel, se pueden probar variaciones y evaluar la efectividad del diseño. Ejemplos incluyen:

- Un carrito de compras con un solo producto vs. con múltiples productos y descuentos aplicados
- Un encabezado con títulos de diferente longitud

Este es el nivel donde se realizan pruebas finales y ajustes basados en el contexto real del usuario.

![atomic-design-cover](https://bradfrost.com/wp-content/uploads/2013/06/page1.jpg)

Referencia de la imagen: https://bradfrost.com/blog/post/atomic-web-design/

## ¿Por qué usar Atomic Design?

- Atomic Design ofrece un enfoque estructurado para el diseño de interfaces:
- Promueve la consistencia en el diseño de productos digitales.
- Facilita la escalabilidad, permitiendo agregar o modificar componentes sin afectar toda la interfaz.
- Optimiza la colaboración entre diseñadores y desarrolladores.
- Permite iteraciones rápidas, facilitando la prueba y mejora de componentes individuales antes de su implementación global.

Atomic Design no solo mejora la organización y la reutilización de elementos, sino que también garantiza que cada componente se construya con una función específica y clara en mente, optimizando la experiencia del usuario y la eficiencia del desarrollo.