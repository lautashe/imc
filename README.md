def cat_bmi (bmi):

    si bmi <19,5: r = "Tiene bajo peso"

    elif bmi <= 24.9: r = "Estás dentro del rango de peso saludable"

    elif bmi <= 29.9: r = "Tienes sobrepeso"

    elif bmi <= 34.9: r = "Tiene obesidad tipo 1"

    elif bmi <= 39.9: r = "Tiene obesidad tipo 2"

    else: r = "Tienes obesidad tipo 3"

    volver r

def imprimir (a):

    print (a ["Nombre"]. superior () + "" + a ["Apellido"]. superior () + "" + a ["Edad"] + "" + a ["Peso"] + "" + a ["Altura"] + "" + a ["Dirección"]. superior () + "" + a ["Teléfono"] + "" + resultado. superior () + "" + str (a ["IMC" ]))

print ("bienvenido al programa..")

person = {"Nombre": "",

        "Apellido":"",

        "Edad": 0,

        "Peso": 0,

        "Altura": 0,

        "Dirección":"",

        "Teléfono":""}

para x en persona:

     persona [x] = input (f "escribe tu {x}:")

bmi = round (float (person ['Weight']) / ((float (person ['Height'])) ** 2), 2)

persona ["BMI"] = bmi

resultado = "fastidio"

resultado = cat_bmi (bmi)

imprimir (persona)
