# -*- encoding: utf-8 -*-
from math import sin, cos, e, tan, log

# f(x)
def f(x):
	return -0.5*pow(x,2) + 2.5*x + 4.5

# Derivada de f(x)
def fl(x):
	return 2.5 - x

x0 = -2.0 # limite inferior
x1 = -1.0 # limite superior
epsilon = 0.0001
e1 = 0.0001
e2 = 0.0001
k = 0
n = 10

print 'Método de Newthon Raphson:'

while k < n:
	k += 1
	x1 = x0 -f(x0)/fl(x0)
	# TODO: condição de parada
	x0 = x1
	print 'k = ', k, 'x0 = ', x0, 'x1 = ', x1
