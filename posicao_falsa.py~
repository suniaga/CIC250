# -*- encoding: utf-8 -*-
from math import sin, cos, e, tan, log

# funcao a ser trabalhada
def f(x):
	return x - pow(e,x)
#	return sin(x) + pow(x,2) + 1
#	return sin(x) - x + 2
#	return 2*x-tan(x)
#	return pow(x,3) - sin(x)
#	return 3*x - cos(x) + 1
#	return  log(x) - sin(x)
#	return x - sin(x)
#	return sin(x) - x - 1
#	return 2*x-pow(e,-1)

a = -2.0 # limite inferior
b = -1.0 # limite superior
low = a
high = b
epsilon = 0.0001
k = 0
n = 50

while k < n:
	k += 1 # quantidade de iteracoes
	midpoint = (f(high)*low -f(low)*high)/(f(high)-f(low))

	if abs(f(midpoint)) < epsilon:
		break
	elif f(low)*f(midpoint) < 0:
		high = midpoint
	else:
		low = midpoint
	print 'k = ', k, ' p. médio = ', midpoint, \
	' f(pmedio) = ', f(midpoint), 'low = ', low, 'high = ', high

