# 🌐 Gemelo Digital de Inventarios — Agroferretería Sibarco

**Prototipo académico** para la representación, registro y análisis del proceso de inventarios.

##  Descripción

Este proyecto corresponde al desarrollo de un **gemelo digital del proceso de inventarios**
de la Agroferretería Sibarco, como parte de un proyecto de grado de ingeniería.

El sistema permite:

- Cargar información histórica real desde un archivo Excel (hoja `BASE_VENTAS`).
- Registrar entradas y salidas de productos mediante formularios.
- Calcular existencias y movimientos.
- Visualizar indicadores y gráficos de ventas.
- Ejecutar un **modelo bayesiano de demanda** (Poisson–Gamma).
- Exportar toda la información a Excel.

##  Tecnologías

- HTML5, CSS3, JavaScript (vanilla)
- [SheetJS](https://sheetjs.com/) — lectura/escritura de Excel
- [Chart.js](https://www.chartjs.org/) — gráficos
- `localStorage` — persistencia local
- **GitHub Pages** — hosting

> No utiliza backend, base de datos, ni servidores. Todo se procesa localmente en el navegador.

##  Cómo usarlo

1. Abre el enlace público del proyecto.
2. En el Dashboard, haz clic en **"Cargar archivo Excel"**.
3. Selecciona el archivo `.xlsx` con la hoja `BASE_VENTAS`.
4. Explora los módulos: Productos, Entradas, Salidas, Existencias, Movimientos, Ventas, Análisis, Demanda.
5. Registra entradas/salidas manualmente si lo necesitas.
6. Exporta los resultados.

##  Fuente de información

- **Datos históricos:** archivo Excel `BASE_VENTAS` de la Agroferretería Sibarco.
- **Datos operativos:** registros manuales introducidos en el prototipo.

##  Alcance y limitaciones

El presente desarrollo corresponde a un **prototipo académico de gemelo digital** orientado
a la representación, registro y análisis del flujo de entradas y salidas de inventario.
**No constituye un sistema ERP integral** ni reemplaza los procedimientos administrativos
y físicos de la empresa.

##  Autor

- **Nombre:** [Tu nombre]
- **Institución:** [Tu universidad]
- **Año:** 2025

## 🔗 Enlace publicado

👉 [Ver prototipo en vivo](https://tu-usuario.github.io/tu-repositorio/)
