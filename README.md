#Abril 19

##Ejercicios Practicos

- Ejercicio 1.
Instruccion que retorna el numero de procesos en ejecucion en un sistema operativo.

```
ps -A | wc -l	
```

- Ejercicio 2.
Instruccion que imprime el valor de elevar 2 a la potencia 4, por medio del operador "**" .

```
echo $(( 2 ** 4 ))
```

- Ejercicio 3.
Instruccion que retorna el numero de procesos en ejecucion en un sistema operativo, por medio del comando tail .

```
ps -A | tail -n +2 | wc -l
```

