# Loja-de-Tintasfrom math import ceil
area = float(input("Informe a área a ser pintada(metros quadrados):"))
tinta_litros = area/6 #Aqui, será obtido os litros necessários para pintar a parede.
quant_lata = ceil(tinta_litros/18) #Aqui, será obtido a quantidade de latas arredondadas.
custo = quant_lata*80 #Aqui, será obtido o custo.
print("Com {}m2 de área a ser pintada, será necessário {} lata de tinta, Ultilizando Galões de 18L. Isso custará R${}".format(area,quant_lata, custo ))
lata_2 = ceil(tinta_litros/3.6)# Aqui, será obtido a quantidade de latas, usando 3.6l por capacidade de lata.
custo2 = lata_2*25 #Aqui, será obtido o custo.
print("Ultilizando a mesma area, com galões de 3.6L, ao final será custeado R${}".format(custo2))
