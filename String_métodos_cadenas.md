# ejercicios_Manipulación_de_Cadenas

STRING:

UPPER(): CONVIERTE EN MAYÚSCULAS TODAS LAS LETRAS DE UN STRING

LOWER(): PASA A MINÚSCULAS UN STRING

CAPITALIZE(): PONE EN MAYÚSCULA LA PRIMERA LETRA

COUNT(): CONTAR CUÁNTAS VECES APARECE UNA CADENA DE CARACTERES DENTRO DE UNA FRASE

FIND(): MUESTRA EL ÍNDICE O POSICIÓN DE UN CARACTER O UN TEXTO

ISDIGIT():BOOLEANO QUE NOS DICE SI EL VALOR INTRODUCIDO ES UN VALOR NUMÉRICO O NO

ISALUM():COMPRUEBA SI SON ALPHANUMÉRICOS

ISALPHA(): COMPRUEBA SI HAY SÓLO LETRA

SPLIT():SEPARA POR PALABRAS UTILIZANDO ESPACIOS

STRIP(): BORRA LOS ESPACIOS SOBRANTES AL PRINCIPIO O AL FINAL 

REPLACE(): CAMBIA UNA PALABRA O UNA LETRA POR OTRA

RFIND():HACE LO MISMO QUE FIND , REPRESENTA EL ÍNDICE DE UN CARACTER PERO CONTANDO DESDE ATRÁS, CON FIND CUENTA DESDE EL PRINCIPIO Y RFIND CUENTRA DESDE ATRÁS.


UPPER,LOWER,CAPITALIZE:

nombreUsuario=input("Introduce un nombre de Usuario: ")

print("El nombre es ", nombreUsuario.upper()) #CAROL

print("El nombre es ",nombreUsuario.lower()) #carol

print(nombreUsuario.capitalize()) #Carol


edad=input("Introduce la edad")


#devuelve true si introduzco números sino False

while(edad.isdigit()==Flase):

  print("Por favor, introduce un valor numérico")
  
  edad=input("Introduce la edad: ")
  
  
if(int(edad)<18):
  
  print("No puede pasar")
  
else:

  print("Puedes pasar")



UN RECURSO PARA VER DOCUMENTACIÓN DE CADENAS DE CARACTERES ES LA WEB pyspanishdoc.sourceforge.net/lib/string-methods.html
