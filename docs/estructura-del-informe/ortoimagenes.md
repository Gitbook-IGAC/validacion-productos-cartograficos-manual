# Ortoimágenes

<figure><img src="../.gitbook/assets/int_07.png" alt=""><figcaption></figcaption></figure>

Al acceder a la interfaz de validación, el sistema presenta un informe en blanco cuya estructura se encuentra establecida. Este se diligencia progresivamente a medida que se realiza la inspección y la verificación de los criterios de calidad correspondientes.

<div data-full-width="true"><img src="../.gitbook/assets/Estructura_Orto (1).gif" alt=""></div>

<p align="center"><sup><em>Diligenciamiento del Informe de validación en Ortoimágenes</em></sup></p>

### Estructura e integridad

El criterio inicial de calidad a evaluar corresponde a la Estructura e Integridad del producto raster, el cual asegura que el archivo cumple con las especificaciones técnicas fundamentales para su uso. Este criterio se compone de subelementos que definen la calidad de la imagen: la Resolución Espacial (el tamaño del píxel o GSD), la Resolución Espectral (el número de bandas utilizadas) y la Resolución Radiométrica (la profundidad de bits).

<figure><img src="../.gitbook/assets/Diligenciamiento del Informe de validación_Estructura e Integridad (2).png" alt=""><figcaption></figcaption></figure>

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Estructura e Integridad</em></sup></p>

### Totalidad

El siguiente elemento de calidad a evaluar es la Totalidad por Omisión, el cual verifica el área geográfica continua del producto raster/imagen respecto a los límites del área del proyecto. Este criterio es fundamental para asegurar que no existen vacíos de imagen. La plantilla del informe permite registrar la cuantificación de la omisión y su correspondiente declaración de conformidad.

<figure><img src="../.gitbook/assets/Diligenciamiento del Informe de validación_Totalidad_2.png" alt=""><figcaption></figcaption></figure>

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Totalidad</em></sup></p>

### Exactitud en posición

La Exactitud en Posición Relativa se evalúa mediante una metodología de muestreo espacial, que consiste en la definición y medición de puntos de verificación distribuidos de manera uniforme a lo largo del área del proyecto. La evaluación de este ítem es de gran importancia, ya que el valor máximo de error aceptable se determina en función de la escala cartográfica del producto. El informe documenta el error obtenido y se compara con el nivel de tolerancia estándar para determinar la conformidad.

![](<../.gitbook/assets/Unknown image (33)>)

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Exactitud en Posición</em></sup></p>

### Consistencia lógica

El criterio de Consistencia Lógica es importante para los productos de imagen, ya que verifica la coherencia interna de un mosaico o una imagen individual. Esta evaluación se enfoca en tres subelementos esenciales: el Empalme (evaluando la continuidad geométrica a lo largo de las líneas de unión), la Distorsión Geométrica (identificando errores internos que afecten la planimetría de la imagen) y el Desbalance Radiométrico (asegurando la uniformidad de color y brillo entre las imágenes componentes).

![](<../.gitbook/assets/Unknown image (34)>)

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Consistencia Lógica</em></sup></p>

### Formato

El siguiente elemento de evaluación es la Conformidad del Formato de Entrega y Despliegue. Este criterio asegura la interoperabilidad en los entornos de producción. Se requiere que el producto sea entregado en cualquiera de los siguientes formatos validados: TIFF (Geo TIFF, TIELD512):

![](<../.gitbook/assets/Unknown image (35)>)

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Formato</em></sup></p>

### Sistema de referencia

El elemento Sistema de Referencia constituye un requisito de conformidad obligatoria. Para todas las Ortoimágenes, se debe verificar que el sistema de coordenadas horizontal utilizado corresponda con el estándar oficial MAGNA-SIRGAS 2018 Origen-Nacional. La validación de este ítem determina si el producto es técnicamente apto para su integración con el Marco Geocéntrico Nacional de Referencia.

![](<../.gitbook/assets/Unknown image (36)>)

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Sistema de Referencia</em></sup></p>

### Consistencia temporal

Posteriormente, se procede a evaluar la Consistencia Temporal de la Base Vectorial, verificando la vigencia y actualidad de los datos. La norma establece dos rangos de tolerancia: la información debe tener una antigüedad igual o inferior a tres (3) años para áreas de alta dinámica (urbana, infraestructura reciente) y se permite una antigüedad de hasta cinco (5) años para zonas con baja o nula dinámica inmobiliaria (zonas rurales remotas o áreas protegidas estables).

![](<../.gitbook/assets/Unknown image (37)>)

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Consistencia Temporal</em></sup></p>

### Metadato

La evaluación final se centra en el Metadato del producto geográfico, el cual debe cumplir con los estándares normativos vigentes. Esta revisión se lleva a cabo mediante la Herramienta de Validación de Metadato, la cual inspecciona una serie de parámetros obligatorios. El resultado de esta verificación automatizada arroja un concepto final (Aprobado o No Aprobado).

![](<../.gitbook/assets/Unknown image (19)>)

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Metadato</em></sup></p>

### Observaciones finales

Para finalizar el informe, se diligencia la sección de Observaciones Generales y debe contener el concepto final de la validación. Además, esta sección debe incluir las rutas de acceso donde se dispone el producto validado y los resultados detallados de la inspección. Como anexos obligatorios, se deberá adjuntar la salida gráfica de localización del proyecto, y, en caso de haberse detectado inconsistencias, se deberá incluir la Geodatabase (GDB) de Inconsistencias para facilitar su ajuste.

![](<../.gitbook/assets/Unknown image (38)>)

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Concepto</em></sup></p>

Finalmente, la plataforma Colombia en Mapas cuenta con dos casillas al finalizar el módulo, las cuales representan los conceptos finales de las inspecciones de validación de cada producto:

#### **Validación Conforme**

Se asigna la conformidad cuando el producto cumple con los estándares y especificaciones técnicas de cartografía básica. Después de la validación pueden existir inconsistencias, pero estas se encuentran dentro de los umbrales máximos permitidos, lo que permite su posterior oficialización.

#### **Validación No Conforme**

Se asigna la no conformidad cuando las inconsistencias superan el umbral máximo permitido. En este caso, el productor debe revisar y ajustar la totalidad de las inconsistencias, garantizando el cumplimiento de los estándares requeridos. Para soportar este concepto, la plataforma genera automáticamente el reporte final de validación y la geodatabase (GDB) de inconsistencias, en la cual se espacializan los errores encontrados durante el proceso.
