senha_correta=1234 # variável
tentativa=1

while tentativa <= 3: # determina a quantidade de vezes que pode colocar a senha 

    senha= input("Digite sua senha: ") # é aquela parte que vai atribuir o que o usuario vai digitar no teclado a variável.
    if senha == senha_correta: #  aqui vai verificar se a senha digitada é a mesma que está salva 
        print("Acesso liberado!") # ocorre após a verificação
        break # para e vai para o else
    else:
          print("Senha incorreta!")
tentativa +=1 # aparece mais 3 vezes 
print("fim das suas tentativa!")



for numero in range (1,11):
 
    if numero %2 !=0:
        continue

    print(numero)




senha_correta="1234" # variável
tentativa=1

while tentativa <= 3: # determina a quantidade de vezes que pode colocar a senha 

    senha= input("Digite sua senha: ") # é aquela parte que vai atribuir o que o usuario vai digitar no teclado a variável.
    if senha == senha_correta: #  aqui vai verificar se a senha digitada é a mesma que está salva 
        print("Acesso liberado!") # ocorre após a verificação
        break # para e vai para o else
    else:
          print("Senha incorreta!")
tentativa +=1 # aparece mais 3 vezes 
print("fim das suas tentativa!")



for i in range(5):
    numero = float(input("Digite um número:"))

    if numero <0:
        print("Número invalido")
        continue 
    print("Número válido:", numero)

    # para adicionar uma nova mensagem tem que adicionar uma nova variável e if
