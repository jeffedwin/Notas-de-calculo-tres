# Recomendaciones.


## Día de trabajo con Lyx y GitHub Desktop

- I. En **GitHub Desktop**
  1. *Fetch* (Se verifica si hay modificaciones "en la nube")
  2. *Pull* (Si sí hay modificaciones "en la nube", se descargan)
  3. (Tal vez arreglar conflictos...)
- II. En **LyX**
  1. Editar y/o crear archivos.
  2. Guardar modificaciones.
- III. En **GitHub Desktop**
  1. (Si se crearon archivos nuevos, estos se "palomean" automáticamente para ser enviados, pero si no se quieren enviar, pues simplemente "despalomearlos")
  2. *Commit* (con mensaje de descripción breve sobre las modificaciones hechas durante la edición)
  3. (Se pueden hacer varios *Commit* en una sesión de trabajo, puede ser útil para "guardar" varias fases de avance en el trabajo...)
  4. *Push* (Se envían las modificaciones "a la nube")
  5. (En raras ocasiones cuando un colaborador hace un *Push* antes y se detecta algún tipo de conflicto "en la nube", no es posible hacer *Push*. Para solucionarlo, se tienen que hacer los pasos I. 1, 2 y 3, y después III. 2 y 4)


## Sobre archivos **LyX**

Recomiendo crear un archivo *master* que contenga sólo la carátula del documento, el índice, la bibliografía, y las referencias a otros archivos "hijos" *section* (o *chapter*) que contengan las partes correspondientes.

Para añadir documentos **LyX** "hijos" ir a menú *insert* $\rightarrow$ *file* $\rightarrow$ *child document*. Y luego seleccionar el archivo adecuado y la opción *Include* en la ventana de diálogo.


## Sobre archivos de imágenes

El sistema de control de versiones **Git** no tiene problema con recibir archivos imagen binarios como aquellos con extensión JPG, PNG, GIF, etc.

Sin embargo, se recomienda usar archivos de imagen vectorial (internamente son de texto), como aquellos con extensión SVG, EPS, PDF, etc. Además, el documento PDF que generen será de mejor calidad y de menor tamaño en *megabytes*.


## Sobre el documento PDF generado

Pueden añadir el archivo PDF que vayan generando durante su trabajo al control de versiones o no... lo dejo a su criterio...


## Sobre este archivo

Este archivo de texto está en formato *markdown*, así que se ve mejor con un visualizador adecuado para este formato, como la plataforma *web* **GitHub**. No sé si la aplicación **GitHub Desktop** pueda visualizar este archivo correctamente...
