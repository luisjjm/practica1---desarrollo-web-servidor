Hola 
Esta practica consta de un HTML y un PHP.
Se utiliza el metodo GET para enviar variables dentro de una URL.

En la URL:
? 	//query string
num1=0 	//primera variable
&	//separacion
num2=0	//segunda variable


En PHP
recibe la variable con:
$_GET["nombre de la variable"]

//El nombre de la variable corresponde al atributo name del input HTML.

Como las variables son vistas desde la URL es recomendable no enviar datos sensibles con este metodo. 
