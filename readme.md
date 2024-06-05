# Corrida de cobrinha Display 7 Segmentos - MicroControlador 8051

### *Percurso 1:*
![](https://github.com/TC071/Cobrinha8051uC/blob/main/assets/cobrinha_circuito1.gif)

### *Alternando a velocidade:*
![](https://github.com/TC071/Cobrinha8051uC/blob/main/assets/cobrinha_cirtuito2_velocidades.gif)

### *Alterando os percursos:*
![](https://github.com/TC071/Cobrinha8051uC/blob/main/assets/cobrinha_circuitos.gif)

## Projeto
Este projeto foi desenvolvido como atividade avaliativa do curso Técnico em Eletrônica do IFBA para fechar nossos estudos de Assembly para µC 8051.
O programa visualizado acima num emulador, exibe uma sequência de segmentos nos displays conectados nos pinos P2 do µC, que devido a alta taxa de atualização do 8051, aparenta ser uma "cobrinha" de 5 segmentos percorrendo circuitos pré programados.
Foram desenvolvidos 3 percursos para que a cobrinha percorresse e podem ser alternados pelo usuário a partir de uma das seguintes interações:

(No Virtual Machine exibido nos gifs é possível alternar o nível de tensão de todos os pinos das portas P0 a P3, porém na realização do trabalho foram instalados botões apenas nos pinos P3.0 a P3.4)

>**P3.0** : Inverte o sentido do percurso
>
>**P3.1** : Altera o percurso 
>
>**P3.2** : Pausa
>
>**P3.3** : Aumenta a velocidade
>
>**P3.4** : Diminui a velocidade
