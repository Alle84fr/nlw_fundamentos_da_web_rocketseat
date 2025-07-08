_____________________

<center>
<h3>
<span style="color: #8bb174;"> Markdown</spna>

</h3>
</center>

# Título maior, principal #
## Título ##
### Título ###
#### Título menor ####

<span style="color: #168aad;"> span style="color: #168aad;", dentro do < > muda cor</spna>

' &nbsp ;' pula linha e dá espaço 
<br>
<br>
_____________________

<center>
<h3>
<span style="color: #8bb174;"> HTML</spna>
</h3>
</center>

<h1> h1</h1>

<h2> h2 </h2>

<h3> h3 </h3>

<h4> h4 </h4>

<h5> h5 </h5>

<h6> h6 </h6>

<span style="color: #168aad;"> Dica, para criar a tag, só a digite , ex p e dê enter que firá virar < p >< /p > </spna>

- <b>Tag</b> < p ></ p> é parágrafo
<br>
- <b>Tag</b> < a >< /a > -âncora - é para criar hiperlinks

ir em extensões - LiveServer - launch a decep....

para ver botão direito no file index.html - open with live server

abrirá uma "pag web"

- <b>HTTP</b> - <i>HyperText Transfer Procolo </i>/ Protocólo de transfer~encia de hypertextos

    protocolo - conjunto de regras 

<br>

- <u>Hyper Text</u>

    - antigamente tinha apenas texto puro, como livros, jornais
    -com o tempo chegou a versão web que trouxe links (hyper texto), texto que levava a outro lugares
    - Agora temos imagens, vídeos, áudios

<br>    

- <u>Markup</u>

    - marcações:
<br>

- <b>URL</b> - <i>Uniform Resource Locator</i> / Localizador de Recurso uniforme

    Encontrar um recurso (html, cdd, js, pdf, png, mp ...)

    o endereço levará ao recurso
<br>

- <b>IP</b> - <i>Internet Protocol</i> / Protocolo da internet 

    Endereço do computador

    obs - domínio seria o nome ex rocketset.com.br
<br>

- <b>Internet</b>  - rede mundial de computadores. Estes estão conectados atravéz de cabos e wifi
<br>

- <b>DNS</b> <i>Domain Name Server</i> / Sistema de nome de domínio

    Transfora o domínio em um ip

<br>

- <b>Porta</b> - :5050/ ou 8080/ 

    Depois da porta encontra algo (index.html)

    ex: http://127.0.0.1:5500/index.html
<br>

<span style="color: #168aad;"> Dica, digitar a, descer até a:link e enter -> < a href="url"></a> </spna>
<br>
<br>
<span style="color: #ff5714;"> Dica, digitar ! e enter -> 
< !DOCTYPE html>
< html lang="en">
< head>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;< meta charset="UTF-8">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;< meta name="viewport" content="width=device-width, initial-scale=1.0">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;< title>Document</title>
< /head>
< body>
< /body>
< /html></a></spna>

<br>
<br>
Fundamentos do html
<br>
<br>

< !DOCTYPE html>  = tipo do doc


< html lang="en">  = tag root / tag raiz 

deixar em pt-br para mostrar que é em potuguês e assim pode dar dica de , se alguém abrir em outro lugar do mundo, pode ter sugestão de tradução

html é uma estrutura de árcores = pai

< head> < /head> ou < body> < /body> =  nós ou filhos

< head> =  tem metadados, configuração escondidas

< meta charset="UTF-8"> = configura caracteres interpretados na pag, principalmente os especiais
<br>
<center>
<b><u>VIEWPORT =  pag em branco</b></u>
</center>
<br>

< meta name="viewport" content="width=device-width, initial-scale=1.0"> = width=device-width = configura a largura para o tamanho do dispositivo. Já initial-scale=1.0 seria o zoom, neste caso sem , tela normal

< title> título do navegador que aparece na aba branca da pag
<br>

< body> O que aparecerá na pag/ corpo da pag/ dentro da wiewport

< header> Cabeçalho

< img> scr = local   alt = aternativo = decrição da imagem, tipo o id talvez - pessoas que não podem ver a imagem irá ler esta parte

google lê o alt

./ = ponto = na pastas e buscando

< main> conteúdo principal

< section> sessão

observar identação e aberturas

Seletor é quando chama a tag para fazer algo com ela

ex
< style>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h2 {
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;color: red;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
< /style>

-<b>Importar a pag css no html</b>

Apenas teclar link e enter

< head>
    < meta charset="UTF-8">
    < meta name="viewport" content="width=device-width, initial-scale=1.0">
    < title>Título</title>

    // importar css
    < link rel="stylesheet" href="index.html">
    
< /head>

pegar o nome - botão direito no file:css - por ./ antes do nome

ou só link enter - ir no file - copy relative path - por ./ na frente do nome

- <b>rel</b> relacionamento da tag link - que é stylesheet (estilo de pag)

<br>
<br>
_____________________

<center>
<h3>
<span style="color: #8bb174;"> CSS </spna>
</h3>
</center>

<br>
- <b>CSS</b><i>Cascating Style Sheet</i> / Folha em estilo de cascata

- casacatas são regras das escritas

O arquivo terá em sua sintaxe, declarações, propriedades e valores

Irá impactar o html

- aqui se chama apenas a tag

h2 {
    corpo
}

- <b>Declaraçao</b>
- <b>Regras da Escrita</b>
- <b>Hierarquia</b> de baixo prevalece, savo de especificar
- <b>Especifidade</b> ex .title = seleciona a classe title ou h2.title (tudo junto)
<br>
body{
    background-image: url("./assets/pexels-earano.jpg");
}

por uma ou mais imagens

url() = função do css

body{
    background-image: url("./assets/pexels-zvolskiy.jpg");
    /*pega imagem*/
    background-repeat: no-repeat;
    /*keyword - para não repetir imagem*/
    background-size:; 100% auto;
    /*width height - altura*/
    /*automaticamente o tamanho da imagem é 100% da largura da pag */
    background-position: top center;
    /*vertical -y horizontal - x*/
    background-color: #121214;
    /*hex: repete rr, gg, bb*/
    /*pega imagem*/ff é máximo 00 é menos
    /*matriz = hue = posição das cores - de 0° a 360°
    saturação = saturation = pureza e vivacidade - 0 a 100%
    iluminosidade = lightness = brilho - 0% preto e 100% branco*/
}