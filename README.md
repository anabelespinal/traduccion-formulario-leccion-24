****

#TRADUCIENDO UN FORMULARIO

######Nuestro formulario estaba en ingles y se veía así:

![leccion 24](http://i63.tinypic.com/2mwxic0.jpg)

+  Nos piden cambiar el idioma del formulario.
+ Tambien nos piden que modifiquemos el idioma, sin tener que hacer algun cambio e 	el HTML.

#### Para esto tenemos que seguir los siguientes pasos:  

+ Debemos cambiar el titulo, utilizaremos un **'document.getElementById'**, luego       agragaremos un innetHTML para agregar el texto que queremos.
+ Luego tendremos que cambiar el placeholder de los input..
	utilizaremos un **'getElementsByClassName'** con el nombre del class de los input, y como esto te devuelve un array colocaremos '[ ]' con el indice del primer input y luego el segundo.
+ Para cambiar el placeholder **'document.getElementsByClassName("")[ ].placeholder 	= 'new text'**;.
+ Por ultimo tenemos que cambiar el texto del boton, se realiza un procedimiento    	similar, pero utilizarems en 'querySelector' con el nombre del tag y agrgamos un  
	**'innerHTML'** para cambiar el texto.
	
	
##### Con todos estos cambios sin modiificar el HTML, nuestro nuevo formulario se verá asi:


![new form](http://i68.tinypic.com/11j81ky.jpg)


****