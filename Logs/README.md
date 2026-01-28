# Directorio de Logs

## Propósito

Este directorio almacena todos los archivos de texto generados automáticamente por el workflow de n8n. Cada archivo representa una ejecución del proceso automatizado y mantiene un registro histórico de las operaciones realizadas.

## Contenido

Los archivos en este directorio pueden incluir:

- **Registros de ejecución**: Logs detallados de cada ejecución del workflow
- **Archivos de texto generados**: Documentos creados automáticamente por el sistema
- **Timestamps**: Marcas temporales de cada operación
- **Metadata**: Información adicional sobre el contexto de cada ejecución
- **Resultados de procesos**: Output de operaciones automatizadas

## Convenciones de Nomenclatura

Los archivos generalmente siguen un patrón de nomenclatura que incluye:

- Fecha y hora de creación
- Identificador del proceso
- Tipo de operación realizada
- Extensión `.txt` o `.md` según el caso

Ejemplo: `log_2026-01-27_143055.txt`

## Automatización

Todos los archivos en este directorio son:

- Creados automáticamente por n8n
- Versionados mediante Git
- Committeados sin intervención manual
- Parte del historial del repositorio

## Uso

Este directorio **NO** debe modificarse manualmente. Cualquier cambio debe realizarse a través del workflow automatizado configurado en n8n para mantener la integridad del sistema.

## Limpieza

Se recomienda realizar limpieza periódica de archivos antiguos cuando:

- El tamaño del repositorio crezca significativamente
- Los logs tengan más de cierto período de antigüedad
- Se requiera optimizar el rendimiento del repositorio

La limpieza debe coordinarse con el equipo responsable para evitar pérdida de información relevante.
