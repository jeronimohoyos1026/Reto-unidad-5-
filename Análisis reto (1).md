# **Análisis reto** 

Juan Camilo Valencia Hurtado Jeronimo David Hoyos Espinosa 

**(Estudiantes)** 

Henry Hermel Andrade Caicedo **(Docente)** 

Programacion 

**(Curso)** 

Universidad Pontificia Bolivariana 

Sede Medellín 

Colombia, Antioquía, Medellín 

# **Análisis** 

En el siguiente análisis detallamos estructuradamente los datos txt y csv 

# **1. ¿De dónde salieron?** 

#  **Texto literario (** **_Cien años de soledad_ ):** 

Origen primario: Es una obra literaria de ficción escrita por Gabriel García Márquez en 1967. 

Origen del archivo de datos: El archivo PDF procesado proviene de repositorios digitales educativos institucionales ( de la  Secretaría de Educación de Veracruz), donde el libro fue digitalizado para su consulta y análisis sintáctico mediante scripts de lectura de texto plano (.txt o procesamiento de PDF). 

#  **Dataset de transporte (Aeropuertos de operación - SATENA):** 

Origen primario: Datos operacionales de la empresa estatal Servicio Aéreo a Territorios Nacionales (SATENA) y la Aeronáutica Civil de Colombia. 

Origen del archivo de datos: Portal Oficial de Datos Abiertos del Gobierno de Colombia (datos.gov.co),administrado por el Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC), disponible en formatos estructurados (como .csv) con delimitadores estándar. 

# **2. ¿Qué representan?** 

#  **Texto literario (** **_Cien años de soledad_ ):** 

Representación de datos: Constituye un conjunto de datos no estructurados. 

Representa el universo cultural, histórico y fantástico de Macondo. En un contexto analítico,permite estudiar la frecuencia de términos, la longitud de las líneas, patrones 

narrativos, personajes y conceptos clave como el aislamiento, las enfermedades o el tiempo. 


Representacion de datos: Lo obtuvimos descargándolo desde una página de Google dedicada a repositorios públicos de datos y recursos educativos en línea.

Desde allí se guardó directamente en el equipo en la ruta local /Users/camilovalencia/Documents/txt/long-doc.txt.txt para ser procesado localmente mediante el script de Python.

Representa un archivo de texto plano (formato .txt) estructurado para pruebas de análisis de datos. Contiene una combinación de información geográfica de departamentos de Colombia (como Chocó, Antioquia o Amazonas con sus respectivas coordenadas de latitud y longitud) junto con un corpus de texto sintético compuesto por bloques de Lorem Ipsum e instrucciones de código (como la palabra translate), diseñado específicamente para practicar extracción de datos, visualización y procesamiento de lenguaje natural.

#  **Dataset de transporte (SATENA):** 

Representación de datos: Constituye un conjunto de datos estructurados organizados en filas y columnas. 

Representa la infraestructura física, la cobertura de transporte aéreo regional y la conectividad geográfica en Colombia. Permite realizar análisis cuantitativos como el conteo de frecuencias por departamento, promedios, medianas y visualización de tendencias o dispersión de datos. 

# Conclusiones obtenidas de los gráficos de los datos 
•	Existe una alta diversidad topográfica en la red de operaciones de la aerolínea. Mientras que muchos aeródromos operan a nivel del mar o en zonas planas de baja altitud (cerca de 0 pies), otros picos superan los 800 pies, reflejando los retos geográficos de conectar regiones selváticas, costeras y montañosas.

•	Chocó (10.5%), Antioquia (7.0%) y Amazonas (7.0%) lideran la concentración de operaciones o infraestructura registrada. Esto demuestra estadísticamente el propósito misional de la aerolínea estatal: priorizar la conectividad en regiones periféricas, selváticas o apartadas donde la infraestructura vial es limitada.

•	Se confirma que el archivo carece de párrafos largos o densos. Las líneas son extremadamente cortas, lo cual es coherente con frases de saludo o líneas de texto sueltas.

• La gran mayoría de las palabras principales en el análisis corresponden al texto estándar de relleno (sit, lorem, ipsum, elit, dolor, consectetur, amet y adipiscing), cada una con exactamente 2000 apariciones.          

• Chocó representa la proporción más alta dentro de la distribución total con un 10.5%, dando a concluir que el chocó es el departamento  donde la aerolínea satena realiza mas sus vuelos con frecuencia.

