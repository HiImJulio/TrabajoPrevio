#NORMAS DEL PROYECTO 

Normas generales a la hora de implementar: 
 
A la hora de crear código, deberíamos seguir las siguientes pautas: 

Estructura del código 

1. La gran mayoría del peso de código debería recaer en funciones. El objetivo es poder crear funciones que nos permitan abstraer el 
código hasta cierto punto y que nos permitan reutilizar código con facilidad. 

a. A la hora de crear funciones , es conveniente darles una descripción en la cabecera, compuesta de una descripción general, definición de
los inputs y definición de los outputs.

b. Es recomendable crear funciones pequeñas y específicas. Si puede ser, con menos de 20-25 líneas y 3-4 inputs, a costa de más 
subfunciones. De esta forma el código será más limpio y fácil de reutilizar cuanto más avancemos. 


Distribución del proyecto 
 
2. El código debe estar organizado en módulos. En vez de definir las funciones en nuestros notebook, deberíamos definir archivos .py
en el que definamos conjuntos de funciones e importarlos en los notebook. De esta forma, los programas principales serán legibles
y pequeños. 

a. Cada .py debe de contener un grupo de funciones con una relación fuerte entre ellas, que quede claro el uso 
concreto de esa librería. Al hacer esto, podemos trabajar en varias partes del código a la vez con menos preocupación por
pisarnos el código (sobrescribirnos cosas) debido a la separación de código en módulos bien definidos.

b. Los archivos principales en los que ejecutaremos nestros programas serán notebooks o archivos .ipynb 


Problemas al implementar

3. La prioridad es que el código funcione y sea muy claro. Optimizar el código está bien, pero si no se consigue
no se consigue xd (aunque ya que hacemos esto para aprender, podríamos esforzarnos más en ello, ya veremos). 
