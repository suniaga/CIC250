# -*- encoding: utf-8 -*-
from math import sin, cos, e, tan, log

# f(x)
def f(x):
	return -0.5*pow(x,2) + 2.5*x + 4.5

x0 = 6 # limite inferior
x1 = 7 # limite superior
x2 = 0
epsilon = 0.0001
e1 = 0.0001
e2 = 0.0001
k = 0
n = 50

print 'Método da Secante'
while k < n:
	k += 1

	x2 = x1 - (f(x1)/(f(x1) - f(x0))) * (x1 - x0)
	# TODO: condição de parada
	x0 = x1
	x1 = x2
	print 'k = ', k, 'x0 = ', x0, 'x1 = ', x1, 'x2 = ', x2
