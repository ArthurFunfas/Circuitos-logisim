Circuitos-Logisim


## 4-Bit-Adder:

Um circuito lógico que realiza soma binária de dois números binários, ambos de 4 bis. Construido primeiramente por um *Half-Adder* que soma as duas entradas e gera uma saída de soma e outra de *Carry-Out*→*Carry-In* para o próximo somador, depois do *Half-Adder* ele passa por 3 *Full-Adder* consecutivamente, o *Full-Adder* recebe as duas entradas mais o *carry-out* anterior que no operador atual se torna um *carry-in*. No último *Full-Adder* o *Carry-Out* não conecta à saída. A saída "soma" de todos os somadores se conecta na saída respectivamente de acordo com sua ordem de operação. 


## Half-Subtractor
### Entradas: A entrada A simboliza o valor positivo enquanto a B simboliza o valor negativo da operação.
### Saída: Diff mostra a diferença da subtração entre as duas entradas. Borrow indica se precisa pegar um valor emprestado da casa posterior.
### Explicação: Um sistema que subtraí a entrada A pela entrada B, mostrando o resultado das operação em Diff e a necessidade de pegar valor emprestado em Borrow.

## Full-Subtractor 
### Entradas: A entrada A simboliza o valor positivo enquanto a B simboliza o valor negativo da operação, Bi (Borrow-In) é valor que foi pego emprestado pela casa anterior.
### Saídas: Diff mostra o resultado da subtração entre as entradas e o Borrow-In. Bo(Borrow-Out) indica se precisa pegar um valor emprestado da casa posterior.
### Explicação: Um sistema que realiza a operação de subtração entre as entradas positiva(A) e negativa(B) e verifica se há pendências, indicadas por Borrow-In. Mostra o resultado das operações em Diff e a necessidade de pegar valor emprestado da casa posterior em Borrow-Out.
