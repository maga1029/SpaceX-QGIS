## Componentes de la Capa Geoespacial

Este directorio contiene los archivos que componen la capa geoespacial en formato vectorial, junto con los metadatos e imágenes de referencia. Todos los archivos tienen el mismo nombre pero diferente extensión, y deben almacenarse en el mismo directorio.

### Capa Vectorial en Formato Shapefile

La capa vectorial se compone de cuatro archivos esenciales que son indispensables para abrir el mapa:

- **shp**: El archivo principal que almacena la geometría de la entidad.
- **shx**: El archivo que almacena el índice de la geometría de la entidad.
- **dbf**: Tabla dBASE que almacena la información de atributos de las entidades.
- **prj**: Archivo que contiene la información del sistema de coordenadas de la capa.

> **Nota**: Para abrir la capa geoespacial en formato vectorial, utilice un programa compatible con archivos shapefile (SHP).

### Metadatos y Archivos de Referencia

- Un archivo **xml** con el metadato.
- Un archivo **html** con el metadato.
- Dos archivos **png** con imágenes de vista previa.

### Archivos Adicionales

El directorio puede contener otros archivos de referencia o complementarios. Para obtener más detalles, se recomienda leer el metadato asociado a la capa geoespacial.
