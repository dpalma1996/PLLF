# Procedencia y gestión de datos

[Volver a la portada](../README.md)

## Descarga utilizada

| Campo | Valor |
|---|---|
| Proveedor | U.S. Geological Survey · Nonindigenous Aquatic Species |
| Consulta | https://nas.er.usgs.gov/queries/CollectionInfo.aspx?SpeciesID=963 |
| Taxón exportado | Pterois volitans/miles |
| Fecha de acceso | 11/11/2026 |
| Archivo descargado | NAS-Data-Download-11-11-2026-20654.zip |
| Copia utilizada en la revisión | NAS-Data-Download-11-11-2026-20654(1).zip |
| Tabla interna | NAS-Specimen-Download.csv |

El sufijo `(1)` corresponde al nombre de una copia descargada; no se interpreta como versión científica del conjunto.

## Contenido del ZIP

- `NAS-Specimen-Download.csv`
- `citation.txt`
- `USGS NAS Data Disclaimer.txt`
- `2016-10-24_NAS_Metadata.pdf`

## Cómo obtener los datos

Consultar la página indicada y su opción de descarga. La base puede actualizarse: una descarga posterior puede producir resultados distintos. Para reproducir exactamente el diagnóstico inicial debe utilizarse el ZIP del 11/11/2026. El cuaderno calcula su SHA-256 para identificar los bytes empleados.

## Organización local prevista

- `data/raw/`: originales sin modificaciones.
- `data/processed/`: datos derivados, acompañados de reglas de preparación.

Estas carpetas se excluyen inicialmente del control de versiones. Los agregados y figuras revisados pueden publicarse en la carpeta de resultados del caso cuando sus condiciones de uso lo permitan. No se incluyen datos originales en este paquete documental.

## Reglas de trabajo

Conservar procedencia y fecha de consulta; mantener los originales; no añadir credenciales; diferenciar datos observados de derivados; comprobar condiciones de redistribución y uso comercial por fuente. Un catálogo de fuentes no concede una licencia conjunta.

## Cita

U.S. Geological Survey, 2026, Specimen observation data for Pterois volitans/miles, Nonindigenous Aquatic Species Database, Gainesville, FL, https://nas.er.usgs.gov/queries/CollectionInfo.aspx?SpeciesID=963, Access Date: 11/11/2026.
