# Repo-Reto-2
# Integrantes y tema
Integrantes: Raul Ferris, Christian Vázquez y Andrés Gimeno
Tema: Variables, tipos y strings

# 1. Pedimos los datos al usuario
nombre = input("Dime tu nombre: ")
edad_texto = input("Dime tu edad: ")

# 2. Convertimos la edad de texto (str) a número entero (int)
edad_numero = int(edad_texto)

# 3. Mostramos los tipos de datos para demostrar el cambio
print(f"Tipo de 'nombre': {type(nombre)}")
print(f"Tipo de 'edad_texto' (lo que devuelve input): {type(edad_texto)}")
print(f"Tipo de 'edad_numero' (después de convertir): {type(edad_numero)}")

# 4. Mensaje formateado usando f-strings, .upper() y len()
print(f"Hola {nombre.upper()}, tienes {edad_numero} años y tu nombre tiene {len(nombre)} letras.")

# Pregunta para la clase
"Si borramos la línea donde convertimos la edad con int(), y al final intentamos hacer print(edad_texto * 2) habiendo introducido un '20'... ¿Qué creéis que saldrá por pantalla? ¿Dará un error, saldrá '40' o saldrá otra cosa?

## Cómo ejecutarlo
Ejecutar el archivo principal desde la terminal:
`python main.py`

## Resultado esperado
Dime tu nombre: Andres
Dime tu edad: 22

Tipo de 'nombre': <class 'str'>
Tipo de 'edad_texto' (lo que devuelve input): <class 'str'>
Tipo de 'edad_numero' (después de convertir): <class 'int'>

Hola ANDRES, tienes 22 años y tu nombre tiene 6 letras.

# Error típico
Olvidar poner int() cuando se le pide un número al usuario.