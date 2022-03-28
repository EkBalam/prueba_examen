# prueba_examen
Escriba un programa que pregunte por la edad, estaura y si hay tarjeta de crédito o no (usando las palarbas si y no en minusculas y sin acentos)

La salida debe ser, si no puede entrar

LLama a sus papas

si puede entrar 

Puedes entrar diviertete

Cuide que el texto sea tal cual el 
```python

edad = int( input('Teclea tu edad: ') )
estatura = float( input('Dime tu estatura: ') )
credito = input('Tienes tarjeta de credito, si o no: ')

if (edad < 18 or edad > 36) or estatura < 1.65 or credito == 'no':
    print("LLama a sus papas")
else:
    print("Puedes entrar diviertete")
```

