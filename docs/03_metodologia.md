# Metodología de trabajo

[Volver a la portada](../README.md)

## 1. Definir la decisión y las preguntas

Identificar al usuario, la decisión que necesita tomar y el resultado esperado. Delimitar especie, territorio, periodo y variables. Cada pregunta debe tener una entrega concreta y condiciones para reconocer que los datos no bastan.

## 2. Consultar el catálogo

Revisar las fuentes existentes antes de iniciar búsquedas adicionales. Evaluar pertinencia, cobertura, granularidad, acceso y reutilización. Documentar las fuentes utilizadas, complementarias y descartadas para el caso.

**Criterio de salida:** contar con una extracción utilizable para la primera pregunta o documentar el impedimento y una alternativa. No esperar a reunir todos los datos existentes.

## 3. Documentar la extracción

Registrar fuente y proveedor original, URL, fecha, filtros, versión si existe, archivo, licencia o condiciones conocidas y huella SHA-256 cuando sea posible. Distinguir la fecha de descarga de la fecha del registro.

## 4. Diagnosticar sin modificar

Inspeccionar cabecera, dimensiones, tipos, nulos, categorías, identificadores y duplicados. Determinar qué representa cada fila. Leer los metadatos necesarios para interpretar las variables.

## 5. Preparar con trazabilidad

Trabajar sobre una copia. Conservar valores originales y registrar transformaciones. No imputar fechas o ubicaciones sin fundamento. Distinguir valores ausentes de ceros y registros inválidos de registros incompletos pero útiles.

Para datos de presencia, validar coordenadas dentro de rango no equivale a verificar su ubicación real. La precisión declarada por el proveedor tampoco debe convertirse automáticamente en metros.

## 6. Analizar a una escala compatible

Calcular indicadores con denominadores explícitos. No tratar datos anuales como observaciones mensuales ni sumar registros de fuentes potencialmente duplicadas sin revisar su procedencia. Mantener separados datos observados, estimados y derivados.

## 7. Comunicar y exportar

Entregar tablas, figuras y una interpretación ligada a las preguntas. Incluir limitaciones, carencias y próximos datos necesarios. Indicar qué resultados están ejecutados y cuáles son propuestas.

## 8. Cerrar la versión

Una versión se cierra cuando las preguntas acordadas tienen respuesta reproducible o una carencia documentada. Las ampliaciones se registran en pendientes. El catálogo y el procedimiento se mejoran con los casos, sin reiniciar el proyecto.

## Qué se generaliza

Se reutilizan el catálogo, la documentación de procedencia, los patrones de diagnóstico, las validaciones pertinentes al tipo de dato y la estructura de entrega. Se adaptan la lectura del formato, los nombres de columnas, la interpretación de categorías y las reglas del dominio.

## Evidencia científica y contexto experto

La primera versión utiliza antecedentes seleccionados para orientar el análisis; no pretende una revisión sistemática. Se separan hechos respaldados, interpretaciones y supuestos. El conocimiento experto ayuda a formular preguntas, pero no sustituye la comprobación de datos.
