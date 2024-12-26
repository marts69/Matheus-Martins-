# Exercício 1
numero = int(input("Insira um número: "))
if numero % 2 == 0:
    print("O número é par.")
else:
    print("O número é ímpar.")

# Exercício 2
idade = int(input("Qual é a sua idade? "))
if idade >= 0 and idade <= 12:
    print("Criança")
elif idade >= 13 and idade <= 18:
    print("Adolescente")
else:
    print("Adulto")

# Exercício 3
usuario_esperado = "admin"
senha_esperada = "1234"
usuario = input("Nome de usuário: ")
senha = input("Senha: ")
if usuario == usuario_esperado and senha == senha_esperada:
    print("Acesso concedido.")
else:
    print("Acesso negado.")

# Exercício 4
x = float(input("Insira a coordenada x: "))
y = float(input("Insira a coordenada y: "))
if x > 0 and y > 0:
    print("Primeiro Quadrante")
elif x < 0 and y > 0:
    print("Segundo Quadrante")
elif x < 0 and y < 0:
    print("Terceiro Quadrante")
elif x > 0 and y < 0:
    print("Quarto Quadrante")
else:
    print("O ponto está localizado no eixo ou na origem.")
