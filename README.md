Explicação inicial
==============

Para este teste deve ser feito um programa que receba as entradas e imprima no console a saída desejada pelo problema.
Deve ser feito em java e o código deve ser commitado neste repositório através de um pull request ou enviado para o email thiago@rogalabs.com. Qualquer indício de que o canditado copiou o código de algum lugar o desclassificará.

Teste para Entrevista
==============

Problema do Robô de Marte
             

Um esquadrão de robôs NASA, chamado Mars Rovers, estão para desembarcar em um platô em Marte. Este planalto, que é curiosamente retangular, deve ser navegado pelos rovers para que suas câmeras on-board possam obter uma visão completa do terreno circundante para enviar de volta para a Terra. A posição da sonda e de sua localização é representada por uma combinação de coordenadas x e y  e uma letra que representa um dos quatro pontos cardeais de compasso. O planalto é dividido em uma grade para simplificar a navegação. Uma posição de exemplo pode ser 0, 0, N, o que significa que o rover está no canto inferior esquerdo e de frente para o Norte. 
A fim de controlar um rover, a NASA envia uma simples seqüência de letras. As letras possíveis são 'L', 'R' e 'M'. 'L' e 'R' fazem com que os rover rotacionem 90 graus para a esquerda ou direita, respectivamente, sem sair de seu local atual. O 'M' faz com que ele avançe um ponto na grade, mantendo a mesma posição.
Suponha que o quadrado indo para Norte a partir de (x, y) é (x, y +1).

ENTRADA: 

A primeira linha da entrada são as coordenadas superior direita do planalto, as coordenadas inferior esquerdo devem ser assumidas como 0,0. 

O resto da entrada é informação relativa aos rovers que foram implantados. Cada rover tem duas linhas de entrada. A primeira linha dá a posição do rover, e a segunda linha é uma série de instruções que dizem ao robô como explorar o planalto. 
A posição é constituída por dois números inteiros e uma sequencia separada por espaços correspondentes à x e y de coordenadas e a orientação da sonda. 

Cada rover será concluída em seqüência, o que significa que o segundo rover não vai começar a mover-se até que a primeira terminou em movimento.

SAÍDA:

A saída para cada rover deve ser a sua coordenada final e para onde está apontando (Ex.: 2 4 N ou 3 3 S)


ENTRADA E SAÍDA:

Test Input:
5 5

1 2 N

LMLMLMLMM

3 3 E

MMRMMRMRRM
