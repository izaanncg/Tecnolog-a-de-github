# 🌟 Festival Juvenil Vila-real 2026

## Descripción del proyecto
Web informativa estática para el **Festival Juvenil Vila-real 2026**, un evento cultural y musical abierto al público joven de 14-25 años. La web presenta el evento de forma atractiva y responsive, con toda la información esencial: qué es, programa completo, ubicación y cómo participar.

**Objetivo**: Difundir el evento y facilitar la inscripción a talleres y conciertos gratuitos.

## 🎨 Secciones de la web y columnas Bootstrap usadas

| Sección | Estructura Bootstrap | Columnas usadas |
|---------|---------------------|-----------------|
| **Navbar** | `navbar-expand-lg navbar-dark bg-primary` | Logo + 4 enlaces (Hero, Programa, Ubicación, Contacto) |
| **Hero** | `jumbotron` con `container` + `row` centrada | `col-12` (título + botón CTA completo ancho) |
| **Programa** | `container` + `row` con 3 cards | `col-md-4` x 3 (3 días del festival) |
| **Ubicación** | `container` + `row` con mapa + info | `col-lg-8` (mapa) + `col-lg-4` (detalles) |
| **Footer** | `footer bg-dark text-white` | `col-12` (centrado, info completa) |

## 🛠️ Componentes Bootstrap utilizados
- **Navbar** responsive con toggle para móvil
- **Cards** para mostrar los 3 días del festival
- **Buttons** (primary, outline-secondary) para CTA
- **Grid system** completo (`container`, `row`, `col-*`)
- **Jumbotron** adaptado para Hero section
- **Responsive utilities** (`d-none d-md-block`, etc.)
