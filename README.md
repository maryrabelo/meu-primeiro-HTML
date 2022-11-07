# meu-primeiro-HTML
Desafio de Projeto para criar um HTML
<html>
    <head>
        <title>Introdução ao HTML na Prática</title>
    </head>
    <body><h1><strong style="color: rgb(41, 0, 43);">Introdução ao HTML na Prática</strong></h1><hr />
        <h1 id="início" style="color:rgb(8, 65, 6)">Tópicos abordados</h1>
        <ul><font size="4"><li><a href="#falando-sobre">Falando sobre Tags e Seus Atributos</a></li>
        <li><a href="#links">Links</a></li>
        <li><a href="#textos">Textos</a></li>
        <li><a href="#listas-ol-ul">Listas Ordenadas e Não Ordenadas</a></li></font>
        </ul>
        <h2 id="falando-sobre" style="color:rgb(255, 0, 149)" >Falando sobre Tags e Seus Atributos</h2>
            <p>São as propriedades que uma tag pode ter. Temos os atributos globais e específicos. Por exemplo, na tag "strong", em que colocamos o texto em negrito, podemos ter um atributo que se chama "id". Esse atributo é como um identificador desse elemento. </p>
            <p>Como vimos nas primeiras aulas, conseguimos abrir nos navegadores as "Ferramentas do Desenvolver" e, a partir dela, fazer algumas alterações no site para o nosso navegador. Quando que atualizamos a página, ela volta para o originalmente desenvolvido. Podemos fazer isso com textos, cores, fontes e etc.</p>
            <p>Agora como exemplo de atributos específicos, podemos citar outro exemplo. A tag "input", que gera um campo texto no HTML, tem o atributo "type", que é específico para a tag. Assim, se mudar o atributo "type" de "text" para "number", automaticamente aparecerá setas no campo texto do HTML denotando os números. </p>
            <h2 id="links" style="color:rgb(255, 0, 149)">Links</h2>
            <small><a href="#início">Voltar ao início</a></small>
            <p>Quando estamos no site e clicamos em outros link, estamos navegando na internet. Então, para utilizar um link em nosso site usamos a tag "a" de anchor (âncora), ou seja, está indo para um lugar específico mas ancorado na página:</p>
                <blockquote><a href="http://dio.me">Dio.me</a></blockquote>
            <p>Podemos também configurar para o link abrir na mesma guia ou em outra, ou na mesma janela ou em uma outra.</p>
            <p>Também é possível auxilar na navegabilidade do site usando o atributo "title", que assim aparece uma mensagem ao passar o cursor em cima do texto que contém o link.</p>

            <h2 id="textos" style="color:rgb(255, 0, 149)">Textos</h2>
            <small><a href="#início">Voltar ao início</a></small>
        <p>Textos são basicamente o que o usúario irá ver. Para essa finalidade temos as tags "h"'s, que vão do h1 até h6. A inicial "h" vem de "header", cabeçalho em portugês, que é como se fosse o título da sua página - e cada um dos "h"'s se referem a um nível (título e subtítulos). Já para um parágrafo -um texto simples- utilizamos a tag "p". A cada ponto final devemos colocar um "p" novo.</p>
        Agora, se queremos fazer uma citação, usamos a tag "blockquote". Vou usar uma citação do Professor Dennys Xavier para exemplificar: <blockquote>"Liberdade de expressão é a arte de conviver (no mundo das ideias e das palavras) com tudo o que pode ofender e machucar".</blockquote> </p>
        <p>Além da tag "strong", podemos usar também a "u", de "underline", para sublinhar alguma frase. Vamos utilizar a mesma frase anterior para exemplificar:</p>
        <blockquote> <u>"Liberdade de expressão é a arte de conviver (no mundo das ideias e das palavras) com tudo o que pode ofender e machucar".</blockquote></u>
        <p>A tag "i" é para deixar a frase em itálico:</p>
        <blockquote> <i>"Liberdade de expressão é a arte de conviver (no mundo das ideias e das palavras) com tudo o que pode ofender e machucar".</blockquote></i>
        <p>Ou a tag "mark" para grifar um texto:</p>
        <blockquote> <mark>"Liberdade de expressão é a arte de conviver (no mundo das ideias e das palavras) com tudo o que pode ofender e machucar".</blockquote></mark>
        <p>A tag "small" em HTML é usada para definir o tamanho pequeno da fonte, e é utilizado para reduzir o tamanho da fonte num intervalo definido de um texto.</p>
        <blockquote>"Ninguém é tão grande que não possa aprender, <small>nem tão pequeno que não possa ensinar</small>"</blockquote>
        <p>Temos também a tag "sup" que é designada para "superscript text", ou seja, texto sobrescrito, que é utilizado quando precisamos utilizar um pequeno caracter acima da linha normal. Alguns exemplos são uma marca registrada, utilizações matemáticas, fórmulas químicas e etc.</p>
        <blockquote>Adidas<sup>R</sup>, H<sup>2</sup>O, 16<sup>2</sup>.</blockquote>
        <p>A tag "sub" é justamente para fazer o contrário, ou seja, é utilizado para escrever um texto com letras menores e com o alinhamento abaixo das que do resto do conteúdo:</p>
        <blockquote>C<sub>6</sub>H<sub>6</sub></blockquote>
        <p>Já a tag "hr" representa uma quebra temática entre elementos de nível de parágrafo (por exemplo , uma mudança da cena de uma história, ou uma mudança de tema com uma seção)</p>
        <blockquote><p>COISAS QUE IREI REALIZAR EM 2023</p></blockquote>
        <hr>
        <ul> <li> Passar no mestrado</li>
            <li>Ler 24 livros</li>
            <li>Subir no Pico do Itacolomi</li>
        </ul>
        <p>A tag "del" representa uma parte do texto que foi excluída de um documento: <del>This text has been deleted</del></p>
        <p>Por fim, a tag "abbr" representa uma abreviação e opcionalmente fornece uma descrição completa para ela.</p>
        <p>Essas são apenas alguns exemplos de tags de texto. Outros exemplos podem ser achados no site <a href="https://www.w3schools.com/">W3Schools</a>.</p>
        <h2 id="listas-ol-ul" style="color:rgb(255, 0, 149)">Listas Ordenadas e Não Ordenadas</h2>
        <small><a href="#início">Voltar ao início</a></small>
        <p>Existem basicamente dois tipos de listas, as ordenadas e as não ordenadas. Para as listas ordenadas, a tag utilizada será "ol" de "ordered lists", que em português significa listas ordenadas. Essa tag tem uma particularidade porque ela não aceita colocar vários textos em linhas uma em baixo da outra. A tag precisa das "filhas" para poder funcionar. Quando falamos em "tag filha" significa uma tag dentro de outra</p>
        <p>Para isso utilizamos a tag "li" (list item-item da lista), e assim colocar um embaixo do outro. Exemplo:
            <blockquote> <ol><strong>Lista Supermercado</strong>
                            <li>Mamão</li>
                            <li>Morango</li>
                            <li>Atum</li>
                            <li>Papel toalha</li>
                            <li>Detergente</li>
                            <li>Sabão Líquido</li>
            </ol>
            <p>Como se trata de uma lista ordenada, o navegador irá entender que existe uma ordem, logo colocará números nos itens. Uma outra observação importante, é que podemos colocar outra lista dentro da lista.</p>
            <p>Já para as listas não ordenadas utilizamos a tag "ul", que serve para usarmos marcadores ao invés de números:</p>
<blockquote> <ul><strong>Lista Supermercado</strong>
<li>Mamão</li>
<li>Morango</li>
<li>Atum</li>
<li>Papel toalha</li>
<li>Detergente</li>
<li>Sabão Líquido</li></ul>

              
        
       

    </body>
</html>
