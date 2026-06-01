lista = [9, 42, 21, 14, 28, 3, 19, 32, 46, 6]
maior = -1  
for num in lista:
    if num % 2 != 0:  # se for ímpar
        if num > maior:
            maior = num
if maior == -1:
    print("Não tem número ímpar")
else:
    print(maior)
