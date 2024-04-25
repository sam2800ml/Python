Variables
Una variable permite almacenar informacion de forma temperal, puede ser ya sea numerica, booleana o de texto

```python

miVarible = "Hola desde python"
miVariableNumerica = 2

```
Una vez declarando el nombre de la variable se puede llamar desde otra funcion o puede ser usada despues para imprimirla en pantalla

```python

print(miVariable)
# Salida: Hola desde python
```

Con la funcion **print** se puede mostrar los valores en la consola, por lo cual es buena en caso de que sea necesario de mostrar un valor o un proceso el cual se esta realizando
Ademas cabe aclarar que la forma en la cual se ejecuta el codigo es de manera secuencial

- Con las variables tambien se pueden hacer operaciones matematicas tambien en caso de que sean cadenas de texto tambien se pueden unir para hacer una mas larga

```python
x=2
y=3
z=x+y
print(z) # imprime 5

texto1 = "Hola"
texto2 = "Mundo"
texto3 = texto1 + texto2
print(texto3) # Imprime "HolaMundo"
```
 
 -Todas estas variables se almacenan en una parte en nuestras computadoras, cuando queremos saber en que posicion de memoria esta se puede utilizar **id** 

 ```python
print(id(x))
#salida: 140704840272344
 ```
