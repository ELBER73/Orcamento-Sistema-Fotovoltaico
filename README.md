# Orcamento-Sistema-Fotovoltaico
Orçamento de sistema fotovoltaico
Algoritmo "OrçamentoFotovoltaico"

Var

       Valor: Inteiro


Inicio

    EscrevaL ("------------------------------------")
    EscrevaL ("         TABELA DE PREÇOS           ")
    EscrevaL ("------------------------------------")
    Escreval ("          Digite seu pedido         ")
    Escreval (" [1] para Sistema Fotovoltáico 330Kw" )
    Escreval (" [2] para Sistema Fotovoltáico 400Kw" )
    Escreval (" [3] para Sistema Fotovoltáico 500Kw" )
    Escreval (" [4] para Sistema Fotovoltáico 600Kw" )
    Escreval (" [5] Qual a potencia necessaria para sua residencia" )
    Leia (Valor)
    Escolha Valor
       Caso 1
            Valor <- 8000
       Caso 2
            Valor <- 12000
       Caso 3
            Valor <- 15000
       Caso 4
            Valor <- 18000
       Caso 5
    Escreval ("Digite seu melhor E-mail para enviarmos o orçamento.")
    FimEscolha
    Escreval (" SEU SISTEMA CUSTARÁ R$ ", Valor)
    Escreval ("Obrigado pela confiança em nossos serviços")
    EscrevaL ("-------------------------------------")


    
Fimalgoritmo
