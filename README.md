Receita
🟩 Linguagem e Estrutura

O documento está escrito em HTML e começa com a tag <html lang="pt-br">, indicando que o idioma da página é português do Brasil.

🧠 Estrutura do Código
<head> (linhas 3 a 5)

A tag <head> está presente, mas está vazia. É onde normalmente se colocam informações como o título da página, links para CSS, metadados etc.

<body> (linhas 6 a 33)

É onde fica o conteúdo visível da página.

📸 Imagem da Receita:
<figure>
    <img src="pudim-de-pão-.png" alt="" width="500">
</figure>


Mostra uma imagem chamada pudim-de-pão-.png, com largura de 500 pixels.

Está dentro da tag <figure>, usada para agrupar imagens e legendas (embora não haja legenda aqui).

📝 Ingredientes (linhas 13 a 23):
<h2>Ingredientes</h2>
<ul style="list-style: -moz-element();">


<h2> é o título "Ingredientes".

A lista é uma lista não ordenada (<ul>), mas com um estilo estranho: list-style: -moz-element();, que não é válido para CSS moderno e pode não funcionar corretamente.

Itens da lista:

4 ovos

1 lata de leite condensado

3 pães

1 colher de margarina

2 medidas de leite

1/2 xícara de açúcar

1 xícara de açúcar para a calda

👨‍🍳 Modo de preparo (linhas 24 a 31):
<h3>Modo de preparo</h3>
<ol>


<h3> indica o título da seção.

A lista é ordenada (<ol>), usada para mostrar passo a passo.

Passos:

Misture todos os ingredientes no liquidificador e bata bem.

Reserve.

Em uma forma própria para pudim, derreta o açúcar para fazer a calda, espere endurecer um pouco e coloque o líquido.

Leve ao fogo por uns 35 minutos ou até o garfo sair limpo.

link

🧠 Cabeçalho
</head>


O </head> aparece, mas está faltando a abertura <head> e possíveis metadados como <title> ou <meta charset="UTF-8">.

📄 Corpo da Página (<body>)
<body>
    <h1>Inserindo imagens</h1>


Um título de nível 1 dizendo "Inserindo imagens".

    <p>Yakuza 0, ambientado no ano de 1988, conta a história de Kazuma Kiryu e Goro Majima, explorando seus passados e como eles se tornaram figuras proeminentes na organização Yakuza.</p>


Um parágrafo explicando o enredo do jogo Yakuza 0.

    <hr>


Uma linha horizontal para dividir visualmente seções do conteúdo.

    <img src="Yakuza0.png" alt="" width="900">


Um elemento de imagem:

src="Yakuza0.png" → o arquivo da imagem.

alt="" → texto alternativo (aqui está vazio).

width="900" → largura da imagem será 900 pixels.

    <hr>


Outra linha horizontal.

    <p>Este <a href="https://wallpapersafari.com/w/dLx3q4/download" target="_blank">link</a> vai para o google</p>


Um parágrafo com um link:

href="..." → link para download de um wallpaper.

target="_blank" → abre o link em uma nova aba.

Texto visível do link: "link".

Mas a frase fora do link está um pouco confusa: "vai para o google" (o link não vai para o Google, vai para um site de wallpapers).

📦 Finalização
</body>
</html>


Fecha o corpo e o HTML da página.
