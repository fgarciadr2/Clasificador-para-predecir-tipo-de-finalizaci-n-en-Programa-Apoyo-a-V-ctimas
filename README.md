El Programa Apoyo a Víctimas de la Subsecretaría de Prevención del Delito, funciona en gran parte a través de Centros de Apoyo a Víctimas de Delito (CAVD), de los cuales hay al menos uno en una comuna de todas las regiones de Chile. En estos centros, las víctimas de delito reciben ayuda de psicólogos, abogados y trabajadores sociales, con el objetivo de superar las consecuencias negativas de la victimización.
Las víctimas que ingresan a estos centros pueden recibir distintos tipos de intevención: Intervención T1, la cual es de baja complejidad y no requiere establecer objetivos de intervención; Intervención T2, de mediana complejidad en la cual se establecen objetivos que pueden estar asociados a cualquier profesión (Abogado, Psicólogo o Trabajador social); e Intervención T3, para casos de alta complejidad, en los cuales se establecen objetivos que están asociados exclusivamente a alguna de las profesiones mencionadas.
Las víctimas pueden finalizar por haber terminado alguna de estas intervenciones, o bien por haber dejado de asistir a 3 sesiones consecutivas (Cierre administrativo), porque no se haya hecho ningún tipo de actividad relacionada a esta por un periodo de 15 días (No adscripción) por haber sido derivada a otro CAVD o institución (Derivación o referenciación) o por haber abandonado la intervención voluntariamente (Deserción).
En este análisis, aplicamos un clasificador Random Forest para predecir cuál de estos tipos de finalización se esperaría en una víctima que ingresa a alguno de estos centros. Las variables independientes utilizadas para este análisis son las siguientes:
•	Vía de ingreso
•	Delito
•	Edad
•	Sexo
•	Comuna de residencia
•	Comuna del delito
•	Nacionalidad
•	Mes de ingreso
•	CAVD
•	Duración de la intervención
•	Tipo de víctima
•	Contexto VIF
Este clasificador tiene una precisión de 47%, lo cual muestra que es necesario que los sistemas de registro del Pograma Apoyo  a Víctimas necesitarían incluir más variables de caracterización de la victima para poder predecir cómo finalizaría cada víctima.
