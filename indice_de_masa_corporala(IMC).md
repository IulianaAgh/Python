# Python
height = input("Introdu inaltimea ta(m**m): ")
weight = input("Introdu greutatea ta(kg): ")

height_float=float(height)
BMI=float(weight)/(height_float**2)
print(BMI)

if BMI<=18.49:
    print("Subponderal")
elif BMI>=18.50 and BMI<=24.99:
    print("Greutate normala")
elif BMI>=25 and BMI<=29.99:
    print("supraponderal")
elif BMI>=30 and BMI<=34.99:
    print("Obezitate(gradul I)")
elif BMI>=35 and BMI<=39.99:
    print("Obezitate(gradul II)")
else:
    print("Obezitate morbida")
