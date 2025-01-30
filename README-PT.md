# ParkingLock


## Princípio de Funcionamento


O princípio de funcionamento do Parking Lock é relativamente simples. Ele utiliza um motor DC acoplado a uma caixa de redução, que, por sua vez, está conectado ao eixo da alavanca de bloqueio. Esse conjunto é responsável por realizar os movimentos de elevação e descida da alavanca.

Para realizar o controle dos acionamentos, o conjunto utiliza 3 chaves mecânicas do tipo fim de curso, responsáveis por indicar a posição da alavanca de bloqueio durante os movimentos de subida e descida.

[Imagem do Locking Park]

Para facilitar a compreensão do funcionamento completo do sistema, as chaves fim de curso foram enumeradas da direita para a esquerda, como mostra a imagem abaixo

[Imagem Fim de Curso]

A partir disso, foi criada a tabela com o estado de cada uma das chaves nas respectivas posições

|Estado/Sensor| FC3     | FC2     |  FC1    |
| :---:       | :---:   | :---:   | :---:   |
| A           | Fechado | Aberto  | Aberto  |
| B           | Aberto  | Aberto  | Aberto  |
| C           | Aberto  | Fechado | Aberto  |
| D           | Aberto  | Fechado | Fechado |

