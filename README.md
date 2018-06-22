Trabalho de Avaliação e Desempenho

Este trabalho visa avaliar o desempenho de um roteador, servindo a tráfego de
dados e voz e transmitindo num canal de comunicação de 2 Mbps.
Como o tráfego de voz é sensível a atraso, este tráfego terá prioridade sobre o
tráfego de dados. Simularemos o comportamento do roteador como um servidor
único e duas filas de espera, atendendo a dois grupos de fregueses: dados e voz. O
tempo de serviço do pacote de dados será a variável aleatória X1 e o tempo de
serviço do pacote de voz será a variável aleatória X2. A voz será prioritária em
relação a dados.
Obteremos medidas estatísticas para serviço prioritário preemptivo (interrupção de
transmissão de pacote de dados pela chegada de pacote de voz e retorno do pacote
para a fila de espera para aguardar nova transmissão de todo o pacote) e serviço
prioritário não preemptivo (pacote de dados em transmissão não sendo interrompido
pela chegada de pacote de voz).
Em ambas as disciplinas, a fila de espera de pacotes de dados só volta a ser
servida, quando a fila de espera de pacotes de voz se esvaziar. Pacotes em cada
fila são servidos na ordem de chegada (FIFO).
