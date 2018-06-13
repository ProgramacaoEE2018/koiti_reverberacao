# koiti_reverberacao
## INTRODUÇÃO

Esse projeto tem como objetivo simular o fenômeno da reverberação de um sinal acústico. Para isso, utilizaremos o MATLAB R2016a. O projeto, no entanto, não se aprofunda na teoria da acústica. Em vez disso, utilizaremos classes e funções prontas da Mathworks.

## EXECUÇÃO DE TUTORIAL

O tutorial realizado foi o seguinte: [https://www.mathworks.com/videos/creating-a-gui-with-guide-68979.html]

O objetivo do tutorial foi programar uma interface capaz de plotar diferentes dados (peaks, membrane e sinc) de três diferentes maneiras (surf, mesh e contour). Com isso, pôde-se aprender o básico da interface [GUIDE](https://www.mathworks.com/discovery/matlab-gui.html) do MATLAB.

O resultado final do tutorial pode ser observado na imagem abaixo:

![tutorial](imagens/tutorial.png)

Nessas imagens, pode-se observar o app do tutorial totalmente funcional, sendo inclusive possível usar as ferramentas Zoom in, Zoom Out, Pan, Rotate e Data Cursor.

## FLUXOGRAMA (DESATUALIZADO)

## INTERFACE VISUAL

![interface](imagens/interface.png)

![interface2](imagens/interface2.png)

A interface conta com 4 pushbuttons: 

1. *(Procurar...)* Para que o usuário insira o arquivo WAV em que deseja fazer a simulação.
2. *(Iniciar)* Para que o usuário inicie a simulação.
3. *(Save)* Para salvar o arquivo WAV produzido.
4. *(Play)* Para tocar o áudio produzido.

Para controlar os parâmetros da simulação, há 3 sliders para controlar os três atributos da classe Reverb.m.

Além disso, a cada vez que o usuário insere um arquivo sonoro ou realiza uma simulação, o gráfico do arquivo é plotado.

## INSTALAÇÃO (AINDA NÃO ESTÁ PERFEITO)

Basta executar o arquivo MyAppInstaller_web.exe. (DÁ ERRO EM ALGUMAS MÁQUINAS)

## INSTALAÇÃO ALTERNATIVA

1. Baixar os arquivos da pasta for_testing;
2. Instalar o MATLAB Runtime 9.0.1 (correspondente ao MATLAB 2016a) conforme é expLicado no arquivo readme.txt;
3. Rodar o arquivo ReverberatorAlpha.exe.

Fernando Koiti Tsurukawa\
Instituto Militar de Engenharia\
Eng. de Telecomunicações - 3º ano
