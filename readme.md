
# Curso - Lógica de programação II: pratique com desenhos,animaçõs e um jogo -Alura - 10h - 30/10/2020
  

    <canvas> </canvas> área da tela que eu posso desenhar com um "pincel"
   
   x = width = "600" largura
   y = height = "400" altura
   
No Javascript pode usar ' ' (aspas simples);
tela.getContent('2d'): é o meu "pincel" para pintar a tela;
fillRect = tamanho (x,y);
fillStyle = cor da tela

    /*  comentário no canvas
    */
    
    pincel.fillStyle = yelow; (cor do pincel)
    pincel.beginPath(); (novo caminho)
    pincel.moveTo(300,200); (mover a partir do ponto)
    pincel.lineTo(200,400); (cria linha até os pontos)
    pincel.lineTo(400,400); (cria linha até os pontos)
    pincel.fill(); (preencher)

Exemplo básico: [clicar aqui.](https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API)

Colocar borda no quadrado:

    pincel.fillStroke = 'black';
    pincel.fillStrokeRect(0,0,50,50);
    pincel.StrokeStyle = 'red';

Para o canvas interagir com o usuário:

    tela.onclick = (exibe aberta);
   *Fim!*
