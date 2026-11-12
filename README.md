# PLLF · Datos para la conservación marina

**Del dato disperso a la evidencia útil para decidir.**

Proyecto de Derian Palma Quirós orientado al desarrollo de servicios de análisis y asesoría basados en datos para la conservación marina y la gestión de especies invasoras. El pez león es el primer caso de aplicación.

> **Estado: prototipo en desarrollo · Versión documental 0.1 · 12 de noviembre de 2026.**
> La propuesta comercial todavía no está validada. El trabajo publicado documenta el aprendizaje, las decisiones y los resultados obtenidos.

## El problema

La información útil para estudiar una especie puede encontrarse en bases de biodiversidad, registros de observaciones, estadísticas pesqueras, publicaciones y archivos de organizaciones. Cada fuente tiene una estructura, cobertura y finalidad distintas. Encontrar datos no basta: hay que determinar qué preguntas permiten responder y con qué limitaciones.

## La propuesta

PLLF busca transformar esa información en entregas trazables: datos preparados, indicadores, visualizaciones y diagnósticos de carencias. La evolución hacia **Data as a Service (DaaS)** dependerá de validar necesidades recurrentes, condiciones de reutilización y disposición a pagar.

El procedimiento se diseña para adaptarse a distintas especies y territorios. Ninguna fuente es obligatoria: se consulta un catálogo común y se selecciona la información pertinente para cada caso.

## Caso piloto: pez león

La primera implementación utiliza una descarga de USGS NAS correspondiente a *Pterois volitans/miles*. Permite comenzar por la cobertura temporal y territorial de los registros y su calidad. La dimensión económica se abordará con fuentes específicas cuando exista información suficiente.

**Los registros de presencia no equivalen a abundancia, y un vacío de registros no demuestra ausencia de la especie.**

## Avances y próximos resultados

| Etapa | Estado | Evidencia o resultado esperado |
|---|---|---|
| Propuesta y alcance | Primera versión redactada | Usuarios, entregables e hipótesis explícitas |
| Catálogo de fuentes | Seis candidatas delimitadas | Revisión operativa pendiente en varias fuentes |
| Diagnóstico NAS | Cuaderno generado y ejecución confirmada por el autor | Inspección de estructura, nulos y categorías |
| Preparación e indicadores | Pendiente | Validaciones, tabla territorial y gráficos |
| Evidencia comercial | Pendiente | Fuente específica o carencias documentadas |
| Validación con usuarios | Pendiente | Contraste de utilidad y necesidades |

## Explorar el repositorio

1. [Servicio y alcance](docs/01_servicio_y_alcance.md)
2. [Catálogo inicial de fuentes](docs/02_catalogo_fuentes.md)
3. [Metodología](docs/03_metodologia.md)
4. [Caso del pez león](casos/pez_leon/README.md)
5. [Cuadernos del caso](casos/pez_leon/notebooks/README.md)
6. [Resultados y limitaciones](casos/pez_leon/resultados/README.md)
7. [Decisiones y pendientes](docs/04_decisiones_y_pendientes.md)
8. [Procedencia y gestión de datos](data/README.md)

## Reproducibilidad

Los cuadernos se trabajan en Google Colab. Cada análisis debe identificar la descarga utilizada, su fecha, los filtros aplicados y las transformaciones realizadas. Los archivos originales se conservan separados de los datos preparados.

## Autor y contexto

**Derian Palma Quirós** · Ingeniería mecatrónica y análisis de datos.

Este proyecto conecta con mi experiencia previa en monitoreo de pez león mediante ROV y visión artificial, y con mi formación en análisis de datos. El Sprint 08 de Pandas sirve como referencia metodológica para la fase inicial de preparación y exploración.

[Perfil de GitHub](https://github.com/dpalma1996) · [Repositorio PLLF](https://github.com/dpalma1996/PLLF)

## Atribución y reutilización

Los datos de terceros conservan sus condiciones originales. La publicación de este repositorio no concede derechos adicionales sobre ellos. Cada entrega deberá identificar las fuentes y verificar las condiciones aplicables antes de redistribuir datos o incorporarlos a un servicio comercial. La licencia del código y de la documentación propia queda pendiente de elección.
