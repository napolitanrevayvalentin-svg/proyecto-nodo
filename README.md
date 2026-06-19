# Cooperativa Nodo - Sistema de Diseño y Prototipo Web

**Estudiante:** Valentin Napolitan Revay  
**Seminario:** Diseño Multimedial  

## Sobre el Proyecto
Este proyecto es la entrega final del seminario. Consiste en el diseño, documentación e implementación de un sistema de diseño modular aplicado a "Cooperativa Nodo", una organización autogestiva enfocada en el reciclaje de hardware (e-waste), la reducción de la brecha digital y la alfabetización tecnológica.

## Características Técnicas Implementadas
- **Mobile First & Diseño Adaptativo:** Estructura macro resuelta íntegramente con CSS Grid, escalando fluidamente desde un layout de 1 columna (mobile) hasta 3+ columnas (desktop).
- **CSS Custom Properties (Variables):** Sistema de *Design Tokens* (paleta brutalista, tipografía de consola y escala de espaciado) centralizado en `:root`.
- **Container Queries:** Microcomposición inteligente en las tarjetas de componentes (`.card-hardware`), alterando su layout interno en función del ancho de la columna padre mediante `container-type: inline-size`.
- **Documentación Integrada:** El propio sitio incluye la documentación visual y teórica del sistema (Etapa 4).

## Tecnologías Utilizadas
- HTML5 (Semántico)
- CSS3 (Puro, sin frameworks)

## Instalación y Despliegue
Al ser un sitio estático puro, no requiere dependencias. Simplemente clonar el repositorio y abrir `index.html` en cualquier navegador moderno.