# jean.py
PRACTICA DE PYTHON DE JEAN LUCA ALIAS CARBONCITO
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
4. 2. Tipos de Datos
Es la forma en que la computadora clasifica la información:

Texto (str): Cadenas de caracteres (ej. "Hola mundo").

Números Enteros (int): Números sin decimales (ej. 42).

Números Decimales (float): Números con punto decimal (ej. 3.14).

Booleanos (bool): Valores de Verdadero (True) o Falso (False).

3. Condicionales (Decisiones)
Permiten que tu programa tome caminos diferentes según la situación. Funcionan como un "Si pasa esto, haz A; si pasa lo otro, haz B".

edad = 20

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
    
4. Bucles o Ciclos (Repetición)
Sirven para automatizar tareas repetitivas sin tener que escribir el mismo código varias veces.

# Imprime los números del 0 al 4
for i in range(5):
    print(f"Número: {i}")
    
5. Funciones
Son pequeños bloques de código reutilizables. Creas una receta una sola vez y la puedes invocar las veces que necesites.

def saludar(nombre):
    return f"¡Hola, {nombre}! Bienvenido a la programación."

# Uso de la función
mensaje = saludar("Python")
print(mensaje)
🛠️ Primeros Pasos Sugeridos
Instalación: Descarga e instala Python desde su sitio web oficial.

Editor de Código: Utiliza un editor amigable como Visual Studio Code.

¡Prueba tu código! Crea un archivo llamado main.py, escribe tu primer print("¡Hola mundo!") y ejecútalo en tu terminal.
