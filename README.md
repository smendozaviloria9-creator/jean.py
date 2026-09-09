# jean.py
PRACTICA DE PYTHON DE JEAN LUCA ALIAS CARBONCITO

¡Bienvenido a este repositorio introductorio! Si estás dando tus primeros pasos en el mundo de la programación, **Python** es el lenguaje ideal para empezar. Su sintaxis es limpia, legible y se parece mucho al inglés cotidiano, lo que te permite concentrarte en entrenar tu lógica en lugar de luchar con códigos complejos.

---

## 🐍 ¿Qué es exactamente Python y por qué deberías aprenderlo?

Creado por Guido van Rossum y lanzado por primera vez en 1991, **Python** es un lenguaje de programación de alto nivel, interpretado y de propósito general. 

Para entenderlo de forma sencilla, imagina que hablar con una computadora es como darle instrucciones a un asistente que no entiende modismos ni metáforas:
- **De alto nivel:** Significa que el lenguaje está diseñado para que los humanos lo entendamos y escribamos fácilmente, alejándose de los códigos binarios o de bajo nivel que maneja directamente el procesador de la computadora.
- **Interpretado:** No necesitas "compilar" o transformar todo tu código en un programa ejecutable antes de probarlo. Un programa llamado *intérprete* lee tu código y lo ejecuta línea por línea al instante, lo cual hace que encontrar y corregir errores (depurar) sea muy rápido y amigable para quienes empiezan.
- **De propósito general:** No está atado a una sola cosa. Con Python puedes desde automatizar tareas aburridas de tu computadora hasta construir páginas web, analizar millones de datos o crear modelos de Inteligencia Artificial.

### Ventajas clave para quienes empiezan:
1. **Sintaxis limpia:** Usa espacios y sangrías obligatorias, lo que obliga a que tu código siempre luzca ordenado y sea fácil de leer por ti y por otros.
2. **Gran comunidad:** Al ser uno de los lenguajes más populares del mundo, si te atoras en un problema, es 100% seguro que alguien más ya pasó por ahí y la solución está a un clic de distancia en internet.
3. **Curva de aprendizaje amigable:** Te permite ver resultados funcionales con muy pocas líneas de código desde el primer día.

---

## 📚 Conceptos Básicos de Programación

Para empezar a programar en Python, es fundamental comprender estos cinco cimientos:

### 1. Variables
Imagina que son **cajitas o etiquetas** donde guardas información para usarla y modificarla después en tu programa.
```python
nombre = "Sebastián"
edad = 25
```

### 2. Tipos de Datos
Es la forma en que la computadora clasifica la información:
- **Texto (`str`):** Cadenas de caracteres (ej. `"Hola mundo"`).
- **Números Enteros (`int`):** Números sin decimales (ej. `42`).
- **Números Decimales (`float`):** Números con punto decimal (ej. `3.14`).
- **Booleanos (`bool`):** Valores de Verdadero (`True`) o Falso (`False`).

### 3. Condicionales (Decisiones)
Permiten que tu programa tome caminos diferentes según la situación. Funcionan como un *"Si pasa esto, haz A; si pasa lo otro, haz B"*.
```python
edad = 20

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
```

### 4. Bucles o Ciclos (Repetición)
Sirven para automatizar tareas repetitivas sin tener que escribir el mismo código varias veces.
```python
# Imprime los números del 0 al 4
for i in range(5):
    print(f"Número: {i}")
```

### 5. Funciones
Son pequeños bloques de código reutilizables. Creas una receta una sola vez y la puedes invocar las veces que necesites.
```python
def saludar(nombre):
    return f"¡Hola, {nombre}! Bienvenido a la programación."

# Uso de la función
mensaje = saludar("Python")
print(mensaje)
```

---

## 📝 Ejercicios Prácticos para Principiantes

Pon a prueba lo que has aprendido resolviendo estos 5 ejercicios:

#### Ejercicio 1: El saludo personalizado (Variables y Tipos de Datos)
* **Objetivo:** Crear variables para guardar información y mostrarla combinada en pantalla.
* **Instrucción:** Declara una variable para tu nombre (`nombre`), otra para tu edad (`edad`) y otra para tu ciudad de residencia (`ciudad`). Luego, usa la función `print()` para mostrar una oración completa que los una.

#### Ejercicio 2: ¿Mayor de edad? (Condicionales)
* **Objetivo:** Tomar decisiones lógicas usando `if` y `else`.
* **Instrucción:** Crea una variable llamada `edad` con un número. Escribe un programa que evalúe si esa edad es mayor o igual a 18 e imprima un mensaje acorde.

#### Ejercicio 3: La tabla de multiplicar (Bucles / Ciclos)
* **Objetivo:** Usar un bucle `for` para repetir una tarea automáticamente.
* **Instrucción:** Escribe un bucle que imprima en la consola la tabla de multiplicar del número 5 (del 1 al 10).

#### Ejercicio 4: Calculadora de área (Funciones)
* **Objetivo:** Crear un bloque de código reutilizable que reciba datos y devuelva un resultado.
* **Instrucción:** Crea una función llamada `calcular_area_rectangulo(base, altura)` que multiplique ambos valores y devuelva el resultado del área.

#### Ejercicio 5: Clasificador de números (Condicionales anidados)
* **Objetivo:** Evaluar múltiples escenarios con condiciones.
* **Instrucción:** Crea una variable con un número entero. Escribe un programa que determine si el número es **positivo**, **negativo** o **igual a cero**.

---

## 🛠️ Primeros Pasos Sugeridos

1. **Instalación:** Descarga e instala Python desde su [sitio web oficial](https://www.python.org/).
2. **Editor de Código:** Utiliza un editor amigable como *Visual Studio Code*.
3. **¡Prueba tu código!** Crea un archivo llamado `main.py`, escribe tu primer `print("¡Hola mundo!")` y ejecútalo en tu terminal.
