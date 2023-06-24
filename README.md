# Exercicio041.py


from datetime import date
atual = date.today().year
nasc = int(input('Digite o seu ano de nascimento: '))
idade = atual - nasc
print('O atleta tem {} '.format(idade))
if idade <= 9:
    print('CLASSIFICAÇÃO: Mirin')
elif idade <= 14:
    print('CLASSIFICAÇÃO: Infantil')
elif idade <= 19:
    print('CLASSIFICAÇÃO: Junior')
elif idade <= 25:
    print('CLASSIFICAÇÃO: Senior')
else:
    print('CLASSIFICAÇÃO: Master')
