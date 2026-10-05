# motion

- **Carga:** titular entra línea por línea (1s), subrayado, lead y CTAs en stagger (.8–.95s), burger con fade + scale + translateY (1.3s).
- **Scroll:** reveal `.rv` con IntersectionObserver (opacity + translateY 26px, .9s).
- **Hover:** botones translateY(-3px) rotate(-1deg); flecha translateX(6px); tarjetas -6px y foto x1.05 (.5–.6s).
- Header reduce su tamaño al hacer scroll. Menú móvil con fade .4s.
- Solo `opacity` y `transform`. Sin rebotes ni glitch.
- `prefers-reduced-motion`: se anulan animaciones y transiciones.
