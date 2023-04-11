# JogoIA
Programa escrito em Java com o objetivo de simular um jogo que tenha aplicações de inteligência artificial de busca heurística,

OBS: não foram implementadas todas as funcionalidades das regras, estando apenas com 3 cartas por jogo, e um humano e um BOT

Regras do jogo: Você irá jogar contra o computador. Ambos iniciam com 5 vidas e vão
perdendo conforme erram o número de palpites na rodada. Todos iniciam com 5 cartas, e
conforme as rodadas vão sendo finalizadas, será retirada uma carta de cada jogador.
Disposição das cartas: a ordem das cartas é 3, 2, 1, 12, 11, 10, 7, 6, 5, 4. Sendo que após a
distribuição das cartas para todos os jogadores, o restante das cartas é colocada ao centro
da mesa, e a carta ao topo é virada, sendo a próxima numeração a mais forte do jogo e
posteriormente a ordem das cartas citadas acima. Exemplo: Caso a carta virada for 6, a de
número 7 será a mais forte, e depois 3, 2, 1, 12, 11, 10, 6, 5, 4.
Como jogar: Cada um deverá dizer quantas jogadas irá vencer na rodada em questão. A
somatória de vitórias não pode ser igual ao número de cartas na mão da rodada em que
estão.
O(s) vencedor(es) será(ão) aquele(s) que finalizar(em) a rodada acertando o palpite que fez
antes do jogo começar, de quantas vitórias iria conseguir naquela rodada
