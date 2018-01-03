# Kata FizzBuzz

Descripción de la kata: http://www.solveet.com/exercises/Kata-FizzBuzz/11

N.B.: gracias a los repos de https://github.com/12meses12katas y https://github.com/SoftwareCraftersMadrid por la inspiración ;-)


## Objetivos
* El objetivo de este primer coding dojo es familiarizarse con la técnica de TDD (Test-Driven Development), practicando su ciclo y entendiendo sus ventajas.
* Por otra parte, este coding dojo se organiza para **APRENDER** en un entorno seguro, donde podamos probar cosas que en nuestro día a día no nos permita nuestro entorno (puede ser una determinada técnica, o una librería, atajos del IDE, un nuevo concepto, pair programming, etc.).
* El objetivo **NO** es acabar la kata, ni crear el mejor código del mundo.


## Requisitos
Es necesario venir con tu portátil, tu IDE favorito instalado y con un entorno básico ya configurado. Para esto último podéis usar los esqueletos existentes en el repositorio www.github.com/CraftersEntrePercebes/esqueletos-katas (a continuación explicamos cómo usarlos).

## Cómo montar el entorno
Evidentemente puedes hacerlo como quieras, pero de cara a poder compartir tu código con otras personas, te recomendamos los siguientes pasos:
1. Haz un fork de este repositorio (ver botón "Fork" en la esquina superior derecha de GitHub).
2. Clónate el repositorio en local de esta kata, ya sea con tu cliente de Git favorito o desde terminal con `git clone git@github.com:<TuCuenta>/FizzBuzz.git`
3. Crea una carpeta con tu nombre o nick.
4. Si no quieres prepararlo por tu cuenta, clónate el repositorio de esqueletos: `git clone git@github.com:CraftersEntrePercebes/EsqueletosKatas.git`
5. Copia el esqueleto concreto que te interese


## Reglas
* Se deberá **trabajar en parejas**. Si hubier un número impar de personas, se pondrá en trieja. Lo ideal sería crear parejas combinando gente con más experiencia en general (ya sea en testing o en desarrollo de software) con gente con menos.
* Deberá trabajarse obligatoriamente con TDD (Test-Driven Development).
* Se realizarán varias iteraciones, pudiéndose cambiar de pareja si así se desea (de hecho sería lo ideal).
* Tras cada iteración, recordad dar las gracias a vuestra pareja por la sesión :-)


## Qué NO debes esperar de este coding dojo
* No es una clase magistral ni un curso, ya que lo aprendas depende principalmente de ti. Habrá dos facilitadores para dar unas primeras explicaciones sobre la técnica de TDD, proponer un ejercicio práctico (la kata) y crear el contexto adecuado para que se dé el aprendizaje.
* No es un lugar donde aprender un nuevo lenguaje. Al menos una de las dos personas de la pareja debe encontrarse cómodo con el lenguaje de programación elegido.
* No es un lugar donde aprender a configurar un entorno de desarrollo.


## Cómo comenzar
1. **Encontrar una pareja/trieja**.
2. **Decidir** qué **lenguaje de programación** vais a usar y en qué portátil.
3. **Lee cuidadosamente el problema abajo descrito** (o aquí: ) y en caso de tener alguna duda, consultad con los facilitadores.


## Descripción de la kata

Imagínate el siguiente escenario. Tienes 11 años y en los últimos 5 minutos del final de la lección, tu profesor de matemáticas decide hacer la clase mas divertida, introduciendo un juego. El explica que irá señalando a cada compañero de clase en orden y preguntándole el siguiente número de la secuencia, comenzando por el número uno. La parte divertida es que, si el número es divisible por 3, tienes que decir "Fizz" en vez del número. Y si es divisible por 5, debes decir "Buzz".

Las matemáticas no es tu fuerte y tienes miedo de que te llegue el turno y no sepas qué decir. Así que, con el fin de evitar la vergüenza delante de toda la clase, tienes que obtener la lista completa impresa para saber qué decir. Tu clase tiene unos 33 alumnos y se pueden llegar a hacer unas tres rondas antes de que suene el timbre para el recreo. La siguiente clase de matemáticas es el jueves. ¡Codifícalo! :)

Escribe un programa que imprima los números del 1 al 100, pero aplicando las siguientes normas:

* Devuelve Fizz si el número es divisible por 3.
* Devuelve Buzz si el número es divisible por 5.
* Devuelve FizzBuzz si el número es divisible por 3 y por 5.

**Salida de ejemplo**
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
... etc hasta el 100
```

### Test cases

| Input | Resultado |
|-------|-----------|
| 1     | 1         |
| 2     | 2         |
| 3     | Fizz      |
| 4     | 4         |
| 5     | Buzz      |
| 6     | Fizz      |
| 10    | Buzz      |
| 15    | FizzBuzz  |



### Bonus track
* Devolver “Woof” si un número es divisible por 7
* Devolver “Fizz” si es divisible por 3 o si incluye un 3 en el número
* Devolver “Buzz” si es divisible por 5 o si incluye un 5 en el número
* Un único nivel de indentación por método
* Sin condicionales (if, while, etc.)
* Sin bucles (for, while, foreach, etc.)
* No más de 4 líneas por método.    
