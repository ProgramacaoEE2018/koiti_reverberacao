# koiti_reverberacao

Esse projeto tem como objetivo simular o fenômeno da reverberação de um sinal acústico. Para isso, utilizaremos o MATLAB R2016a. O projeto, no entanto, não se aprofunda na teoria da acústica. Em vez disso, utilizaremos classes e funções prontas da Mathworks.

**EXECUÇÃO DE TUTORIAL**

O tutorial realizado foi o seguinte: [https://www.mathworks.com/videos/creating-a-gui-with-guide-68979.html]

O objetivo do tutorial foi programar uma interface capaz de plotar diferentes dados (peaks, membrane e sinc) de três diferentes maneiras (surf, mesh e contour). Com isso, pôde-se aprender o básico da interface GUIDE do MATLAB.

O resultado final do tutorial pode ser observado nas imagens abaixo:

![tutorial](reverberacao_tutorial.jpg)

![tutorial2](reverberacao_tutorial2.jpg)

Nessas imagens, pode-se observar o APP totalmente funcional, sendo inclusive possível usar as ferramentas Zoom in, Zoom Out, Pan, Rotate e Data Cursor.

**FLUXOGRAMA (DESATUALIZADO)**

O fluxograma utilizado como base para a interface foi o seguinte:

![fluxo](fluxograma_reverberacao.jpg)

**INTERFACE VISUAL**

![interface](interface.png)

A interface com 3 pushbuttons: 

(Procurar...) Para que o usuário insira o arquivo WAV em que deseja fazer a simulação.

(Iniciar) Para que o usuário inicie a simulação.

(Save) Para salvar o arquivo WAV recebido.

Para controlar os parâmetros da simulação, há 3 sliders para controlar os três atributos da classe Reverb.m.

Além disso, a cada vez que o usuário insere um arquivo sonoro ou realiza uma simulação, o gráfico do arquivo é plotado.

Fernando Koiti Tsurukawa

Instituto Militar de Engenharia

Eng. de Telecomunicações - 3º ano
