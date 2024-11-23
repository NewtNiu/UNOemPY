Atividade individual ou em duplas cujo objetivo é a abstração de um jogo de cartas em um sistema
computacional usando a linguagem Python.

Regras e componentes do jogo de cartas a ser implementado:
    1) O jogo possui cartas numeradas de 1 a 9 de 4 cores (azul, vermelha, amarela e verde), totalizando 40
    cartas.
    2) O jogo tem dois jogadores.
    3) A sequência de jogo acontece da seguinte forma:
    a. Forma-se um baralho (pilha) com as 40 cartas organizadas de forma aleatória (embaralhadas);
    b. Distribui-se 5 cartas fechadas (apenas o jogador pode ver sua mão) para cada um dos
    jogadores a partir do baralho;
    c. Abre-se 1 carta aberta (visível a todos) na mesa, ao lado do baralho;
    d. No turno de cada jogador, ele deve escolher uma carta da mão para jogar que seja da mesma
    cor ou de mesmo número da carta aberta na mesa, formando uma pilha;
    e. Caso o jogador não tenha nenhuma carta de mesma cor ou de mesmo número na mão, ele
    deve pescar uma carta do baralho para sua mão e passar a vez;
    f. O jogo termina quando um dos jogadores ficar sem cartas na mão ou quando um jogador tiver
    que pescar uma carta e o baralho estiver vazio.
    4) Ganha o jogo aquele jogador que bater primeiro (ficar sem cartas na mão) ou o jogador com o menor
    número de cartas na mão (caso a partida termina por conta do baralho vazio).
    g. Caso a partida termine e ambos os jogadores ficarem com o mesmo número de cartas na mão,
    a partida é considerada um empate.
    O trabalho deve possuir as seguintes características:
    1) O jogo deve ser desenvolvido na linguagem Python, mas não é necessário desenvolver interface
    gráfica. A interação com o usuário pode ser via terminal/console.
    2) O nome de cada jogador, deve ser informado pelo usuário ao iniciar o jogo.
    3) A seleção da carta a ser jogada por cada jogador deve ser solicitada ao usuário. Não é necessário
    esconder as mãos do jogador do usuário (não teria como sem usar elementos de rede para criar um
    jogo multijogador com múltiplos usuários).
    4) No início de cada turno de jogador deverá ser impresso a última carta jogada (carta sobre a pilha na
    mesa) e as cartas da mão do jogador atual.
    5) Ao final do jogo deve-se anunciar/imprimir o nome do jogador vencedor ou se houve a partida
    terminou em um empate.

------------
Feito por: Niumar Girardi - Novembro de 2024.