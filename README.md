altura = float(input('Qual e sua altura em cm: '))
peso = float(input('Qual e o seu peso em kg: '))
IMC = peso / (altura / 100)**2

print(IMC)

if IMC < 18.5:

  print(f'Seu IMC e de ({round(IMC,1)}), e e classificado como Magreza')

elif IMC >= 18.5 and IMC < 24.9:

  print(f'Seu IMC e de {round(IMC,1)}) , e e classificado como Normal')

elif IMC >= 25 and IMC < 29.9:

  print(f'Seu IMC é de {round(IMC,1)}), e é classificado como Sobrepeso')

elif IMC >= 30 and IMC < 39.9:
  print(f'Seu IMC é de {round(IMC,1)}), e é classificado como Obesidade')

else:
  print('Obesidade Grave')

