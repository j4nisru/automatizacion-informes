# Automatización Informe de Precios

## Objetivo

Automatizar completamente la generación del Informe de Precios mediante Python, reproduciendo los gráficos del PowerPoint con la mayor fidelidad posible.

## Flujo del proceso

1. Leer la base de datos.
2. Detectar automáticamente la fecha de cohorte.
3. Filtrar la información correspondiente.
4. Generar todos los gráficos.
5. Exportar los gráficos en PNG (300 dpi).
6. Guardarlos en la carpeta correspondiente a la cohorte.

## Estructura del proyecto

scripts/
- Código fuente.

datos/
- Base de datos de entrada.

ppt_modelo/
- PowerPoint utilizado como referencia visual.

output/
- Archivos generados automáticamente.

## Convenciones

- Reutilizar funciones existentes antes de crear nuevas.
- Mantener una arquitectura modular.
- Evitar duplicación de código.
- Centralizar estilos (colores, fuentes, tamaños) en un solo archivo.
- Priorizar código claro y mantenible.

## Criterios visuales

Los gráficos deben replicar la PPT respetando:

- colores
- tipografía
- tamaños
- ejes
- etiquetas
- leyendas
- márgenes
- resolución
- espaciados

La PPT es la referencia principal.

## Al realizar modificaciones

Antes de programar:

1. Analizar el proyecto completo.
2. Identificar funciones reutilizables.
3. Detectar dependencias.
4. Proponer un plan de implementación.

Luego:

- implementar los cambios;
- verificar que el código siga funcionando;
- no modificar funcionalidades existentes sin justificación.

## Objetivo final

Que el proceso mensual requiera únicamente actualizar la base de datos y ejecutar el script.
