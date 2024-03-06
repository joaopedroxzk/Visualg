# Visualg

Algoritmo "semnome"

Var

num1 : inteiro
num2 : inteiro
soma : inteiro
opcao : inteiro
Inicio

escreva("Digite o 1° número: ")
leia(num1)
escreva("Digite o 2° número: ")
leia(num2)

escreval(" ------------------------------- ")

escreval ("1 - Adição")
escreval ("2 - Subtração")
escreval ("3 - Multiplicação")
escreval ("4 - Divisão")

leia (opcao)
escolha opcao

caso 1
 escreval (" A soma dos seus números é igual a", num1 + num2)
caso 2
 escreval (" A subtração dos seus números é igual a", num1 - num2)
caso 3
 escreval (" A multiplicação dos seus números é igual a", num1 * num2)
caso 4
 escreval (" A divisão dos seus números é igual a", num1 / num2)
 
 outrocaso
 escreva("escolha uma das opção acima")
 fimescolha

Fimalgoritmo
