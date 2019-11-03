x = input('Wprowadz numer: ')
num=int(x)
if num%2==0:
    print("numer {} jest parzysty ".format(num))
elif num%4==0:
    print("Hej ta liczba jest wielokrotnością 4!")

y = input('Wprowadz numer: ')
z = input('Wprowadz numer: ')
num1=int(y)
num2=int(z)
if num1%num2==0:
    print("numer 1 dzieli się bez reszty przez numer 2")
else:
    print("numer 1 nie dzieli się bez reszty przez numer 2")
