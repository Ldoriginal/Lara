Algoritmo "Lanchonete: Lara Vasconcelos 2"

Var
opcao, total, valor: Real
Inicio

total <- 0

Escreval("Bem-vindo a Lanchonete Da Lara!")
Escreval("Menu de Lanches:")
Escreval("1 - X-Salada: R$8,00")
Escreval("2 - X-Bacon: R$10,00")
Escreval("3 - X-Egg: R$9,00")
Escreval("4 - Refrigerante: R$5,00")
Escreval("5 - Finalizar pedido")

Repita
    Escreval("Digite a opcao desejada (1 a 5): ")
    Leia(opcao)

    Se opcao = 1 Entao
        valor <- 8.0
    Senao
     Se opcao = 2 Entao
        valor <- 10.0
    Senao
     Se opcao = 3 Entao
        valor <- 9.0
    Senao
     Se opcao = 4 Entao
        valor <- 5.0
    Senao
     Se opcao = 5 Entao
        Escreval("Pedido finalizado. Total a pagar: R$", total)
    Senao
        Escreval("Opção inválida. Escolha uma opção válida.")
    FimSe
    fimse
    fimse
    fimse
    fimse


        total <-(total + valor)
Ate opcao = 5
FimAlgoritmo
