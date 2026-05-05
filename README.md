![Portada](images/portada.png)

# Policy Brief Interactivo de Indicadores Mineros – Provincia de San Juan

Aplicación HTML interactiva con enfoque mixto: análisis económico-financiero, impacto territorial y agenda de política pública para el sector minero de San Juan.

## Objetivo

El tablero está diseñado para apoyar la lectura ejecutiva de indicadores económicos y estadístico-financieros vinculados al sector minero sanjuanino. Integra información pública de la Secretaría de Minería de la Nación, CAEM y el visor oficial de empleo minero en Tableau.

## Características

- Narrativa tipo informe ejecutivo / policy brief.
- Botón para exportar o guardar en PDF desde el navegador.
- Selector de idioma ES / EN.
- KPIs ejecutivos.
- Gráficos con Chart.js.
- Carga de archivos Excel/CSV con selección de hoja, variables, períodos y tipo de gráfico.
- Visor oficial de empleo minero embebido desde Tableau.
- Créditos profesionales y nota de uso de IA.

## Cómo exportar PDF

1. Abrir `index.html` en el navegador.
2. Presionar **Exportar / Guardar PDF**.
3. En destino, elegir **Guardar como PDF**.
4. Ajustar escala si fuera necesario.
5. Guardar.

## Fuentes principales

1. Secretaría de Minería de la Nación – Compendio Estadístico de la Actividad Minera, segundo semestre 2025.  
   https://www.argentina.gob.ar/sites/default/files/compendio_estadistico_actividad_minera_2do_semestre_2025.pdf

2. CAEM – Reporte mensual de datos y análisis del sector minero, agosto 2025.  
   https://caem.com.ar/storage/2025/11/202508-reporte-mensual-de-datos-y-analisis-del-sector-minero-caem.pdf

3. Secretaría de Minería de la Nación – Mercado de Cobre 2026.  
   https://www.argentina.gob.ar/sites/default/files/mercado_de_cobre_2026_0.pdf

4. Secretaría de Minería de la Nación – Visor público Tableau de Empleo Minero.  
   https://public.tableau.com/app/profile/sec.mineria/viz/EmpleoMinero/EmpleoRubro

## Archivos del repositorio

```text
/
├── index.html
└── README.md
```

Se recomienda renombrar el archivo HTML como `index.html` para publicarlo directamente con GitHub Pages.

## Uso del módulo Excel/CSV

El tablero permite cargar archivos `.xlsx`, `.xls` o `.csv`.

Pasos:

1. Seleccionar archivo.
2. Elegir la hoja del Excel.
3. Seleccionar el eje X.
4. Seleccionar una o varias variables Y.
5. Elegir un campo de período, si corresponde.
6. Seleccionar uno, varios o todos los períodos.
7. Elegir tipo de gráfico: barras, línea o torta.
8. Presionar **Graficar**.

También incluye una plantilla CSV descargable desde el propio dashboard.

## Estructura sugerida para archivos de datos

```csv
periodo,provincia,indicador_exportaciones,empleo_directo,inversion_usd_millones,unidad,fuente
2025-06,San Juan,100,12000,33000,índice/físico/monetario,Fuente propia
2025-07,San Juan,120,12150,33000,índice/físico/monetario,Fuente propia
2025-08,San Juan,135,12300,33000,índice/físico/monetario,Fuente propia
```

## Librerías utilizadas

El dashboard utiliza librerías cargadas desde CDN:

- Chart.js para gráficos.
- SheetJS/XLSX para lectura de archivos Excel y CSV.

Para usar el módulo de gráficos dinámicos y el visor Tableau es recomendable contar con conexión a internet.

## Notas metodológicas

Los datos precargados son una base ejecutiva de referencia. Para uso institucional se recomienda validar:

- Fecha de corte.
- Cobertura geográfica.
- Unidad de medida.
- Periodicidad.
- Fuente primaria.
- Responsable del dato.
- Definiciones estadísticas utilizadas.

## Licencia sugerida
Uso demostrativo, institucional y educativo. Antes de reutilizar o publicar resultados oficiales, validar los datos con las fuentes primarias correspondientes.

## Créditos

Diseñado por **Silvana Sánchez Di Domenico**.  
GitHub: https://github.com/ssanchezdd7

Este dashboard fue desarrollado con apoyo de herramientas de inteligencia artificial (ChatGPT - OpenAI) para generación de código, estructuración analítica, diseño UX/UI, integración de visualizaciones, procesamiento de datos y documentación técnica. La interpretación y validación final corresponden al criterio experto de la autora.

