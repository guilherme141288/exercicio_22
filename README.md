# exercicio_22

#displaying the units, tenths, hundreths and thousandths of a given number up to 9999

num = input ('informe um numero: ')

numb = int(num)

u = numb // 1 % 10
d = numb // 10 % 10
c = numb // 100 % 10
m = numb // 1000 % 10

print ('unidade {}'.format(u))
print ('dezena {}'.format(d))
print ('centena {}'.format(c))
print ('milhar {}'.format(m))
