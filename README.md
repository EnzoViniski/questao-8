Algoritmo "Cerveja"

var
   n1, n2, area, custo: real
   
inicio
   //Entrada de dados
   escreva("Digite o raio da lata em metros: ")
   leia(n1)
   
   escreva("Digite a altura da lata em metros: ")
   leia(n2)
   
   //Operações
   area <- 2 * (3.14159 * (n1 ^ 2)) + 2 * 3.14159 * n1 * n2
   custo <- area * 100
   
   //Saída de dados
   escreva("O VALOR DE CUSTO É = ", custo)
fimalgoritmo
   
