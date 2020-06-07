<h1>GitHub de la práctica de Limpieza y Validación de los Datos de la asignatura Tipología y Ciclo de Vida de los Datos del Master en Data Science</h1>

<p><h2>Autores:  </h2></p>
          <b>Anddy Aldave Valle</b> &nbsp; github: https://github.com/aaldaveva</br>
          <b>Alejandro Pulido Duque</b> &nbsp;github: https://github.com/alexxplus</p>

<p><h2>Objetivo:  </h2></p>
<p>Identificación de los datos relevantes para un proyecto analítico y en el uso de herramientas de integración, limpieza, validación y análisis de las mismas.</p>

<p><h2>Relación de archivos:  </h2></p>
<p>A continuación se listan los archivos presentes en este análisis:</p>
<ul><li>diamonds.csv: set de datos original</li>
          <li>diamonds_processed.csv: set de datos generado después del análisis</li>
          <li>carpeta codigo: PR2.rmd: código en R creado para el análisis de los datos en formato markdown</li>
          <li>carpeta documentacion: contiene 2 ficheros: PRD2.html: informe dinámico en formato markdown HTML generado tras el análisis, incluyendo todas las conclusiones y procedimientos y PR2.pdf: informe anterior en formato PDF</li>
</ul>

<p><h2>Desarrollo:  </h2></p>
<p>La práctica la hemos desarrollado en R. Para su correcta ejecución, se necesita instalar las siguientes librerías:</p>
<ul><li>install.packages("VIM")</li><li>install.packages("reshape2")</li><li>install.packages("ggplot2")</li><li>install.packages("psych")</li><li>install.packages("arules")</li><li>install.packages("rcompanion")</li><li>install.packages("ResourceSelection")</li><li>install.packages("pROC")</li><li>install.packages("tidyverse")</li><li>install.packages("rpart")</li><li>install.packages("rpart.plot")</li><li>install.packages("faraway")</li><li>install.packages("caret")</li>
</ul>

<p><h2>Atributos presentes en el set de datos original:  </h2></p>
<p>El análisis se ha basado en los siguientes atributos presentes en el set de datos original:</p>
<ul><li>carat: Peso del diamante</li><li>cut: Calidad subjetiva del corte</li><li>color: Color del diamante</li><li>clarity: Claridad o transparencia del diamante</li><li>depth: Altura del diamante</li><li>table: Anchura del diamante</li><li>price: Precio</li><li>x: Longitud del diamante</li><li>y: Ancho del diamante</li><li>z: Profundiad del diamante</li></ul>


![alt text](https://github.com/aaldaveva/limpiezaValidacionDatos/blob/master/images/diamante.JPG?raw=true "Diamante")
