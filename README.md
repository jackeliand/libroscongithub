# LIBROS EN GITHUB

---
**Impartido por Alí González**

*Apuntes del taller. Octubre 5, 2019*

*Daniel M. Olivera* daniel.m.olivera@gmail.com


[Para ver la presentación](http://bit.do/librosengithub)


---


## Sobre el enfoque de libros en Git

Edición contributiva como "un documento vivo" (por open source)
Github, es, en si, un control de versiones. Sus ventajas es acerca de que el código siempre está disponible y visible. Además, permite la colaboración (incluso entre pares que no se conocen). Además cualquiera puede abris proyectos disponibles para todos.

Una de las cuestiones que no hemos tenido en cuenta sobre un hackatón para la gente de humanidades es cómo es que se forma una comunidad, con objetivos claros, acciones que llegan a algun lado y en tiempo corto.

También hemos menospreciado la relación entre humanistas e ingenieros en cuanto a cómo se pueden combinar en proyectos públicos que tengan incidencia social.

Entre los desarrolladores, no importa tanto dónde estudiaste o qué haces, sino está **orientado a resultados**. Es decir, importa más que está uno haciendo y si puede uno colaborar en un proyecto. Esto también contrasta con humanidades.

La idea es tener libros vivos, abiertos y libres. Que recojan los aprendizajes continuamente, que dejen de tener un autor único, y que se pueda distribuir.

La ventaja de los libros open source es que podemos saber quien modificó o compartió por medio de copleft.




## Uso de git para edición

En este caso, Git se mantiene como un *editor* o como un *asistente de editor* ya que permite controlar las versiones y decidir sobre los cambios.

Este enfoque lo que busca es transmitir conocimiento. Sin preocuparse sobre el diseño, formato o cómo llega este conocimiento.

**Tecnología cívica** apareció durante el gobierno de Obama. Así pasó con healthcare.gov

El enfoque es sobre dejar de pensar en el autor como *la máxima autoridad* en cuanto al texto. La idea es crear comunidad y de allí al texto.

En cuanto a los **fork**, la idea es tener una copia de cierto repositorio (y que se mantiene un link hacia el bueno). La idea es que el fork sea una copia **modificada**. Si no se modifica, solo sería una copia *muerta*. 

Los **commit** deben ser lo suficientemente largos para ser significativos (no solo una coma), pero tampoco es una buena práctica modificar muchos archivos en bloque en un solo commit.  Esto es porque si hay un archivo cuyo cambio está mal, se tendría que rechazar *todo el bloque*.


## Sobre el licenciamiento

Un problema es que son textos *con varios autores*. ¿Cómo podemos coordinar a varias personas en un solo proyecto?

El código de computadora, en México, está dentro de las *obras de arte*. ESto está chafa porque la modificación del código (por muy pequeña que sea) está violando detechos de autor.

Por ello se requiere que tengamos una licencia que *abra* el código a su modificación y distribución. (Checar, Open Data Handbook en la presentación).

Lo revolucionario de esto es que el valor ya no está en el código en sí. Sino que es **libre y para todos**. Solo se requiere conocimiento para acceder al código.

Filosóficamente, cambia la generación de valor y que el conocimiento sea para todos. Se genera dinero del conocimiento (y no solo *desde la licencia*)

## Colaboración

GitHub permite flexibilidad para que cada equipo tenga su flujo de trabajo. Sin embargo, la colaboración se puede dar por: mostrar o discutir problemas (**issues**), contribuir con un cambio (**commit**), o propuestas de cambios, resolución de problemas o mejoras, sujetas a evaluación por parte del que inició el proyecto (**pull request**).

En los *issues* me lo puedo asignar a mi mismo para resolverlo y mandar un *commit* que resuelva el problema. O cualquier persona de la comunidad, igual puede marcar un *issue*, discutirlo o asignarse la solución.
 
En cuanto a los *pull request* son pedidos de cambios ya hechos sobre el código o texto. Todo mundo puede ver qué cambio se aceptó o rechazó y opinar sobre el cambio.

La idea de los *commits* es tener cambios chicos como unidades. Es una unidad mínima de trabajo.

## Markdown

Es un lenguaje de marcado sencillo el cual tiene una sintaxis muy sencilla.

 - Títulos (según nivel): iniciar con #, ##, ###
 - Links: [Link a Google](www.google.com.mx)
 - Negritas: abrir y cerrar con dos asteriscos **negrita**
 - Itálicas: abrir y cerrar con un astetisco *itálica*
 - Las negritas e itálicas son tambien con guiones bajos _italicas_
 - Se pueden conbinar negritas e italicas _**negrita e italica**_
 - Listas no ordenadas: Al inicio de línea, un espacio y guión
 - Listas ordenadas: Al inicio de línea, espacio + número + punto
 - Imagen: como el link pero con un ! antes (alt text entre corchetes)

## Uso del repositorio GitHub

 - Creamos un repositorio nuevo
 - Agregamos una licencia diferente (para textos) en LICENCE.md
 - Publicamos en master branch
 - Creamos una organización (es bueno por si somos activistas)
 - Hicimos fork
 - Unimos algunas branch

**Estuvo bueno**
