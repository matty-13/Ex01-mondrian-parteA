# 01exMondrian

Comecei por abrir a imagem base da pintura do Mondrian no Illustrator onde fui encontrando, pixel por pixel, as respetivas coordenadas de cada uma das linhas e retângulos que compõem a geometria desta composição.
Defini valores como o tamanho do canvas, a cor do background e o modo de cor para o RGB.
Assim, só me restou ir montando a composição, começando pelos retângulos vermelho amarelo e azul, respetivamente, todos com a mesma "formula": 
    noStroke(); - para não haver nenhum traço a contornar as formas
    fill(238,36,0); - com o respetivo código de cor RGB da cor desejada
    rect(0,0,362,312) - com as cordenadas que dão forma a cada retângulo
As linhas foram feitas dum modo, também, simples, começando per definir a cor de todas as linhas: stroke(3,2,2);
E, depois as espessuras para as linhas horizontais
    strokeWeight(14)
e para as verticais
    strokeWeight(12);

Assim, cada linha, à semelhança dos retângulos coloridos, foi feita segundo a seguinte "formula":
    line(367,0,367,height)
    
Tendo reparado que os traços não são 100% retos em termos de pixeis, como pode parecer em pequena escala, optei por fazer ligeiras alterações nestas coordenadas de modo que as linhas no ecrã se assemelhem mais ao traço feito pela mão humana com um pincel.