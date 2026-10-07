# Product Backlog

Puntos = esfuerzo relativo (1 = muy fácil, 3 = medio, 5 = difícil). El Product Owner puede cambiar el orden dentro del sprint, pero **no** mover tareas entre sprints sin avisar al equipo.

## Sprint 1 (Día 1) — Base de la tienda · 12 puntos

| ID | Tarea | Puntos | Criterio de aceptación |
|---|---|---|---|
| T01 | Estructura HTML de la página | 2 | Hay `header` (título), `main` (catálogo y carrito) y `footer`. |
| T02 | Estilos básicos | 2 | Tipografía, colores y espaciados definidos en `styles.css`; la página se ve ordenada. |
| T03 | Mostrar el catálogo desde el arreglo `productos` | 3 | Los 8 productos de `data.js` aparecen en pantalla generados con JavaScript (no escritos a mano en el HTML). |
| T04 | Tarjeta de producto | 2 | Cada producto muestra emoji, nombre, categoría y precio en formato `$25.00`. |
| T05 | Botón "Agregar al carrito" | 3 | Al hacer clic, el producto se guarda en un arreglo `carrito` (se ve con `console.log`). |

## Sprint 2 (Día 2) — Carrito de compras · 13 puntos

| ID | Tarea | Puntos | Criterio de aceptación |
|---|---|---|---|
| T06 | Mostrar el carrito en pantalla | 3 | Lista cada producto agregado con su cantidad; si agregas el mismo producto dos veces, sube la cantidad. |
| T07 | Calcular el total | 2 | Se muestra el total a pagar y se actualiza solo. |
| T08 | Quitar producto y vaciar carrito | 3 | Botón para quitar uno y botón "Vaciar carrito". |
| T09 | Contador en el encabezado | 2 | El header muestra "Carrito (N)" con el número de artículos. |
| T10 | Diseño responsivo | 3 | Se ve bien en pantalla de celular (probar con el modo móvil del navegador). |

## Sprint 3 (Día 3) — Pulido y pedido · 13 puntos

| ID | Tarea | Puntos | Criterio de aceptación |
|---|---|---|---|
| T11 | Filtro por categoría | 3 | Botones (Todos, Comida, Bebidas, Snacks) que filtran el catálogo. |
| T12 | Buscador por nombre | 3 | Una caja de texto filtra los productos mientras se escribe. |
| T13 | Guardar el carrito (`localStorage`) | 3 | Al recargar la página, el carrito sigue igual. |
| T14 | Formulario de pedido | 3 | Pide nombre y valida que no esté vacío; al confirmar muestra un mensaje con el resumen y vacía el carrito. |
| T15 | Documentar | 1 | El README incluye una captura de pantalla y cómo abrir el proyecto. |

---

**Total: 15 tareas · 38 puntos.**

> Product Owner: si un equipo termina todo antes de tiempo, puede proponer una tarea extra y agregarla al Backlog (con puntos y sprint), por ejemplo "modo oscuro" (2 puntos) o "botón de pedido por WhatsApp" (3 puntos).
