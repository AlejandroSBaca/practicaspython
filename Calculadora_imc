#Se imprime un mensaje en pantalla indicandole al usuario en que consiste el programa
print("Este programa le mostrará su Indice de Masa Corporal, de acuerdo a la escala de la Organizaciòn Mundial de la Salud")

#Usamos un ciclo while para la validacion de datos. Si los datos ingresados son correctos continua, sino, imprime un mensaje en pantalla indicando el error.
while True:
       nombre =(input("Introduzca su nombre, por favor "))
       if nombre. isalpha(): #El ciclo if nos ayuda a validar si el dato es alfanumerico con el comando isalpha():
        break 
       else:
        print("Lo siento, ingrese un dato valido. Intentelo de nuevo.")
        
#Usamos la misma iteracion para todos los datos de tipo numerico (edad, peso, altura), validando si son correctos. En caso contrario, se repite el proceso. 
while True:
     try:
         edad= int(input("Introduzca su edad "))
         break
     except:
         ValueError
         print("Lo siento, ingrese un dato valido. Intentelo de nuevo ")
         
while True:
    try:
        peso= float(input("introduzca su peso en Kilogramos "))
        break
    except:
        ValueError
        print("Lo siento, ingrese un dato valido. Intentelo de nuevo")
  
while True:
    try:
        altura= float(input("Introduzca su altura en en metros "))
        break
    except:
        ValueError 
        print("Lo siento, ingrese un dato valido. Intentelo de nuevo")
        
 #Calculamos el Indice de Masa Corporal, usando la funcion round para redondear las cifras a numeros enteros     
imc= round(peso/altura**2)

#usamos una estructura de control condicional if-elif, para dar flujo a cada una de las condiciones. Si alguna de las condiciones es correcta, si imprime un mensaje en pantalla.
if imc >=0 and imc <=15.99:
    print(str(nombre) +",usted tiene " + str(edad) + " años y su IMC es de "+ str(imc) +".Padece de delgadez severa")
elif imc >= 16.0 and imc <=18.4:
     print(str(nombre) +",usted tiene " + str(edad) + " años y su IMC es de "+ str(imc) +".Usted es delgado")   
elif imc >= 18.5 and imc <=24.9:
     print(str(nombre) +",usted tiene " + str(edad) + " años y su IMC es de "+ str(imc) +".Usted tiene un peso saludable")
elif imc >= 25.0 and imc <=29.9:
    print(str(nombre) +",usted tiene " + str(edad) + " años y su IMC es de"+ str(imc) +".Usted padece sobrepeso")
elif imc >= 30.0 and imc <= 34.9:
    print(str(nombre) +",usted tiene " + str(edad) + " años y su IMC es de "+ str(imc) +".Usted padece Obesidad") 
elif imc >35:
    print(str(nombre) +",usted tiene " + str(edad) + " años y su IMC es de "+ str(imc) +".Usted padece Obesidad Morbida")
    
 #Fin del programa, solicitando al usuario que pulse una tecla para salir.  
input("Pulse cualquier tecla para salir... ")
 
   
    
    
    
    
          
        
        
        

 
