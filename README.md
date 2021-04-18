Quem nunca jogou Jokenpô? Famoso, Predra, Papel e Tesoura...

O código foi feito durante as aulas do curso Dev Samurai, com o professor Felipe Fontoura.
Fiz uma alteração importante, na função de SetTimeOut, mudando de 3500 para 1000.
Dessa forma, caso o jogador queira sem mais rápido nas jogadas, o Highlight da jogada anterior,
vai ser limpo mais rapidamente.
Quando estava em 3500, o programa fixava o Highlight, se o jogador fosse clicando rapidamente
em novas opções. Destravando somente quando clicava na opção que estava "travada".

Com o SetTimeOut em 1000, o Hightlight limpa rapidamente, fazendo com que o jogo seja
mais dinâmico e não trave nenhuma opção.
