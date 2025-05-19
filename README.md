//Diapositiva 1-5 (HTML) "Find the bug in the code"

Hemos identificado etiquetas HTML mal cerradas (</p>) y en el caso de (/div) cerradas en una línea incorrecta.

Una de las cosas que nos repite Alex hasta la saciedad es que no seamos "guarretes" con el código. Vemos un texto largo e interpreto que no hay saltos de línea.

Etiquetas cerradas en diferentes líneas de forma innecesaria. <h2> es una etiqueta de una sola línea, no debería abrir y cerrar en líneas diferentes.

Etiquetas <h2> y <p> mezcladas en un mismo nivel sin tener estructura clara.

//Diapositiva 6-7 (Javascript)  

Vemos que calc no dice que me va a calcular.

nums y total son demasiados genéricos, ya que no me explican que representan exactamente. Cómo diría el profe ¿números de qué? ¿total de qué?

//Diapositiva 8-13 (JavaScript) "Variable global"

result está fuera de las funciones, así que se considera global (si he apuntado bien en los apuntes) así que, cualquier función puede cambiarla, sin importar el orden.

Se debe cambiar function accumulate por let result, ya que accumulate depende de que result tenga un valor adecuado puesto con anterioridad. Si se cambia el orden, el resultado también cambia.

//Diapositivas 14-16 (JavaScript) Condicionales super mega anidades

if al cubo. Cada if dentro de otro if, marea a los ojos. En la clase del miércoles 14/05 nos dijeron que cuanto más se anide más dificil es seguir una lógica.

Agobia ver tanta sangría, visualmente dificulta el mantenimiento.

Si hay que evaluar cuesta verlo, y ni te cuento si más tarde tengo que modificarlo. Seguro que lo rompo a lo bestia.

Así que vemos que las condiciones lo dejan de forma clara y ordenada, evitamos usar else, porque tengo return, por lo tanto al devolver con return el resto de código no se ejecutará.