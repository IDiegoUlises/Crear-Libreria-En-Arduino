# Crear Libreria En Arduino

Crea una libreria del arduino notita la verdad que es lo mismo que crear una libreria en c++ y arduino esta basado en c++ se crea dos fichero con extension codigo.cpp y el otro no me acuerdo la extension es de la misma manera que se realiza una libreria en c++ luego se puede crear un archivo para cambiar de colores palabras por ejemplo "accion" creo el fichero para marcar la palabra "accion" de otro color  en el editor de texto del arduino luego todo se comprime en .zip luego en el arduino > incluir libreria > selecciona esa libreria y listo cualquier otra persona puede utilizar la libreria que has creado muy simple..  


nota: para crear la libreria se crea dos archivos con dos extenciones diferentes para programar codigo !no tengo idea porque se utiliza 2 archivos con diferentes extensiones cuando puedes crear la libreria solo con la necesidad de un archivo que contenga todas las funciones... pero de manera generalizado todas las librerias que e encontrado en arduino contiene 2 archivos debe ser porque es mejor ..

una de mi estimacion es que cuando llamas una libreria "libreria.h" ejecuta todo el codigo que tiene la libreria y por ejemplo puede modificar los valores de nuestra variables si se usan variables de mismo nombres y el otro archivo no estoy muy seguro pero estoy suponiendo para evitar que las variables con el mismo nombre se cambien porque se ejecutan de manera independiente del codigo principal es decir que se ejecuta 2 metodos loop y setup de manera independiente... para no generar conflictos del codigo o fallos...

Informacion sin CONFIRMAR Solo estimacion
ADD: Cuando llamas una libreria todo el codigo que tiene adentro de la libreria se ejecuta es decir si en la liberia crear una variable = 3  en tu codigo tendras esa variable creada para que alguien las utilize las debe llamar como una funcion como encender(); o como una funcion con parametros como encender(120); y la razon porque se crea un archivo "h." y el archivo "cp." es para que las variables que se encuentran el archivo "h." existan en el archivo "cp." estan definidas para que incluyas las librerias solo existan las variables del archivo "cp." porque muchas veces para nuestra libreria debemos crear variables que son inutil y ademas puede generar un conflicto si la persona intenta crear la misma variable que existe en la libreria.

Palabras De colores: Se crea un archivo con el nombre de cualquier palabra para que esa palabra en el editor de texto del arduino cambie de color como al color verde, esto es utilizado para diferenciar las palabras que se usan para una funcion.
