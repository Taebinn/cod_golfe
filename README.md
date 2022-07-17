Exercício interessante do módulo JavaScript Básico da certificação Algoritmos e estruturas de dados em JavaScript na FreeCodeCamp

Descrição:

Jogar golfe de código
No jogo de golfe, cada buraco tem um par, significando o número médio de strokes que se espera que golfista faça a fim de derrubar a bola no buraco para completar 
a jogada. Dependendo da distância acima ou abaixo de par que seu número de strokes estiver, há diferentes apelidos.
Sua função receberá os argumentos par e strokes. Retorne a string correta de acordo com esta tabela que lista os strokes em ordem de prioridade; superior (mais alta) 
para o final (mais baixo):

Strokes       Retorno
   1          "Hole-in-one!"
<= par - 2	  "Eagle"
par - 1       "Birdie"
par           "Par"
par + 1       "Bogey"
par + 2       "Double Bogey"
>= par + 3    "Go Home!"


par e strokes sempre será um número e positivo. O array é apenas para conviniência.
