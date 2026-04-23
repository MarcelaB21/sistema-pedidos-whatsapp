# Sistema de Pedidos vía WhatsApp 

Este proyecto es una aplicación web interactiva diseñada para la visualización de productos y la gestión de pedidos de forma simplificada a través de WhatsApp.

> **Nota:** Este repositorio corresponde a una **versión demo** del proyecto.  
> Está basado en un caso de uso real, pero todos los datos visibles (nombre comercial, precios, contactos y contenido) han sido modificados o anonimizados.  
> No se utilizan datos reales ni corresponde a un sistema en producción.

---
## Problema resuelto

Este software fue desarrollado para optimizar el proceso de toma de pedidos de un negocio local, que anteriormente se realizaba de forma manual mediante mensajería.

La solución permitió organizar productos en un catálogo digital, automatizar cálculos de cantidades y subtotales, y generar solicitudes listas para enviar por WhatsApp.

Con ello, se redujo el tiempo de atención, se mejoró la organización del proceso y se minimizaron errores en los pedidos.

---
## Funcionalidades

- Catálogo dinámico de productos cargados desde un archivo JSON
- Gestión de carrito por peso (libra) o unidades con cálculo automático de subtotales
- Generación automática del mensaje de pedido mediante enlace `wa.me`
- Interfaz completamente responsiva, optimizada para dispositivos móviles
- Validaciones en tiempo real y confirmaciones mediante modales personalizados

---

## Tecnologías

| | | |
| :---: | :---: | :---: |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) | ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) | ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) |

---

## Proyecto en vivo

[Ver sitio web](https://avicola-yenner.netlify.app/)


---

## Estructura del proyecto

- `/index.html` — Estructura principal de la aplicación  
- `/css/style.css` — Estilos, animaciones y diseño responsivo  
- `/js/main.js` — Lógica de renderizado, carrito e integración con WhatsApp  
- `/data/productos.json` — Base de datos de productos

---




