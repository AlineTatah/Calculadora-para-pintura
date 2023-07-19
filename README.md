# Calculadora-para-pintura
Programa em python que identifica a quantidade de latas para pintar uma parede!

largura=int(input('Informe a largura:'))


altura=int(input('Informe a altura:'))


rendimento=int(input('Informe o rendimento da lata:'))

 
area = int(largura*altura)


latas = str(area/rendimento)
print('Você precisa de  ' + latas + ' latas de tinta!')
