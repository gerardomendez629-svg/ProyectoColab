# SB Admin - Proyecto Colaborativo

Este repositorio contiene una versión reducida del panel de administración basado en la plantilla oficial de [SB Admin (Start Bootstrap)](https://startbootstrap.com/theme/sb-admin), conservando únicamente las secciones de **Dashboard** y **Tables**.

El proyecto fue desarrollado de forma colaborativa utilizando Git y GitHub, aplicando un flujo de trabajo ramificado para dividir responsabilidades entre las dos personas del equipo, cada compañero trabajando y subiendo sus cambios desde su propia cuenta de GitHub.

## Flujo de Trabajo en Git

Se establecieron las siguientes ramas:

- `main`: Rama de producción estable que contiene el código integrado y final.
- `developer1`: Rama de trabajo para el Dashboard.
- `developer2`: Rama de trabajo para las Tables.

### Ciclo de Integración

1. Cada colaborador trabajó y confirmó sus cambios en su respectiva rama (`developer1` / `developer2`) desde su propia cuenta de GitHub.
2. Se subieron los cambios a GitHub mediante `git push origin <rama>`.
3. Cada quien abrió su propio Pull Request desde su cuenta hacia `main`.
4. Se revisaron e integraron ambos Pull Requests mediante **Merge**.

## Estructura del Proyecto

```
SB-Admin/
├── assets/          Recursos gráficos e imágenes
├── css/             Hojas de estilo
├── js/              Scripts de interactividad y plugins
├── README.md        Documentación del proyecto
├── tables.html      Vista de Tablas
└── index.html       Vista del Dashboard