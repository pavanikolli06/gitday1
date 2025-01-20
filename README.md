# THE LEAP YEAR CODE
year=int(input())
leap=False
if year%100==0 and year%400!=0:
    leap=False
elif year%4==0:
    leap=True
else:
    leap=False
print(leap)


# CONVERTING THE TEMPERATURE IN CELUSIUS TO FAHRENHEIT AND KELVIN


c=int(input("enter temperature in celsius:"))
F=c*(9/5)+32
K=273+c
print(f"temperature in Fahrenheit:{F}")
print(f"temperature in Kelvin:{K}")
