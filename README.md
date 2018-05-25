# koiti_reverberacao

Esse projeto tem como objetivo modelar o fenômeno da reverberação de um sinal acústico. Para isso, partir-se-á da resposta do ambiente a um sinal conhecido, como o impulso, e então será possível encontrar a resposta do ambiente a um som qualquer.

Esse projeto pode utilizar como ferramentas o MATLAB ou até o LABVIEW.

Alternativamente, pode-se utilizar a geometria do ambiente para se modelar a reverberação, contanto que o formato da sala seja simples o suficiente.

**EXECUÇÃO DE TUTORIAL**

O tutorial realizado foi o seguinte: [https://www.mathworks.com/videos/creating-a-gui-with-guide-68979.html]

O objetivo do tutorial foi programar uma interface capaz de plotar diferentes dados (peaks, membrane e sinc) de três diferentes maneiras (surf, mesh e contour). Com isso, pôde-se aprender o básico da interface GUIDE do MATLAB.

O resultado final do tutorial pode ser observado nas imagens abaixo:

![tutorial](reverberacao_tutorial.jpg)

![tutorial2](reverberacao_tutorial2.jpg)

Nessas imagens, pode-se observar o APP totalmente funcional, sendo inclusive possível usar as ferramentas Zoom in, Zoom Out, Pan, Rotate e Data Cursor.

**USER INTERFACE**

O fluxograma utilizado como base para a interface foi o seguinte:

![fluxo](fluxograma_reverberacao.jpg)

Assim, com as ferramente apreendidas no tutorial, foi possível montar a interface não funcional do programa.

![interface](reverberacao_UI.jpg)

A interface possui somente 4 pushbuttons. Esses pushbuttons terão a função de pedir ao usuário o arquivo da amostra de impulso e o arquivo a ser filtrado, outro para iniciar a simulação e outro para salvar o arquivo sonoro obtido.

Fernando Koiti Tsurukawa

Instituto Militar de Engenharia

Eng. de Telecomunicações - 3º ano
