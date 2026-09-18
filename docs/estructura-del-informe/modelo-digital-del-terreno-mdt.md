# Modelo Digital del Terreno (MDT)

<figure><img src="../.gitbook/assets/int_06.png" alt=""><figcaption></figcaption></figure>

Al acceder a la interfaz de validación, el sistema presenta un informe en blanco cuya estructura se encuentra establecida. Este se diligencia progresivamente a medida que se realiza la inspección y la verificación de los criterios de calidad correspondientes.

<div data-full-width="true"><img src="../.gitbook/assets/Estructura_MDT.gif" alt=""></div>

<p align="center"><sup><em>Diligenciamiento del Informe de validación en Modelos Digitales de Terreno</em></sup></p>

### Totalidad

El criterio inicial de calidad para evaluación es la Totalidad. En el contexto del Modelo Digital de Terreno (MDT), este elemento evalúa específicamente la Omisión de la Cobertura Superficial del MDT respecto a los límites definidos para el área del proyecto. La validación asegura que no existan vacíos o datos faltantes dentro del área geográfica estipulada. La plantilla del informe facilita el registro de los valores de resultado y el nivel de conformidad obtenidos tras el análisis de la continuidad del producto.

![](<../.gitbook/assets/Unknown image (202)>)

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Totalidad</em></sup></p>

### Consistencia lógica

Una vez determinada la Totalidad, se procede a la evaluación de la Consistencia Lógica del Modelo Digital de Terreno (MDT). Este criterio es esencial para asegurar la integridad estructural y la coherencia interna del producto. La inspección se centra en tres subelementos clave: _la Resolución Espacial,_ verificando el tamaño de celda y su correspondencia con la escala de producción, _la Determinación de Valores Atípicos_, identificando y cuantificando las anomalías abruptas de elevación que comprometen la continuidad del modelo y la _detección de vacíos,_ identificando inconsistencias en la geometría de curvas, errores de modelo y polígonos basura.

![](<../.gitbook/assets/Unknown image (203)>)

<p align="center"><sup><em>Diligenciamiento del Informe de validación: Consistencia Lógica</em></sup></p>

### Exactitud en posición

La Exactitud en Posición Relativa se evalúa mediante una metodología de muestreo espacial, que consiste en la definición y medición de puntos de verificación distribuidos de manera uniforme a lo largo del área del proyecto. La evaluación de este ítem es de gran importancia, ya que el valor máximo de error aceptable se determina en función de la escala cartográfica del producto. El informe documenta el error obtenido y se compara con el nivel de tolerancia estándar para determinar la conformidad.

<figure><img src="../.gitbook/assets/Diligenciamiento Elemento de calidad_Exactitud en Posición (2).png" alt=""><figcaption></figcaption></figure>

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Exactitud en Posición</em></sup></p>

### Formato

El siguiente elemento de evaluación es la Conformidad del Formato de Entrega y Despliegue. Este criterio asegura la interoperabilidad en los entornos de producción. Se requiere que el producto sea entregado en cualquiera de los siguientes formatos validados: TIFF (Geo TIFF de 32 bits número real de tipo float).

<figure><img src="../.gitbook/assets/Diligenciamiento Elemento de calidad_Formato de Entrega_2.png" alt=""><figcaption></figcaption></figure>

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Formato de Entrega</em></sup></p>

### Sistema de referencia

El elemento Sistema de Referencia constituye un requisito de conformidad obligatoria. Para todos los MDTs, se debe verificar que el sistema de coordenadas horizontal utilizado corresponda con el estándar oficial MAGNA-SIRGAS 2018 Origen-Nacional. La validación de este ítem determina si el producto es técnicamente apto para su integración con el Marco Geocéntrico Nacional de Referencia.

<figure><img src="../.gitbook/assets/Diligenciamiento Elemento de calidad_Sistema de Referencia_2.png" alt=""><figcaption></figcaption></figure>

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Sistema de Referencia</em></sup></p>

### Consistencia temporal

Posteriormente, se procede a evaluar la Consistencia Temporal de la Base Vectorial, verificando la vigencia y actualidad de los datos. La norma establece dos rangos de tolerancia: la información debe tener una antigüedad igual o inferior a tres (3) años para áreas de alta dinámica (urbana, infraestructura reciente) y se permite una antigüedad de hasta cinco (5) años para zonas con baja o nula dinámica inmobiliaria (zonas rurales remotas o áreas protegidas estables).

![](<../.gitbook/assets/Unknown image (207)>)

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Consistencia Temporal</em></sup></p>

### Metadato

La evaluación final se centra en el Metadato del producto geográfico, el cual debe cumplir con los estándares normativos vigentes. Esta revisión se lleva a cabo mediante la Herramienta de Validación de Metadato, la cual inspecciona una serie de parámetros obligatorios. El resultado de esta verificación automatizada arroja un concepto final (Aprobado o No Aprobado).

![](<../.gitbook/assets/Unknown image (208)>)

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Metadato</em></sup></p>

### Observaciones finales

Para finalizar el informe, se diligencia la sección de Observaciones Generales y debe contener el concepto final de la validación. Además, esta sección debe incluir las rutas de acceso donde se dispone el producto validado y los resultados detallados de la inspección. Como anexos obligatorios, se deberá adjuntar la salida gráfica de localización del proyecto, y, en caso de haberse detectado inconsistencias, se deberá incluir la Geodatabase (GDB) de Inconsistencias para facilitar su ajuste.

![](<../.gitbook/assets/Unknown image (209)>)

<p align="center"><sup><em>Diligenciamiento Elemento de calidad: Concepto</em></sup></p>

