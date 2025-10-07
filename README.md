# Dashboard de Gestión de Talento (Talent Management Dashboard)

Este proyecto implementa un **Dashboard interactivo** utilizando **Dash** y **Plotly** para el análisis y la gestión de datos de empleados. Permite a los usuarios filtrar perfiles, visualizar la distribución demográfica, analizar la correlación entre variables clave (como nivel de pago y experiencia) y generar reportes tabulares de diversidad y rotación.

## Características Principales

* **Buscador de Perfiles (Filtros):** Permite filtrar la base de datos de empleados por **Ciudad**, **Género**, **Nivel Educativo** y **Rango de Edad**.
* **Tabla de Perfiles Filtrados:** Muestra los perfiles que cumplen con los criterios de búsqueda, ideal para la asignación de proyectos.
* **Panel de Análisis y Correlación:**
    * **Distribución Demográfica:** Gráfico de barras que muestra la distribución de género por ciudad.
    * **Correlación Pago-Experiencia:** Heatmap que visualiza la frecuencia de empleados según su Nivel de Pago (`PaymentTier`) y su Experiencia en el Dominio Actual.
    * **Riesgo de Abandono:** Boxplot que compara la `ExperienceInCurrentDomain` entre empleados con alto y bajo riesgo de abandono (`LeaveOrNot`).
    * **Historial 'Benched':** Gráfico que muestra la tendencia de empleados que han estado "benched" por año de ingreso.
* **Reportes Tabulares:** Genera tablas de resumen para **Diversidad (Educación y Género)** y **Rotación (Riesgo de Abandono por Ciudad)**.
* **Exportación de Reporte:** Incluye un botón para la futura funcionalidad de exportar un reporte completo.

## Requisitos y Dependencias

Para ejecutar esta aplicación, necesitas tener **Python 3.x** instalado.

### Instalación de Dependencias

Se requiere instalar las bibliotecas de **Pandas**, **Dash**, **Plotly** y sus dependencias.

```bash
pip install pandas plotly dash


