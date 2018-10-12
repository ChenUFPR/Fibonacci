# Fibonacci

def Fibonacci(n):
	while (n<=0):
		print("Só é possível calcular a sequência de Fibonacci com números positivos.")
		n = int(input("Informe um número:"))
	while n >= 0:
		a,i,b = 0,0,1
		print("A sequêmcia de Fibonacci de {} é:".format(n, end=''))
		print(a, end = ',')
		while i < n-1:
			a,b=b,a+b
			i+=1
			print(a, end = ',')
		print(b, end = '.')
		return Fibonacci
				

n = int(input("Informe um número:"))
Fibonacci(n)
