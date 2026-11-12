# Catálogo inicial de fuentes · v0.1

[Volver a la portada](../README.md)

## Finalidad y límite

Este catálogo es un punto de consulta reutilizable para distintos casos marinos. **No es una revisión exhaustiva ni una certificación de disponibilidad.** La versión inicial se limita a seis candidatas; se ampliará cuando una pregunta prioritaria necesite información que estas no cubran.

Fecha de elaboración: 12/11/2026. No se ha probado la descarga de todas las fuentes. Las funciones de las candidatas son orientaciones de selección; las condiciones de acceso y reutilización deben comprobarse para el conjunto concreto.

## Índice de consulta

| Fuente | Función prevista | Unidad que se debe comprobar | Estado en PLLF |
|---|---|---|---|
| [FishBase](https://www.fishbase.se/) | Caracterización de peces, usos y antecedentes | Especie o registro de una tabla temática | Ficha y exportaciones de nombres revisadas; selección de tablas pendiente |
| [WoRMS](https://www.marinespecies.org/) | Referencia taxonómica marina | Nombre o taxón | Candidata; acceso operativo pendiente |
| [OBIS](https://obis.org/) | Biodiversidad marina | Registro, evento o medición, según conjunto | Candidata; descarga pendiente |
| [GBIF](https://www.gbif.org/) | Localización de conjuntos y registros de biodiversidad | Registro, según conjunto y formato | Un conjunto de Barbados inspeccionado; integración general pendiente |
| [USGS NAS](https://nas.er.usgs.gov/) | Especies acuáticas no autóctonas y registros asociados | Registro NAS | Descarga de pez león inspeccionada y utilizada |
| [EASIN](https://easin.jrc.ec.europa.eu/) | Información sobre especies exóticas de interés europeo | Taxón o registro, según producto | Candidata; acceso operativo pendiente |

## Fichas breves

### FishBase

- **Interés:** información biológica, taxonómica, de distribución y usos de peces.
- **Cobertura a comprobar:** disponibilidad por especie y por tabla; la amplitud del portal no garantiza datos para cada variable.
- **Material revisado:** ficha de *Pterois volitans* y dos exportaciones de búsquedas por nombre común.
- **Acceso pendiente:** seleccionar una tabla temática y probar una extracción reproducible.
- **Limitación:** los nombres comunes son ambiguos; las estimaciones de modelos deben distinguirse de valores observados. Los enlaces externos no son necesariamente datos propios de FishBase.
- **Reutilización:** la página compartida en el proyecto indica CC BY-NC 4.0; la incorporación a un servicio comercial requiere aclarar las condiciones aplicables. No se presume autorización.
- **Decisión actual:** referencia candidata; no integrada en los indicadores NAS.

### WoRMS

- **Interés:** contrastar nombres científicos e identificadores taxonómicos marinos.
- **Pregunta posible:** ¿cómo relacionar los nombres originales con una referencia taxonómica común?
- **Pendiente:** verificar cobertura de los taxones del caso, mecanismo de consulta y condiciones de reutilización.
- **Limitación:** resolver un nombre no aporta por sí mismo registros de presencia, precios o abundancia.
- **Decisión actual:** incorporar cuando exista una necesidad concreta de correspondencia taxonómica.

### OBIS

- **Interés:** localizar información de biodiversidad marina pertinente al caso.
- **Pregunta posible:** ¿qué registros adicionales existen para el territorio y periodo seleccionados?
- **Pendiente:** probar consulta y descarga, inspeccionar metadatos, variables y licencia del conjunto.
- **Limitación:** revisar solapamientos con otros agregadores y proveedores originales antes de sumar registros.
- **Decisión actual:** candidata para ampliar cobertura cuando la pregunta lo requiera.

### GBIF

- **Interés:** localizar conjuntos publicados y registros de biodiversidad.
- **Material revisado:** CERMES Barbados Lionfish Sightings 2012, con 43 registros y 169 columnas en su archivo de ocurrencias. No es representativo de todos los conjuntos accesibles mediante GBIF.
- **Referencia del conjunto:** https://www.gbif.org/dataset/8f6d3a0d-10d2-44e3-8612-be219376c860
- **Limitación:** la estructura y completitud dependen del conjunto. La descripción de variables recogidas en un estudio no garantiza que estén presentes en la descarga.
- **Reutilización:** se revisará por conjunto. El archivo inspeccionado muestra CC-BY.
- **Decisión actual:** Barbados queda como ejemplo posterior de incorporación de una fuente adicional.

### USGS NAS

- **Interés:** describir registros de especies acuáticas no autóctonas dentro de la cobertura del producto seleccionado.
- **Extracción utilizada:** consulta de *Pterois volitans/miles*, SpeciesID=963, acceso 11/11/2026.
- **Consulta:** https://nas.er.usgs.gov/queries/CollectionInfo.aspx?SpeciesID=963
- **Formato inspeccionado:** ZIP con CSV, cita, aviso y metadatos.
- **Diagnóstico:** 12.420 registros y 72 columnas; 30 columnas completamente vacías; ningún duplicado exacto ni fila completamente vacía.
- **Limitación:** esta extracción no representa toda la información mundial. No separar *P. volitans* y *P. miles* sin evidencia adicional. Los registros no equivalen a abundancia.
- **Reutilización:** conservar la cita y el aviso de datos provisionales incluidos; comprobar condiciones aplicables a la entrega prevista.
- **Decisión actual:** utilizada en el primer módulo del pez león. No es obligatoria para otros casos.

### EASIN

- **Interés:** explorar información de especies exóticas relevante para casos europeos.
- **Pregunta posible:** ¿qué productos contienen evidencia pertinente para la especie y territorio europeos seleccionados?
- **Pendiente:** comprobar catálogo, productos, granularidad, acceso y condiciones de reutilización.
- **Limitación:** no asumir que un listado de especies equivale a una tabla de observaciones georreferenciadas.
- **Decisión actual:** candidata para el contraste territorial europeo.

## Regla de selección

Una fuente se utiliza si su extracción aporta una variable necesaria con cobertura y calidad adecuadas. Puede utilizarse parcialmente, quedar como complemento o descartarse para ese caso. Una fuente descartada para un caso permanece en el catálogo si puede servir para otros.

## Extensiones pendientes

Las fuentes de desembarques, precios, ventas y costes se incorporarán al abordar la pregunta comercial. Los suplementos de artículos y los datos de colaboradores se describirán como conjuntos específicos, manteniendo su propia procedencia, estructura y condiciones de uso.
