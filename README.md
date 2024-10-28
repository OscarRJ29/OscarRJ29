edad = int(input("Introduce tu edad: "))
clasificacion = input("Introduce la clasificación de la película (AA, A, B, B15, C, D): ").upper()

# Verificar si la persona puede ver la película según la clasificación
if clasificacion == "AA":
    print("¡Puedes ver esta película!")
elif clasificacion == "A":
    print("¡Puedes ver esta película!")
elif clasificacion == "B" and edad >= 12:
    print("¡Puedes ver esta película!")
elif clasificacion == "B15" and edad >= 15:
    print("¡Puedes ver esta película!")
elif clasificacion == "C" and edad >= 18:
    print("¡Puedes ver esta película!")
elif clasificacion == "D" and edad >= 18:
    print("¡Puedes ver esta película!")
else:
    print("Lo siento, no tienes la edad suficiente para ver esta película.")
