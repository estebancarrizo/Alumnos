# Alumnos
Lista de alumnos                                                

Aca vamos a colocar a todos los alumnos de la materia electronica microcontrolada

Algunas consideraciones previas.                               
a) Siempre al iniciar git verifique su usuario (user.name) y su email (user.email).
$ git config --list

  y en caso de no estar configurado o ser distinto del que esperaba, agregue los valores correctos 

$ git config --global user.name '[su nombre]'
$ git config --global user.email '[su email]'

b) Si estuvo trabajando con varios mail en git anteriormente y le da error al trabajar con git,
   verifique las credenciales de windows y borre las credenciales que no utilizara.

   

los pasos a seguir son:        

1) Clono el repositorio con git bash.                                        
$ git clone https://github.com/EMTSTISPC/Alumnos.git                          

2) Edito la lista de alumnos agregandome. 

3) confirmo los cambios.
$ git add 'Lista de Alumnos.xlsx'
$ git commit -m 'Se agrega el [fila] Alumno al archivo'

4) subo los cambios al repo remoto
$ git push https://github.com/EMTSTISPC/Alumnos.git





