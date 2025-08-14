# Laboratorio 3: Análisis GeoEspacial y Sensores Remotos
## Monitoreo de Deforestación en Petén, Guatemala usando Sentinel-2

## Resumen del Proyecto

Análisis de deforestación en Petén, Guatemala comparando imágenes Sentinel-2 entre enero 2020 y enero 2024. Implementa técnicas de teledetección para detectar, cuantificar y visualizar cambios en cobertura vegetal usando índices NDVI.


## Tecnologías

**Plataformas:** Copernicus Data Space Ecosystem, Jupyter Notebook  
**Librerías:** numpy, matplotlib, rasterio  
**Datos:** Sentinel-2 L2A (Bandas B4-Rojo, B8-NIR)  

## Analisis

### **Análisis Básico (Requerido):**
- Mapas NDVI comparativos 2020 vs 2024
- Imagen de diferencia con esquema RdYlGn  
- Máscara deforestación (umbral -0.2)

### **Análisis Avanzado (Adicional):**

**1. Distribución NDVI 2024 y 2020**

Histograma con distribucion de NDVI comparando 2020 y 2024

**2. Análisis de Impacto por Tipo de Vegetación** 

Determina las categorias mas afectadas por la deforestacion

**3. Análisis Multi-Umbral Espacial**

Grid 2x2 mostrando progresión de severidad con porcentajes de área afectada


## Conclusiones

Existe una pérdida de vegetación significativa en el departamento de Petén entre 2020 y 2024. Las áreas protegidas ven un incremento en índice de vegetación, particularmente la selva al norte, mientras que el resto del departamento sufre de deforestación. Las áreas con vegetación densa se han empezado a volver áreas con vegetación moderada o baja.

La deforestación no presenta 'hotspots' donde las pérdidas son grandes en áreas específicas. En su lugar, existen áreas distribuidas a lo largo del departamento que sufren de deforestación y a lo largo de estas áreas se encuentran las pérdidas más grandes. Interesantemente, las áreas con baja vegetación vieron ganancias en vegetación, mientras que las áreas con vegetaciones más densas vieron pérdidas.

Recomendamos que los esfuerzos ecológicos se enfoquen en prevenir la deforestación, en lugar de enfocarse en la reforestación. En este caso, se puede ver como los esfuerzos actuales tienen frutos pero no atacan el 'problema más grande'.

## Recomendaciones Futuras

Para estudios posteriores, se recomienda utilizar más puntos de diferencia temporal para poder llevar a cabo visualizaciones más precisas. Sería beneficioso utilizar identificadores regionales como departamentos o municipios para un análisis más granular. El análisis de NDVI debería complementarse con algunas otras métricas espectrales para mayor robustez. Finalmente, es fundamental consultar con expertos en el área para identificar las causas específicas de los patrones observados.
