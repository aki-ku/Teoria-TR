# Matemàtiques en la programació
# Teoria
Aquí us explicaré com es funciona el llenguatge python3
Abans de res per explicar-te és millor que descargueu Thonny o feu un compte en repl.it.
## La funció print()
Com  veieu el codi 1.py.
``` python3
print("Hola")
```
Aquesta funció ens permet mostrar qualsevol valor proporcionats com arguments. Els valors es separa amb espai i es terminara amb un salt de línia.

## La funció input()
Com veieu el codi 2.py
``` python3
dada = input ()
print(dada)  
```
Aquesta funció ens permet que l'usuari introdueixi una dada nova i després es valideixi

## Variables
Una variable és un nombre asignada a un valor que pot ser número, text, llistes, etc. També es pot variar al llarg del temps. Per saber quin tipus de variable es posem type() i ens dirà la classe. 
Com veieu el codi 3.py fins el codi 6.py

### Lletres (str)
3.py
``` python3
a = "Pep"
print(type(a)) 
```

### Número (int)
4.py
``` python3
a = 1
print(type(a))
```

### Llista (llist)
5.py
``` python3
a = [1,9]
print(type(a))
```

### Boleana (boal)
6.py
``` python3
a = True
print(type(a))
```

## Operacions matemàtiques
En la programació es igual que les matemàtiques ja que té suma, restes, multiplicacions,etc.
Com veiem el codi 7.py fins el codi 13.py

### Suma
La suma té el símbol de +
7.py
``` python3
a = 10
b = 5
c = a + b
print(c)
```

### Resta
La resta té el símbol de - 
8.py
``` python3
a = 10
b = 5
c = a - b
print(c)
```

### Multiplicació 
La multiplicació té el símbol de *
9.py
``` python3
a = 10
b = 5
c = a * b
print(c)
```

### Divisió
La divisió que ens dóna la forma decimal té el símbol de /
10.py
``` python3
a = 10
b = 5
c = a / b
print(c)
```

### Divisió
Ens dóna la forma enter té el símbol de //  
11.py
``` python3
a = 10
b = 5
c = a // b
print(c)
```

### Mòdul
El mòdul de la divisió és a dir el residu de la divisió té el símbol de %
12.py
``` python3
a = 10
b = 5
c = a % b
print(c)
```

### Exponent 
El exponent té el símbol **
13.py
``` python3
a = 10
b = 5
c = a ** b
print(c)
```

## Import 
Com veieu el codi 14.py
``` python3
import math
b = math.sqrt(4)
print(b)
```
És com una biblioteca on està emmagatzemat un munt de llibres. 

## Bucles 
En general, un bucle és una estructura de control que repeteix un bloc d'instruccions. Un bucle for és un bucle que repeteix el bloc d'instruccions un nombre predermint de vegades o fins una condició que poses.
Com veiem el codi 15.py i 16.py

### Bucles for
15.py
No compta l'últim número
``` python3
for i in range (0, 4):
 print(i)
```

### Bucle while
16.py
``` python3
cont = 0
while (cont != 2):
 cont = cont+1
 print(cont)
```

## Condicional
Com veiem el codi 17.py fins 19.py

### Condicional if…
17.py
Permet que el programa ejecuti quan cumpli una condició
``` python3
numero = int(input("Escriu un número positiu: "))
if numero < 0:
   print("He dit que escribis un número positiu!")
print("Ha escrit el número " + str(numero))
```

### Condicional if… else…
18.py
Permet que el programa ejecuti quan cumpli una condició i altres instruccions que no és compleix
``` python3
edad = int(input("Quants anys tens "))
if edad < 18:
   print("Menor d'edat")
else:
   print("Major d'edat")
```
### Condicional if… elif… else…
19.py
Permet que el programa ejecuti quan cumpli una condició o un altre amb diferent condició i altres instruccions que no és compleix
``` python3
edad = int(input("Quants anys tens "))
if edad < 18:
 print("Menor d'edat")
elif edad < 0:
 print("Niguna edat és negativa")
else:
 print("Major d'edat")
```

## Funció
Fer una cosa específica i ens divideix el nostre programa en parts més petites i quan creix el programa les funcions són més ordenades.
Com veiem el codi 20.py
```python3
def nom(name):
 print("Hola, " + name + ".)
nom('Paul')
```
