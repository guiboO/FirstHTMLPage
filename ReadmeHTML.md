TAGS: (sempre com abertura e fechamento </>)
TAGS usadas para estruturar uma página:
<html> - Toda a página.
    <title> - Nome que vai aparecer na aba do navegador.
<head> - tudo que vai ser corregado antes de aparecer a página para o usuário.
<body> - Todo o corpo da página. O que realmente vai aparecer para o usuário na página.
<header> - Cabeçalho da página, aonde pode ser feito um menu, navbar, etc.
<footer> - Rodapé da página, aonde pode ser colocado contatos, quem desenvolveu, copyrights, etc.
<div> - Define uma divisão no Documento HTML que é usada como um container para diversos elementos HTML. que depois podem ser manipulados através do CSS ou JavaScript. Uma classe ou id podem ser atribuídas para ser facilmente manipulada.
<nav> - Define um conjunto de links, um menu de navegação pelo site.

TAGS usadas para textos:
<section> - Representa uma seção genérica contida em um documento HTML, para exibir resultado de pesquisa, mapas, imagens, em sua maioria para usar com textos.
<article> - Meio que um filho da tag <section>. Usado para distribuir, desestruturar o conteúdo de uma Section. Ex: Artigos, Post de Fórum, Notícias.
<aside> - Usado para explicar algo em específico do Texto a sua volta que está em um <p>, <section> ou <article>
<h1 a h6> - Títulos de diferentes níveis, tamanho e importância.
<p> - Usado para parágrafos, dar corpo ao texto.
<blockquote> - Usado para citações, uma observação
<q> - Usado também para citações com "".
<strong> - Deixa em negrito.
<i> - Deixar o texto em itálico.
<u> - Deixar o texto sublinhado.
<mark> - Deixa como marca texto.
<small> - Deixa o texto um pouco menor. Legal para legendas de fotos por exemplo ou letras miúdas de uma promoção.
<sup> - Escreve um símbolo ou texto axima da linha, como um * ou um elevado a...
<em> - Deixa o texto mais enfático. Deixa o texto com aparência de itálico, porém o navegador vai ler com mais ênfase.
<address> - Usado para definir um endereço, uma informação de contato (autor/dono) de um artigo ou documento.
<a> - Define um Hyperlink, usado para inserir um link no HTML. Sempre usado com o atributo href=""
    

Existe TAGS que não tem fechamento, e são colocadas alguns atributos dentro delas que mudam o comportamento, como:
<input> - Adicionar um campo para escrever nele no HTML. Muito usado em formulário
<img> - Colocar uma imagem no HTML.

TAGS para listas:
<ol> - Usado para listas ordenadas que são colocados números a frente das linhas.
<ul> - Usado para listas não ordenadas, são colocados marcadores a frente das linhas.
    <li> - Sempre usado junto das duas Tags acima para representar cada linha/item das listas.
<dl> - Usado para listas de descrição.
    <dt> - Usado para definir o nome de cada item desse tipo de lista.
        <dd> - Usado para definir a descrição dos itens do <dt>.

Atributos das tags:
id="" - Usado para identificar um elemento/tag, dar uma identidade à ele. Não pode dar o mesmo id para duas tags diferentes. Para puxar no CSS usa-se "#id".

class="" - Usado para classificar uma tag/elemento. Pode ser usado a mesma classe para tags diferentes. Para puxar no CSS usa-se ".class" e todos com essa  classe será formatado.

type="" - Usado junto com a tag <input> e possui valores diferentes: text, number, color...

src="" - Usado muitas vezes com a tag <img> e significa o caminho/fonte/endereço da imagem que vc colocar.

alt="" - Usado muitas vezes com a tag <img> e significa o nome para imagem quando ela não carregar.

href="" - Atributo mais importante e sempre usado com a tag <a>. Dentro das "" que vai ser colocado o link do destino.

target="" - Atributo do link, usado com a tag <a> para especificar como vai abriro link quando clicado. Por padrão o link é aberto na mesma página.
    target="_blank" - O link será aberto em outra Aba.

title="" - Usado com a tag <a> para quando deixar o mouse em cima do link, aparecer um balãozinho com o texto colocado entre "".

mailto: - Usado dentro do atributo href="" para criar um link que abre o programa de email do usuário, assim deixando ele enviar um novo email para o destinatário inserido.
    Ex: <a href="mailto:someone@example.com">Send email</a>
