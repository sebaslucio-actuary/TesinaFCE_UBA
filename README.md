# TesinaFCE_UBA

El uso de modelos ARIMAX para modelar el impacto de las fluctuaciones de tipo de cambio en el precio del valor de los respuestos. 

"......Para dar claridad acerca de la temporalidad y magnitud de shocks de este tipo, en el
presente trabajo se construye una herramienta de gestión, que simula el impacto de un
shock devaluatorio en la trayectoria individual de cada uno de los componentes de la tasa"


# Introduccion del trabajo

El armado de precios del seguro automotor se apalanca en información pasada, en precios
de referencia del mercado y en la proyección de tendencias de las variables de frecuencia
y severidad. Dentro de la proyección de tendencias podemos encontrarnos con
desequilibrios transitorios correlacionados con variables macroeconómicas que en
entornos de alta volatilidad deberíamos tomar en cuenta para desarrollar una estrategia de
precios adecuada.
El presente trabajo analiza el equilibrio del precio del seguro automotor en la Argentina
para una cobertura de daños parciales, mostrando su estrecha relación con la estabilidad
del tipo de cambio, y el impacto permanente o transitorio que generan las fluctuaciones
de esta variable macroeconómica en la suficiencia de las tasas definidas para esta
cobertura, potencialmente afectando el requerimiento de capital a constituir por las
compañías aseguradoras.
Para dar claridad acerca de la temporalidad y magnitud de shocks de este tipo, en el
presente trabajo se construye una herramienta de gestión, que simula el impacto de un
shock devaluatorio en la trayectoria individual de cada uno de los componentes de la tasa.
Este análisis se enfoca en el llamado grado medio de daño que se refiere a la magnitud
del costo final de un siniestro de daño parcial en relación al valor del vehículo afectado
por el siniestro, dejando de lado cualquier efecto que se pueda dar sobre la frecuencia.
Para esto se utilizaron modelos de series de tiempo denominados ARIMAX que, sobre
información de índole pública sobre la evolución de precios mayorista del mercado
automotor y de autopartes provista por el INDEC, mostraron utilidad para desarrollar una
herramienta de gestión de políticas de tarifación y estimaciones del impacto en
requerimiento de capital, ante cambios estructurales en la tendencia de la severidad.

# Conclusiones

En el presente trabajo, se observa la creciente relevancia que tiene el producto de Todo
Riesgo en el mercado de seguro automotor en la Argentina, donde la cobertura de Daños
Parciales es su característica diferenciadora. Además, se detalla que la constitución de la
tasa a cobrar por dicha cobertura (𝑇𝑎𝑠𝑎􀮽􀯉), puede desglosarse en un componente de
cantidad de siniestros que esperamos en relación con la cantidad de expuestos a ese riesgo
(Frecuencia) y por otro lado a la magnitud de los daños en relación con la suma asegurada
del riesgo cubierto (GMD). El análisis se centró en este último componente que está
determinado por el costo de los repuestos y la mano de obra necesaria para la reparación
del siniestro ocurrido, neteado de la franquicia que es el monto en el que participa el
asegurado en dicho arreglo, y expresado en relación al valor que figura en póliza del bien
asegurado. Asimismo, se observa cómo las insuficiencias permanentes en la tasa pueden
generar requerimientos extra de capital, dado a que todo lo que se deje de cobrar al cliente,
para mantener la solvencia del sistema, tiene que ser previsto por la compañía de seguros.
Cuando se profundizó en el punto 3, en las características de la estructura y los
mecanismos de determinación de precios tanto en el mercado de autopartes como en el
de los costos de los vehículos automotores, encontramos una fuerte incidencia del tipo de
cambio en la determinación de sus precios, dada la naturaleza global del mercado en el
que participan. Tanto la significativa demanda de vehículos importados en el mercado
interno como la relevante participación de autopartes importadas en la producción local
de vehículos automotores, hacen que la cotización de moneda extranjera permee en mayor
o menor medida en la determinación de los listados de precios.
Es así que en el punto 4 encontramos información y metodologías que nos ayudaron a
reflejar el nivel de relación del tipo de cambio y la evolución de los precios de los
mercados mencionados. Partiendo del índice de precios mayoristas de automotores y de
autopartes del INDEC, sumado a la evolución del tipo de cambio nominal multilateral
publicada por el BCRA y los modelos de series de tiempo conocidos como ARMAX se
pudo obtener un modelo de gestión de políticas de precios ante shock de tipo de cambio.
Los modelos ARMAX y las series de información seleccionadas mostraron versatilidad
y compatibilidad para poder reflejar el equilibrio intertemporal de las series de precios
analizadas. Los modelos de cada una de las series, cumplieron con los requisitos
estipulados en la metodología de Box-Jenkins para series de tiempo, que incluye desde
cumplir con las condiciones de estacionariedad de la serie a modelar hasta las condiciones
de independencia y distribución de los residuos, mostrando ser idóneos para modelar este
tipo de fenómenos en los que las serie de tiempo necesita reflejar su correlación con
variables exógenas. Se pudo determinar que el pass throught28 del costo de las autopartes
para este ejercicio puntual fue 46 puntos menor que el pass throught de los vehículos
automotores, generando una trayectoria de GMD a la baja en el caso de un shock
devaluatorio, cuya fuerza contraria radica en el nivel de la inflación de salarios, que si es
sostenidamente un par de puntos mayor a la devaluación comienza a generar la
estabilización del GMD y su recuperación. Además, se observa que esta trayectoria hacia
un nuevo equilibrio es fluctuante hasta estabilizarse en un nuevo equilibrio inercial, dado
a cómo se distribuye el pass throught en el tiempo en cada uno de los mercados,
potenciando distorsiones temporales no permanentes que son con las que se quiere evitar
tomar decisiones, validando la utilidad de nuestro modelo de gestión.
Por último, la definición de la estrategia óptima del modelo de gestión radica en la
velocidad y magnitud de adaptación de los competidores ante un shock devaluatorio, pues
destacan varias razones que impiden que sea inmediato, y que dada la naturaleza
fluctuante de corto plazo los actores se comporten de distintas maneras. Es ahí donde la
decisión de la trayectoria de la tasa de daños parciales, fruto de una política de precios
determinada, va a definir a través de la estimación de nuestro modelo, el potencial
requerimiento o ahorro de capital al que va a tener que hacer frente el accionista.
En economías con constantes shocks macroeconómicos que generan distorsiones de
precios relativos, es de suma utilidad contar con una estimación de la trayectoria de dicho
precio relativo para tomar definiciones estratégicas de manejo del shock y de naturaleza
de largo y mediano plazo.
El modelo del presente trabajo se construyó sobre información de disponibilidad pública.
Para futuras aplicaciones, las estimaciones de sus parámetros con bases de datos propias
de las compañías, agregarían precisión y mayor valor en las estimaciones relevantes para
la cartera que se quiera analizar, ajustándose a las características de la estructura de
formación de costos propia de la dinámica de la compañía sobre la que se esté definiendo
(El pass through hace referencia al impacto que tiene en los precios una suba del tipo
del cambio, en este caso el dólar que es la moneda de referencia en la Argentina
la política de precios.)
Además, en futuras investigaciones se podría analizar el comportamiento de la frecuencia
ante las fluctuaciones del tipo de cambio y cómo esto terminaría influyendo en conjunto
con las fluctuaciones de GMD en la Tasa. En términos de ampliar el modelo propuesto,
es relevante el analizar el levantamiento de los supuestos de nuestro modelo inicial, tal
como la incidencia de la política de franquicias, periodicidad no mensual en la
actualización de la prima a cobrar, impactos en conversión y retención en el equilibrio
final de la estrategia de precios, además de la ampliación de la metodología propuesta a
otras coberturas y variables macroeconómicas relevantes.
