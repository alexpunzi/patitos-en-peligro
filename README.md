# Patitos en Peligro

Proyecto universitario — Escape Room sobre cambio climático desarrollado en la Universidad de Alicante (Sistemas Multimedia, Grupo 41).

## Objetivo

Concienciar sobre el cambio climático mediante un formato lúdico y educativo, combinando misiones QR en el campus con una plataforma web que muestra ranking, mapa interactivo y ajustes personalizables.

## Estructura

- `/index.html`: Landing con hero, cómo funciona, adaptación por edad, testimonios y CTA.
- `/ranking.html`: Tabla de ranking con filtros (global, semanal, mensual, amigos) y stats del jugador.
- `/mapa.html`: Mapa de la UA con ubicaciones temáticas y leyenda.
- `/iniciarSesion.html`: Formulario de inicio de sesión con validación básica y notificaciones.
- `/agradecimientos.html`: Reconocimientos y equipo del proyecto.
- `/ajustes.html`: Panel de configuración (audio, gráficos, tema, juego y accesibilidad).
- `/css/common.css`: Variables, reset, temas y accesibilidad.
- `/css/layout.css`: Estructura, contenedores, header, footer, hero y grids.
- `/css/components.css`: Botones, tablas, formularios, notificaciones, switches, sliders, badges.
- `/css/pages.css`: Estilos específicos por página (steps, age groups, mapa, ajustes, equipo).

## Rutas y despliegue

- Rutas absolutas preparadas para GitHub Pages bajo `/patitos-en-peligro`.
- Favicon y assets como `patitologo1_circulo.png` y `uaLogo2.png` referenciados desde esa raíz.

## Accesibilidad y UX

- Uso de `aria-label`, `role`, estados `aria-selected` en filtros/tablists.
- Soporte de teclado en selección de temas.
- Modo alto contraste, texto grande y reducción de movimiento.
- Animaciones suaves con IntersectionObserver y fallback de reduce-motion.

## Notas

- Los datos de ranking y mapa son de ejemplo y se pueden conectar a APIs reales.
- El login simula un proceso con spinner y notificación; la autenticación real no está implementada.
