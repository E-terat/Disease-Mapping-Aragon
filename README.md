# Disease Mapping (EN version)

In this project we evaluate the BYM model in mortality by ischemical disease in Aragón (Spain), using two aproximations: Markov Chain Montecarlo (MCMC) via WinBUGS and Integrated Nested Laplace Aproximation (INLA). 

The code to replicate this work is avaiable in this repository. There, it is the final report (`.html`) and the Rmarkdown (`.rmd`) in order for you to see all the code used. All the data used is include in the folder `datos`. 


# Downloading data

After downloading the project, if the interest is in the code `.rmd`, it is better to open first the Rproject. Then, open the code inside this environmet, so the data is well loaded.
Some chunks are not shown in the final document, as they were irrelevant to discuss the results. If interested, just change the first chunk in the `.rmd` (`{r setup}`)  to `echo = T`. Som other chunks were setted to `eval = F`, e.g. the previous trials performed with winBUGS, in order to improve the knit of the final `.html`. To eval this code, it is suggested to follow directly the code (or change to `eval = T` the associated chunk options). 

Contact us by email (estera\@alumni.uv.es, pausise\@alumni.uv.es) or GitHub (<https://github.com/E-terat>).


----------------------------------------------


# Cartografía de enfermedades (SP version)

En este trabajo se evalúa el comportamiento del modelo de BYM en la mortalidad de por enfermedad isquémica en Aragón, utilizando dos aproximaciones para ello: Markov Chain Montecarlo (MCMC) via WinBUGS and Integrated Nested Laplace Aproximation (INLA). 

El código para replicar el trabajo está disponible en este repositorio, desde el documento final ya generado (`.html`) hasta el código empleado con todo lo necesario para obtener los resultados. Los datos de cartografía y observaciones de Aragón están disponibles en la carpeta `datos`

# Descarga de datos
Una vez descargado el proyecto, se recomienda abrir el archivo Rproject y, después, el código del trabajo para que la carga de datos no se vea comprometida. 

Algunos trozos del código disponibles en el `.rmd` no aparecen en el `html` final dada su irrelevancia a la hora de analizar los resultados obtenidos. En caso de querer evaluarlos todos conviene modificar la primera inserción de código (`{r setup}`) y utilizar `echo = T`. En otros trozos de código, en los modelos probados con WinBUGS, se ha establecido `eval = F` para el documento final se genere más rápido. En caso de que sea de interés evaluar tales modelos, se recomienda hacerlo directamente desde `Rstudio` por este mismo motivo o cambiar `eval = T` de las opciones de ese trozo de código.

Para cualquier duda, el equípo queda totalmente a su disposición. Puede contactar mediante email (estera\@alumni.uv.es, pausise\@alumni.uv.es) o a través de GitHub (<https://github.com/E-terat>).
