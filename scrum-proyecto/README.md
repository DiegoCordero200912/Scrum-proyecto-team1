# Tienda de la Cafetería — Proyecto Scrum

Actividad de la clase de **Métricas de Software**. Simulan un equipo Scrum que construye una página web sencilla (HTML + CSS + JavaScript, **sin frameworks ni servidor**) para que la cafetería de la escuela venda sus productos en línea.

Para abrir el proyecto basta con abrir `index.html` en el navegador.

---

## Equipo y roles (3 personas)

| Rol | Qué hace |
|---|---|
| **Product Owner** | Es dueño del Backlog. Decide la prioridad, aclara dudas de las tareas y acepta (o rechaza) lo terminado en la Sprint Review. |
| **Scrum Master** | Cuida que se siga el proceso: dirige el Daily Scrum, quita obstáculos y mantiene actualizada la plantilla de Excel. |
| **Scrum Team** | Desarrolla las tareas. *Con solo 3 personas, el PO y el SM también programan tareas*, pero cada quien cuida su rol. |

---

## Reglas de la actividad

- Duración: **3 días = 3 sprints de 1 día**.
- Cada sprint tiene su lista de tareas en [`BACKLOG.md`](BACKLOG.md).
- **Una tarea = una rama + un Pull Request** (o al menos un commit con el ID de la tarea, por ejemplo `T05: botón agregar al carrito`).
- Una tarea está **Terminada** solo si cumple su criterio de aceptación y la **Definición de Hecho** (abajo).
- Si no terminan algo en el sprint, pasa al siguiente sprint (se cuenta como *no cumplida* en el sprint original).

### Definición de Hecho (Definition of Done)
- [ ] Funciona al abrir `index.html` sin errores en la consola.
- [ ] Cumple el criterio de aceptación de la tarea.
- [ ] El código está subido al repo con el ID de la tarea en el commit.
- [ ] El Product Owner la revisó y la aceptó.

---

## Ceremonias de cada día

| Momento | Ceremonia | Qué hacer | Tiempo sugerido |
|---|---|---|---|
| Inicio del día | **Sprint Planning** | El PO presenta las tareas del sprint, el equipo las revisa y las anota en el Excel (hoja *Backlog*) con fecha y hora de solicitud. | 10 min |
| Durante el día | **Daily Scrum** | Cada quien responde: ¿qué hice?, ¿qué haré?, ¿qué me bloquea? El SM actualiza el Excel. | 5 min (mínimo 1 vez) |
| Fin del día | **Sprint Review** | Se demuestra lo terminado al PO, que lo acepta o no. | 10 min |
| Fin del día | **Retrospective** | ¿Qué salió bien?, ¿qué mejorar?, ¿qué probamos mañana? Anótenlo en `RETROSPECTIVA.md`. | 10 min |

---

## Métricas (plantilla de Excel)

Guarden la plantilla `Plantilla_Metricas_Scrum.xlsx` en la carpeta `metricas/` del repo y llénenla **mientras trabajan**, no al final:

- Al planear: ID, tarea, puntos, sprint y fecha/hora de solicitud.
- Al empezar una tarea: estado *En proceso* y hora de inicio.
- Al terminarla: estado *Terminada* y hora de fin.

La plantilla calcula sola la velocidad, el cumplimiento del sprint, el burndown, el lead time y el cycle time.

---

## Estructura del repo

```
├── index.html          # Página principal (la completan ustedes)
├── css/styles.css      # Estilos (los hacen ustedes)
├── js/data.js          # Productos de la cafetería (ya viene hecho)
├── js/app.js           # Lógica de la tienda (la hacen ustedes)
├── metricas/           # Aquí va el Excel
├── BACKLOG.md          # Tareas por sprint
├── BACKLOG.csv         # Las mismas tareas, para pegar en el Excel
└── RETROSPECTIVA.md    # Notas de las retrospectivas
```

## Entrega
Al terminar el Día 3: repo con el código, el Excel de métricas lleno y `RETROSPECTIVA.md` con las 3 retrospectivas.
