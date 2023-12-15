El presente trabajo aborda la transformación analítica de datos en la comunidad "Data Fitness", guiado por el
objetivo de revelar patrones y responder a preguntas clave. El proceso se ha dividido en etapas fundamentales,
cada una contribuyendo al proceso analítico completo.

En primer lugar, se generan los datos en Mockaroo para crear conjuntos de datos simulados y representativos de
la actividad en "Data Fitness". Estos datos se han alojado en GitHub y posteriormente se han ingestado en el
Hadoop File System (HDFS) a través de Apache NiFi. Si bien GitHub no es comúnmente utilizado para este tipo de
procesos fue una solucion adecuada para este caso puntual.

En cuanto a la transformación y refinamiento de datos, se ha hecho mediante Spark, se realizan
transformaciones esenciales para refinar los datos, asegurando coherencia y calidad. El resultado se almacena en
un nuevo directorio en el HDFS.

En tercer lugar, utilizando Hive, se unifican las fuentes de datos refinadas, creando una base para el análisis
subsiguiente. Este paso permite abordar las preguntas planteadas con una visión completa de "Data Fitness".
Por último, con SuperSet, se exploran las tablas de Hive para generar visualizaciones. Este enfoque no solo
responde a las preguntas específicas, sino que también proporciona una narrativa visual que facilita la
interpretación y comunicación de los hallazgos.
