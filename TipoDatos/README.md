Tipos de datos
Para poder trabajar con los datos o con informacion, cada dato tiene un tipo predeterminado, estos tipos ayudan a mejorar los procesos los cuales se estan hacinedo

-Numericos
    -Entero
    -Flotante
    -Complejo
-Diccionarios
-Booleanos
-Set
-Tipos de secuencia
    -Una cadena de texto
    -Lista
    -Tupla

En caso que tengamos una variable la cual desconozcamos, podemos usar la funcion de python **type** y esta nos retornara de que tipo es

```python
x = 10
print(type(x))
# <class 'int'>

x = "Hola mundo"
print(type(x))
# <class 'str'>

x = 3.14
print(type(x))
# <class 'float'>

x = False
print(type(x))
# <class 'bool'>
```

Tambien en caso de ser necesario se puede usar una pista para poder definir de que tipo sera la variable, aunque no es una cadena de fuerza, igual si se cambia el valor no afectara nada a el valor final.

```python
x:str = "Hola mundo"
print(type(x))
# <class 'str'>
```

Cuando se trabaja con cadenas de texto se pueden cocatenar para asi poder para asi poder tener una en total
```python

miGrupo = "Nombre_de_banda"
otroGrupo = " Guitarra"

print("El nombre de mi grupo es: " + miGrupo , otroGrupo)
# Nombre_de_banda mi cabeza
```

Hay un error comun cuando se esta trabajando con cadenas y numeros ya que se tiene lo siguiente:

```python
numero1 = "1"
numero2 = "2"
print(numero1 + numero2)
# 12
```
Se esperaria que la respuesta fuera 3, pero el problema es que las variables con las cuales estamos trabajando son de formato string, lo cual en vez de sumarse se concatenan, por lo cual se buscarian ya sea redefinirlas o hacer el cambio a tipo numerico

```python
numero1 = "1"
numero2 = "2"
print(int(numero1) + int(numero2))
#3
```

En el momento en el cual estemos trabajando con valores booleanos se tienen dos **False** en caso que sea false y **True** cuando sea verdadero, esto ayuda en caso de que estemos haciendo dentro de una variable una validacion o una operacion logica como determina si un numero es mayor que otro

```python

miVariable = 3 < 2
print(miVariable)
# False
```

Esto nos ayuda para poder implementar funciones las cuales nos ayudan a validar funcionamientos como lo seria un **if**

```python
miVariable = 2 < 3
if miVariable:
    print(miVariable)
```
