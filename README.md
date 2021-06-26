# pepaitba

## Pensamiento Estadístico en People Analytics :nerd_face:

Este paquete contiene tutoriales interactivos de las clases de **Pensamiento Estadístico en People Analytics** (PEPA) de la Diplomatura de People Analytics perteneciente a la [Escuela de Innovación del ITBA](https://www.itba.edu.ar/la-universidad/escuelas/escuela-de-innovacion/).

Para poder instalar este paquete directamente desde GitHub, primero hay que tener instalado el paquete `remotes`. En el caso que no esté instalado lo podés hacer de la siguiente manera:

```{r eval=FALSE}
install.packages("remotes")
```

Una vez instalado `remotes`, se puede instalar el paquete `pepaitba` copiando y pegando ésta línea de código:

```{r eval=FALSE}
remotes::install_github("chechoid/pepaitba")
```

Para poder utilizar los tutoriales de este paquete es necesario tener instalado el paquete `learnr`. Si lo necesitás instalar lo podés hacer de la siguiente manera:

```{r eval=FALSE}
install.packages("learnr")
```

## Usar los tutoriales

Ya con todos los paquetes instalados, para poder utilizar un tutorial tenés que correr el siguiente código:

```{r eval=FALSE}
learnr::run_tutorial("pepa1", "pepaitba")
```

-   `"pepa1"` es el nombre del tutorial. Para cada clase utilizar el número de tutorial que corresponda.

-   `"pepaitba"` es el nombre del paquete.

## Inconvenientes, bugs, y esas cosas

Por problemas en el uso de los paquetes, errores en las clases, e inconvenientes que puedan llegar a aparecer con el uso de este paquete nos podés escribir a

[Sergio Garcia Mora](https://www.linkedin.com/in/sergiogarciamora/) (sergio\@d4hr.com o serggarcia\@itba.edu.ar).

[Arturo De Zan](https://www.linkedin.com/in/arturodezan/) (adezan\@itba.edu.ar)

## Agradecimientos y créditos

Muchas gracias a [Yanina Bellini Saibene](https://twitter.com/yabellini) :raised_hands:por la ayuda para resolver problemas en el desarrollo de este paquete y en el armado de los tutoriales.

Para más información sobre sus actividades, les recomiendo seguir a [MetaDocencia](https://www.metadocencia.org/)
