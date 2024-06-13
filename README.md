# Card-Game-dumb-play
O código em C++ apresenta a implementação de um jogo de cartas estratégico e tático, onde dois jogadores se enfrentam em uma série de rodadas. Cada jogador recebe uma mão de cartas de um baralho que inclui cartas de diferentes cores e valores. O objetivo é vencer as rodadas acumulando pontos, que são determinados pelo resultado de combates entre as cartas jogadas pelos jogadores.

No início do jogo, o baralho é inicializado e embaralhado. As cartas são distribuídas entre os jogadores, que então alternam suas jogadas em cada rodada. Durante sua vez, um jogador pode escolher jogar uma carta da sua mão, exibir as cartas presentes na mesa ou encerrar o jogo.

Quando um jogador decide jogar uma carta, essa carta é colocada na mesa e um combate é iniciado. O combate envolve comparar o valor total das cartas pretas jogadas pelos jogadores. Certas cartas têm valores especiais que podem influenciar o resultado do combate. O jogador vencedor do combate recebe pontos e, em alguns casos, cartas adicionais são distribuídas entre os jogadores.

Ao final de cada rodada, os pontos são contabilizados com base nos resultados dos combates e na quantidade de rodadas jogadas. O jogo continua até que todas as cartas do baralho sejam utilizadas. O jogador com mais pontos ao final do jogo é declarado o vencedor.

Essa implementação combina elementos de estratégia, gestão de mão e sorte, proporcionando uma experiência desafiadora e divertida para os jogadores.


