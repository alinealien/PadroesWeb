## PADRÕES WEB

Repositório de estudos e projetos desenvolvidos durante a disciplina de **Padrões Web** do curso de Tecnologia em Sistemas para Internet do IFRN.

## Unidade I

### **História e Arquitetura da Internet**

A história da internet começa com a criação dos mainframes na década de 1950. Estes eram grandes computadores usados por empresas e governos para processar dados, principalmente bancários e científicos. Apesar de inicialmente serem caros e inacessíveis à maioria das pessoas, a evolução tecnológica os tornou mais acessíveis e com maior capacidade.

O engenheiro Robert Metcalfe da Xerox foi fundamental ao inventar a Ethernet em 1973. Essa tecnologia permitiu a comunicação em rede entre computadores, revolucionando o compartilhamento eficiente de informações e recursos empresariais. A Ethernet também possibilitou a criação de redes locais (LANs) mais seguras e confiáveis que protegiam dados sensíveis.

A adoção generalizada da Ethernet nas décadas seguintes impulsionou o crescimento das redes, culminando em seu papel central na comunicação online. Hoje, a Ethernet é a base das redes locais e uma tecnologia essencial para a internet.



### ArpaNET e a crise dos mísseis

Em 1969, a Agência de Projetos de Pesquisa Avançada do Departamento de Defesa dos Estados Unidos criou a ArpaNET, uma rede de computadores destinada a permitir a comunicação entre cientistas e pesquisadores em todo o país.

Na década de 1980, a ArpaNET se expandiu, formando a base da atual Internet. Durante a crise dos mísseis de 1983, a ArpaNET foi crucial para a comunicação entre líderes globais, como Reagan e Andropov, evitando um conflito nuclear iminente. A rede segura transmitiu mensagens criptografadas, permitindo cooperação entre líderes militares dos EUA e aliados. Isso revelou o potencial global da tecnologia de rede. A ArpaNET e a Internet se tornaram vitais para colaboração e comunicação em crises, como desastres naturais e ataques terroristas. A Internet permanece uma ferramenta essencial em tempos críticos.

Na década de 1970, redes como Cyclades e NPL surgiram globalmente. Em 1978, elas se uniram à ArpaNET, formando uma rede global. Essa expansão fez da Internet crucial para comunicação, pesquisa e comércio globais. A fusão trouxe tecnologias cruciais, como o TCP/IP, padronizando a comunicação online. O TCP/IP divide dados em pacotes para entrega segura. Nos anos 1990, a Internet se democratizou com a World Wide Web (WWW), criada por Tim Berners-Lee do CERN. Isso permitiu acesso e compartilhamento intuitivos, graças a protocolos como o HTTP e a linguagem HTML.


### Arquitetura da Internet

A internet é uma arquitetura complexa que interliga dispositivos eletrônicos em todo o mundo. Ela se baseia em clientes (dispositivos usados pelos usuários) e servidores (que fornecem informações). A interação entre eles é central. Quando um cliente faz uma solicitação, um servidor responde, gerando tráfego de rede. Roteadores encaminham dados seguindo regras TCP/IP, cruciais para a comunicação. A arquitetura TCP/IP tem 4 camadas: Aplicação (navegadores, e-mail), Transporte (TCP confiável, UDP rápido), Internet (endereçamento e roteamento) e Rede (transmissão física).

A camada TCP garante envio confiável, dividindo dados em pacotes. A camada de Internet cuida de endereçamento e roteamento. Switches conectam dispositivos em LANs. Para segurança, firewalls protegem contra ameaças. O HTTP e HTML permitem acesso a recursos online, enquanto JavaScript adiciona interatividade.

No lado do servidor, linguagens como PHP e Python são usadas, enquanto JavaScript domina o lado do cliente, trazendo dinamismo. A arquitetura TCP/IP, controle de tráfego, segurança, roteadores, endereçamento IP e criação de páginas web são partes essenciais desse sistema.


### Marcação de Texto e Sintaxe HTML

Navegadores da Web interpretam HTML, CSS e JavaScript para mostrar páginas visualmente agradáveis. Exemplos são Chrome, Firefox, Edge, Safari e Opera. Eles permitem inserção de URLs, navegação por links, visualização de imagens, conteúdo multimídia e têm recursos como preenchimento automático, bloqueio de anúncios e extensões personalizadas. Navegadores evoluíram com suporte a HTML5, CSS3 e WebGL, tornando-se mais rápidos, seguros e versáteis para acessar serviços online, como redes sociais, bancos e streaming. No entanto, há alternativas para explorar a web.

Além de navegadores, diversos programas e serviços conectam-nos online. Apps de mensagens permitem comunicação rápida, chamadas e videoconferências. Serviços de streaming oferecem música, podcasts e 
vídeos. A nuvem é popular para armazenar e compartilhar arquivos, sendo acessível de qualquer dispositivo. Essas opções baseiam-se na WWW, a espinha dorsal da internet moderna.

A linguagem HTML usa elementos ou tags para organizar e mostrar o conteúdo no navegador. Cada elemento tem uma marca de abertura (<tag>) e fechamento (</tag>), com conteúdo no meio. Essas tags definem parágrafos, títulos, links, imagens, tabelas, etc. A HTML também usa atributos para controle, como cores e tamanhos. A estrutura é uma árvore hierárquica de elementos, definindo a semântica e lógica do documento para correta exibição.

O HTML evoluiu, resultando em versões diferentes, incluindo a mais recente, HTML5. Essa versão trouxe recursos avançados como mídia integrada, gráficos vetoriais e formas aprimoradas. O HTML5 possibilita 
apps web mais interativos. Junto ao CSS e JavaScript, é fundamental para criar páginas web atrativas e dinâmicas, tornando conteúdo acessível, legível e interativo para os usuários.



##### **Objetivos da Unidade:**

- Os primeiros mainframes e a Ethernet;
- ArpaNET e a crise dos mísseis;
- O que são Serviços Web e Protocolo HTTP;
- Diferenças entre Linguagens do lado do cliente e do servidor;
- O que é Marcação de texto;
- Sintaxe HTML.




______________

## Unidade II

### HTML: HyperText Markup Language

HTML (HyperText Markup Language) é uma linguagem de marcação para criar páginas web, permitindo estruturar títulos, parágrafos, listas, imagens elinks. Inicialmente, a falta de padronização trouxe confusão aos desenvolvedores. Em 1990, o HTML foi formalizado e padronizado. Em 1994,Tim Berners-Lee fundou o W3C para padronizar a World Wide Web (web ou internet).

O W3C é um consórcio global que reúne equipe integral, afiliados e público para criar padrões web. Liderado por Tim Berners-Lee e CEO Jeffrey Jaffe, visa desenvolver protocolos e diretrizes para impulsionar o potencial da web.

#### Estrutura do HTML

HTML usa marcações ("<" e ">") para definir estrutura e formato. Tags como  `<h1>`para títulos e  x `<p>` para parágrafos são exemplos. Editores modernos consideram tamanhos de tela e idiomas, adicionando tags meta.

#### Formatação de Texto

O formato e destaque do texto em páginas web influenciam a experiência do usuário. A linguagem HTML oferece marcações para aplicar estilos, resultando em apresentação atraente e legível. 

O site w3schools.com é uma fonte útil para explorar formatação e marcação HTML, com uma biblioteca completa de tags e informações detalhadas. Isso permite aprender sobre novas tags, suas funções e como usá-las no código HTML.

| Marcação       | Função                                   |
| -------------- | ---------------------------------------- |
| `<b>`          | Coloca o texto em negrito                |
| `<i>`          | Coloca o texto em itálico                |
| `<em>`         | Nova recomendação, faz o mesmo que a tag i |
| `<strong>`     | Nova recomendação, faz o mesmo que a tag b |
| `<u>`          | Sublinha o texto                         |
| `<sup>`        | Eleva o texto (sobrescrito)              |
| `<sub>`        | Baixa o texto (subscrito)                |
| `<del>`        | Exibe o texto como tachado (riscado)     |
| `<mark>`       | Marca o texto com destaque               |
| `<blockquote>` | Citação em bloco                         |
| `<ins>`        | Coloca um traço sob o texto para marcar que o referido trecho foi incluindo no texto original |
| `<code>`       | Formata o texto como código              |
| `<small>`      | Coloca o texto em destaque, diminuindo seu tamanho em relação ao tamanho padrão |
| `<pre>`        | Preserva a formatação de texto (pré-formatado) |
| `<abbr>`       | Define uma abreviação                    |

##### Atenção:

Devido a uma limitação em meu editor, por enquanto, retirei os símbolos de das tags <> e seu fechamento </>. Lembre-se sempre, as tags, por padrão seguem o modelo:

```html
<div>text</div>

<!--Abriu-->
<div> text 
<!--Fechou-->
</div>
```



#### Hyperlinks em HTML

Os hipertextos, também conhecidos como hyperlinks ou simplesmente links, são elementos 
essenciais no HTML para conectar e navegar entre diferentes páginas da web. Eles permitem que os usuários cliquem em um texto ou imagem e sejam direcionados para outra página, um local específico na mesma página ou até mesmo para um recurso externo. No HTML, os hipertextos são criados 
usando a tag `<a>`. Essa tag é acompanhada pelo atributo `href` que indica o destino do link, ou seja, a URL da página para a qual o usuário será redirecionado ao clicar no link. Por exemplo:

```html
 <a href="<https://www.example.com> "> Clique aqui </a> criará um link com o texto "Clique aqui" 
```

Levará o usuário para o endereço "<https://www.example.com>".

Os hipertextos podem ter atributos adicionais, como "target", que determina onde o conteúdo será aberto (na mesma janela, em uma nova aba ou em um frame) e "title", que fornece uma descrição ou dica quando o usuário passa o mouse sobre o link. Os hipertextos podem ser aplicados a qualquer elemento de texto ou imagem em uma página web, permitindo que os usuários naveguem facilmente entre diferentes seções do site ou acessem recursos externos relevantes. 

É importante usar links de forma clara e significativa para fornecer uma experiência de navegação 
intuitiva e facilitar a descoberta de conteúdo relevante. Além dos Hyperlinks, existem os Links de âncora (*Anchor Links*), também conhecidos como "links internos" ou "links de navegação interna". Eles são elementos em HTML que permitem aos usuários acessarem seções específicas de uma mesma página. Eles são úteis quando se tem um conteúdo longo, como uma página com vários tópicos ou um artigo 
extenso, e deseja-se permitir que os usuários naveguem diretamente para uma seção específica, sem precisar rolar toda a página.

Para criar um link de âncora, você precisa adicionar uma tag de âncora à seção de destino e referenciá-la no link. Primeiro, coloque uma tag  `<a>` com um atributo "name" ou "id" na seção para a qual deseja criar o link de âncora. Por exemplo: 

```html
<h2 id="secao1">Seção 1</h2> ou <div id="secao2">Conteúdo da Seção 2</div>
```


Em seguida, você pode criar um link que referencia essa âncora usando o atributo "href" com o valor "#" seguido pelo nome ou ID da âncora. Por exemplo:

```html
<a href="#secao1">Ir para a Seção 1</a>
```


Ao clicar no link de âncora, o navegador irá rolar automaticamente para a seção específica da página identificada pelo nome ou ID da âncora. Isso proporciona aos usuários uma maneira conveniente de navegar rapidamente para seções de interesse em páginas com muito conteúdo vertical. 
Os links de âncora são particularmente úteis em páginas longas, como tutoriais, documentos extensos ou páginas de perguntas frequentes, onde os usuários podem desejar pular diretamente para uma seção específica. Eles melhoram a usabilidade, facilitando a navegação interna e tornando mais fácil para os usuários encontrarem as informações desejadas em uma página extensa.
​            

#### Imagens e Vídeos em HTML

A inserção de imagens e vídeos no HTML é uma forma essencial de enriquecer e visualmente atrair as páginas da web. Para inserir uma imagem, você pode usar a tag `<img>`. Essa tag requer o atributo obrigatório "src", que especifica o caminho ou URL da imagem. Por exemplo: 

```html
<img src="caminho/para/imagem.jpg" alt="Descrição da imagem">
```

O atributo "alt" fornece uma descrição alternativa para a imagem, que é exibida caso a imagem não 
possa ser carregada ou para fins de acessibilidade.

Para inserir vídeos, você pode usar a tag `<video>`. Essa tag permite a reprodução de vídeos diretamente na página. Você precisa definir o atributo "src" com o caminho ou URL do vídeo e pode especificar outros atributos, como "width" e "height", para definir as dimensões do vídeo na página. Por exemplo: 

```html
   <video src="caminho/para/video.mp4" width="500" height="300" controls></video>
```

O atributo "controls" mostra os controles de reprodução do vídeo. Vídeos de plataformas como YouTube podem ser incorporados usando código fornecido, geralmente um iframe. Adicionar imagens e vídeos no HTML é eficaz para transmitir informações visualmente, tornando as páginas web mais atrativas e interativas.

**Lembre-se:** de otimizar imagens e vídeos para a web, ajustando o tamanho do arquivo e a compatibilidade com navegadores. Adicionalmente, forneça descrições alternativas (atributo "alt") para imagens, melhorando acessibilidade e indexação em mecanismos de busca.



#### Listas em HTML

No HTML, é possível criar listas ordenadas e não ordenadas para estruturar informações de maneira organizada. As listas aprimoram a compreensão e legibilidade do conteúdo.

Para criar uma lista não ordenada, utilize a tag `<ul>` para representar a lista e marque cada item com `<li>`. Por exemplo:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

Este código resultará em uma lista não ordenada com os itens "Item 1", "Item2" e "Item 3", sendo exibidos com pontos ou marcadores como vemos na imagem acima.

Para criar uma lista ordenada, use a tag `<ol>` para representar a lista e marque cada item com `<li>`. Veja o exemplo abaixo:

```html
<ol>
  <li>Primeiro item</li>
  <li>Segundo item</li>
  <li>Terceiro item</li>
</ol>
```

Este código gera uma lista ordenada com os itens "Item 1", "Item 2" e "Item 3", numerados sequencialmente. Também é possível criar listas aninhadas, com uma lista dentro de outra, ao aninhar as tags `<ul>, <ol>, <li>`

Exemplo:

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  <ul>
    <li>Subitem 3.1</li>
    <li>Subitem 3.2</li>
  </ul>
</ol>
```

Aqui, temos uma lista não ordenada com três itens. O segundo item contém uma lista não ordenada aninhada com os itens "Item 2.1" e "Item 2.2". As listas em HTML organizam informações de modo eficiente e claro. As tags `<ul>, <ol> e <li>` são cruciais para formatar listas, desde as simples até as complexas com aninhamentos. Posteriormente, aprenderemos a transformar essas listas em menus interativos para páginas. Exemplo:

```html
<ul>
  <li>Item 1</li>
  <li>
    Item 2
    <ul>
      <li>Item 2.1</li>
      <li>Item 2.2</li>
    </ul>
  </li>
  <li>Item 3</li>
</ul>
```



### CSS: Cascading Style Sheets

#### ID e Classes em CSS

CSS (Cascading Style Sheets) é uma linguagem de estilo utilizada em conjunto com o HTML para definir a aparência e o design de páginas web. Com o CSS, você pode controlar o layout, as cores, as fontes, as animações e outros aspectos visuais de um documento HTML, permitindo uma personalização completa da aparência do conteúdo.

O CSS funciona selecionando elementos HTML e aplicando regras de estilo a eles. As regras de estilo são definidas em blocos de declarações que consistem em um seletor e uma propriedade com o valor correspondente. O seletor indica qual elemento HTML será afetado e a propriedade define qual característica desse elemento será estilizada. Podemos observar a estrutura básica do CSS no exemplo:

```css
/*Selector*/
p{
 /*Declaração*/
  color: black;
}
/*Color é a propriedade e black é o valor*/
```

Neste exemplo, o seletor "p" seleciona todas as tags `<p>` do HTML, a propriedade "color" determina a cor da fonte e o valor "red" determina que a cor vai ser vermelha. Ou seja, a declaração desta regra diz que todo o texto que estiver em uma tag `<p>`

deverá ser por padrão vermelho.


Em CSS, IDs e classes são seletores para aplicar estilos a elementos específicos ou grupos em uma página web. IDs identificam elementos únicos, enquanto classes agrupam elementos similares. Para aplicar 
estilos a um ID, utilize "#" seguido do nome do ID, definido no HTML com o atributo "id". Por exemplo:

```html
<div id="meu-id">...</div>
```

Neste caso, apenas o elemento com o ID "meu-id" receberá a regra.

Classes, por outro lado, são reutilizáveis. Defina-as no HTML com o atributo "class". As regras de classe podem ser aplicadas a várias tags com a mesma classe. Exemplo:

```html
<p class="destaque">...</p>
<div class="destaque">...</div>
```

As duas tags acima compartilham a regra "destaque".

**Quando há conflito de regras, a prioridade é definida por:**

1. Regra aplicada via atributo "style";
2. Regra aplicada via ID;
3. Regra aplicada via classe;
4. Regra aplicada via tag.

Em um exemplo:

```html
<p id="minha-id" class="destaque" style="color: blue;">Paragrafo</p>
```

A cor será azul, pois a regra do atributo "style" tem maior prioridade. Quanto mais específica a regra, maior a prioridade.

​                

#### Príncipais Regras CSS

Com o CSS, é possível aplicar diversos estilos a textos, fontes, cores e fundos em páginas web. Para estilizar textos, você pode usar propriedades como "font-family" para definir a fonte utilizada, "font-size" para o tamanho do texto e "font-weight" para controlar a espessura da fonte:

```css
p {
  font-family: Arial;
  font-size: 16px;
  font-weight: bold;
}
```

Nesse exemplo, o parágrafo `<p>` terá o texto exibido em fonte Arial, tamanho de 16 pixels e em negrito. Além disso, você pode definir a cor do texto usando a propriedade "color". Por exemplo:

```css
p {
  color: red;
}
```

Nesse caso, o texto do parágrafo `<p>` será exibido na cor vermelha. Quanto ao background, você pode definir a cor de fundo de um elemento com a propriedade "background-color". Por exemplo:

```css
body {
  background-color: #f2f2f2;
}
```

Neste caso, o fundo da página inteira terá uma cor cinza claro definida pelo código hexadecimal "#f2f2f2". Além da cor, você pode adicionar uma imagem de fundo usando a propriedade "background-image". Por exemplo:

```css
body {
  background-image: url(caminho/para/imagem.jpg);
}
```

Neste exemplo, a página terá uma imagem como fundo, onde "caminho/para/imagem.jpg" é o local e o nome da imagem. Lembre-se de que as definições de locais de arquivos seguem o modelo Unix, com "./" para a pasta atual e "../" para a pasta anterior. Nas próximas aulas, aprenderemos diversas formas de usar o CSS, fazer animações, trabalhar com áudio e vídeo, e criar formulários em HTML.

##### Objetivos da Unidade:

- HTML - Resumo
- Estruturas do HTML
- Formatação de textos
- Hyperlinks em HTML
- Imagens e Vídeos em HTML
- Listas em HTML
- CSS - Resumo
- ID e classes em CSS
- Principais regras CSS


_______________

## Unidade III



#### Tabelas em HTML

As tabelas são elementos estruturais essenciais no **HTML**, permitindo a organização e exibição de dados em linhas e colunas de forma clara e sistemática. Uma das principais vantagens das tabelas é a capacidade de visualizar dados comparativos. Ao dispor informações lado a lado, torna-se mais fácil analisar e entender padrões, diferenças e tendências entre os dados apresentados.

Outra aplicação prática das tabelas é a exibição de listas de informações. Quando temos dados categorizados, como listas de produtos, características ou eventos, as tabelas oferecem uma maneira ordenada e concisa de apresentá-los. Os usuários podem facilmente encontrar o que procuram e comparar as informações de interesse.

Além disso, as tabelas são ideais para criar calendários. Ao organizar datas em colunas e dias da semana em linhas, os calendários se tornam mais legíveis e facilitam o planejamento e acompanhamento de 
eventos, prazos e compromissos. Entretanto, é importante evitar o uso excessivo de tabelas para fins de layout. 

#### Estrutura da tabela em HTML

A estrutura de uma tabela em HTML é fundamental para organizar e apresentar informações de maneira clara e acessível. A tabela é delimitada pela tag `<table>`, a qual marca o início do elemento tabular. O conteúdo contido dentro desta tag é estruturado em três seções principais: o cabeçalho `(<thead>)`, o corpo `(<tbody>)` e o rodapé `(<tfoot>)`. A adoção dessa divisão, embora opcional, é altamente recomendada, uma vez que confere à tabela maior semântica, facilitando a compreensão por leitores de tela e a indexação por mecanismos de busca.

A construção de linhas na tabela é realizada por meio da tag `<tr>` (table row), onde cada linha representa um conjunto horizontal de células. As células individuais são inseridas dentro das linhas utilizando as tags `<td>` (table data) e `<th>` (table header). A tag `<td>` é empregada para criar células regulares que contêm os dados da tabela. Em contraste, a tag `<th>` é utilizada para desenvolver os cabeçalhos de coluna, ou seja, os títulos que representam as informações contidas nas células abaixo deles. Essa distinção entre `<td>` e `<th>` também se revela valiosa para a estilização adequada da tabela, permitindo a aplicação de diferentes estilos aos cabeçalhos, caso necessário. Exemplo a seguir:

```html
<table> <!--Abre Tabela-->
    <thead> <!-- Defini os cabeçalho da tabela -->
        <tr> <!--Cria uma linha-->
            <th>Produto</th> <!--Cria cabeçalhos-->
            <th>Preço</th> <!--Cria cabeçalhos-->
            <th>Disponibilidade</th> <!--Cria cabeçalhos-->
        </tr> <!--Fecha a Linha-->
    </thead> <!--Fecha o cabeçalho-->
    <tbody> <!-- Defini o corpo da tabela. -->
        <tr> <!--Cria outra linha-->
            <td>Camiseta branca</td> <!--Cria células(colunas)-->
            <td>R$ 29,99</td> <!--Cria células(colunas)-->
            <td>Em estoque</td> <!--Cria células(colunas)-->
        </tr>  <!--Fecha a Linha-->
        <tr> <!--Cria outra linha-->
            <td>Calça jeans</td> <!--Cria células(colunas)-->
            <td>R$ 59,99</td> <!--Cria células(colunas)-->
            <td>Esgotado</td> <!--Cria células(colunas)-->
        </tr>  <!--Fecha a Linha-->
        <tr><!--Cria outra linha-->
            <td>Tênis esportivo</td> <!--Cria células(colunas)-->
            <td>R$ 89,90</td> <!--Cria células(colunas)-->
            <td>Em estoque</td> <!--Cria células(colunas)-->
        </tr>  <!--Fecha a Linha-->
    </tbody>  <!--Fecha o corpo da tabela-->
</table> <!--Fecha Tabela-->

```

Uma característica importante das tabelas é a possibilidade de mesclar células, o que pode ser feito utilizando os atributos `colspan` e `rowspan`. O atributo **colspan permite mesclar horizontalmente células** que se estendem por mais de uma coluna. Enquanto isso, o atributo r**owspan possibilita a mesclagem vertical de células**, abrangendo mais de uma linha. Essa funcionalidade é especialmente útil quando queremos destacar informações importantes ou simplificar a apresentação dos dados. 



#### Tabelas e CSS

As tabelas HTML, quando combinadas com CSS, oferecem um potencial ampliado de personalização e melhoria de layout. O CSS permite definir cores de fundo, espaçamento e bordas, contribuindo para uma apresentação atraente e legível das tabelas. Além disso, é possível aplicar estilos específicos a cabeçalhos e rodapés, realçando essas seções com cores distintas e fontes diferenciadas. Destacar células com estilos personalizados é outra vantagem, permitindo a aplicação de cores específicas a valores relevantes ou acima de um limiar, direcionando o foco para informações cruciais. Além disso, o CSS facilita a gestão de conteúdo com rolagem horizontal, útil quando a tabela possui muitas colunas, evitando distorções no layout ao adicionar uma barra de rolagem horizontal.

```css
/* Estilo para a tabela com rolagem horizontal */
.scrollable-table {
  width: 100%;
  overflow-x: auto;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  padding: 8px;
  text-align: left;
}
```



```html
<!-- No corpo do documento HTML -->
<div class="scrollable-table">
  <table>
    <!-- Conteúdo da tabela aqui -->
  </table>
</div>
```

Neste exemplo, a classe `scrollable-table` é usada para criaruma tabela com rolagem horizontal quando o conteúdo excede a largura da tela. Isso mantém o layout da tabela intacto e permite que os usuários visualizem todas as informações com facilidade.


#### Formulários em HTML

Os formulários em **HTML **são elementos essenciais nas páginas da web, pois desempenham um papel fundamental na coleta de informações dos usuários. Eles possibilitam a criação de campos de entrada, botões de envio e outros elementos interativos que tornam a experiência do usuário mais dinâmica e participativa. Os formulários também podem conter opções de escolha, como botões de rádio e caixas de seleção, que permitem aos usuários fazerem escolhas entre diversas opções pré-definidas. 

```html
<!DOCTYPE html>
<html>
<head>
<style>
  form {
    width: 400px;
    margin: auto;
  }

  label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
  }

  input[type="text"],
  textarea {
    width: 100%;
    padding: 8px;
    margin-bottom: 16px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }

  textarea {
    resize: vertical;
  }

  .align-right {
    text-align: right;
  }

  button {
    padding: 8px 16px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
</style>
</head>
<body>

<h2>Formulário</h2>

<form>
  <label for="name">Nome:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="text" id="email" name="email" required>

  <label for="message">Mensagem:</label>
  <textarea id="message" name="message" rows="6" required></textarea>

  <div class="align-right">
    <button type="submit">Enviar</button>
  </div>
</form>

</body>
</html>

```

Os botões de envio são essenciais para submeter dados de formulários. Eles são fundamentais em sistemas de login, envio de mensagens e interações importantes. Formulários podem ter elementos interativos, como campos de data e seletores de arquivos, melhorando a interação. A segurança e a conformidade com políticas de privacidade são cruciais ao lidar com dados coletados por formulários.



#### Tags de Formulários

Os formulários HTML são essenciais para interação e coleta de informações. Eles usam tags para criar campos, botões e elementos interativos, aprimorando a experiência do usuário.

A tag `<form>` delimita o formulário e possui atributos como "action" (processamento) e "method" (envio de dados).

Exemplo de código de formulário em HTML:

```html
<form action="/script.php" method="POST">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="mensagem">Mensagem:</label>
  <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

  <button type="submit">Enviar</button>
</form>

```

Tags dentro de `<form>`:

- `<input>` cria campos variados, como texto e checkboxes.
- `<button>` cria botões, inclusive envio ou customizados.
- `<label>` gera rótulos para campos.
- `<select>` e `<option>` criam dropdowns de seleção.
- `<textarea>` permite texto multilinhas.

Essas tags, combinadas com CSS e JavaScript, oferecem interatividade e personalização. Utilizá-las adequadamente garante formulários funcionais e seguros para coletar dados essenciais.


#### Tags de Bloco e CSS

As tags HTML desempenham um papel central na construção de páginas web, permitindo criar elementos e formatar conteúdo. Elas se dividem em duas categorias: tags de linha e tags de bloco, cada uma com usos específicos.

As tags de linha ocupam apenas o espaço necessário para o conteúdo, mantendo-se na mesma linha. Exemplos são `<span>`, `<a>`, `<img>` e `<input>`. São úteis para elementos pequenos, interativos ou estilísticos.

As tags de bloco ocupam todo espaço horizontal, começando em nova linha. São adequadas para elementos maiores como parágrafos, títulos, listas e divisões de seções. Escolher a tag certa é crucial para o layout e semântica corretos.

Exemplo de tags de bloco em HTML:

```html
<p>Parágrafo de exemplo.</p>
<h1>Título de Exemplo</h1>
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<div>
  <p>Conteúdo em uma divisão.</p>
</div>

```

A seleção correta entre essas categorias garante a hierarquia visual e o layout desejados na página.



#### Content, Padding, Border e Margin

A estrutura espacial na página HTML de uma `tag` de bloco é composta por quatro principais áreas:


<p align="center"><img src="https://raw.githubusercontent.com/alinealien/PadroesWeb/main/paginahtml_margins.png" alt="Exemplo de Página HTML"></p>




Em uma tag de bloco, temos três elementos essenciais:

1. **Conteúdo**: O núcleo da tag, exibindo texto, imagens ou outros elementos. É a parte visível do elemento na página.
2. **Preenchimento**: Espaço entre o conteúdo e a borda. Acrescenta espaço interno e destaque ao conteúdo.
3. **Borda**: Uma linha contornando o bloco, visualmente demarcando seu espaço. Pode ser personalizada com estilo, espessura e cor.

Além disso, temos a **margem**, que é o espaço entre o bloco e outros elementos adjacentes ou blocos na página. Cria separação visual entre elementos.

O CSS permite controlar esses aspectos, possibilitando ajustes no layout e na aparência dos blocos. Personalizar preenchimento, borda e margem oferece a designers a oportunidade de criar designs atraentes, alinhados com a identidade visual do site e proporcionando experiência agradável aos usuários.


#### Regras de Estado em CSS

As regras de estado em CSS desempenham um papel fundamental na criação de interações visuais nas páginas da web. Com base no estado atual de um elemento, é possível aplicar estilos diferentes, permitindo que os desenvolvedores personalizem a aparência dos elementos conforme as ações do usuário.

Alguns dos seletores de estado em CSS são:

- **:hover:** Aplica estilos quando o cursor do mouse está sobre o elemento. Ideal para efeitos de destaque em botões, links e imagens.
- **:active:** Aplica-se quando o usuário pressiona o botão do mouse sobre o elemento. É usado para simular uma resposta tátil.
- **:focus:** Aplicado quando o elemento está em foco após interação do usuário. Destaca campos de formulário.
- **:visited:** Permite estilizar links já visitados, diferenciando-os para uma navegação eficiente.
- **:first-child** e **:last-child:** Estiliza o primeiro e último filho de um elemento pai, sem a necessidade de classes ou identificadores.

Esses seletores de estado em CSS melhoram o design e interatividade das páginas. Proporcionam feedback imediato, enriquecendo a experiência do usuário e adicionando personalidade e dinamismo ao design do site.



#### Rich Media: Áudio e Vídeo

Rich Media, um termo sugestivo, envolve a inserção de conteúdo multimídia em páginas da web. Por meio de várias tecnologias e elementos HTML, vídeos, áudios, animações e gráficos podem ser incorporados, aprimorando o conteúdo e atraindo a atenção.

Vídeos são uma forma comum de utilizar Rich Media. Através das tags HTML `<video>` e `<source>`, desenvolvedores podem integrar vídeos em páginas web. Isso permite a reprodução de conteúdo audiovisual diretamente no navegador, proporcionando uma experiência visual envolvente.

Áudio também é facilmente adicionado usando as tags `<audio>` e `<source>`. Isso viabiliza a incorporação de arquivos de áudio, como músicas e podcasts, em sites que desejam oferecer tal conteúdo.

A tag `<canvas>` é outra ferramenta do Rich Media. Ela permite a criação de animações, gráficos e até jogos na página, com controle por JavaScript. Para conteúdo externo, as `<iframes>` entram em cena. Através delas, conteúdo de fontes externas, como mapas interativos e vídeos, pode ser integrado à página.

O Rich Media amplia a interatividade e atratividade das páginas web, contudo, equilíbrio é fundamental. A acessibilidade e a velocidade de carregamento devem ser ponderadas. Músicas e vídeos ao abrir uma página sem propósito podem prejudicar a experiência. Garantir compatibilidade com diferentes navegadores e dispositivos é essencial para oferecer a todos uma experiência agradável.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Rich Media</title>
</head>
<body>
    <h1>Vídeo Incorporado</h1>
    
    <video width="640" height="360" controls>
        <source src="exemplo-video.mp4" type="video/mp4">
        Seu navegador não suporta o elemento de vídeo.
    </video>
    
    <p>Este é um exemplo de incorporação de vídeo usando a tag &lt;video&gt;.</p>
</body>
</html>

```

Neste exemplo, estamos utilizando a tag `<video>` para incorporar um vídeo na página. O atributo `controls` adiciona controles de reprodução padrão, como play, pause e barra de progresso. A tag `<source>` é usada para fornecer os diferentes formatos do vídeo para suportar navegadores diferentes. O texto "Seu navegador não suporta o elemento de vídeo." é exibido caso o navegador não seja capaz de reproduzir o vídeo.

Certifique-se de substituir `"exemplo-video.mp4"` pelo caminho correto para o seu arquivo de vídeo. Esse exemplo demonstra como você pode incorporar um vídeo em sua página usando a tag `<video>` em HTML para aproveitar o Rich Media.


##### Objetivos da Unidade:

- Tabelas em HTML
- Estrutura da Tabela em HTML
- Tabelas e CSS
- Formulários em HTML
- Tags de Formulários
- Tags de Bloco e CSS
- Content, Padding, Border e Margin
- Regras de Estado em CSS
- Rich Media: Áudio e Vídeo




_________________

## Unidade IV



#### Organizando o Layout de um site

Desenvolver um website visualmente coeso e atraente demanda cuidados com o layout. No contexto da criação de páginas web, o layout refere-se à organização visual dos elementos no site. Isso inclui a disposição harmoniosa de itens como texto, imagens, gráficos, botões e outros componentes, resultando em uma composição esteticamente agradável e funcional. O layout é a fase primordial do processo de criação, na qual o designer define a distribuição dos elementos visuais na página. Essa etapa engloba escolhas como tamanho, posicionamento, hierarquia visual, espaçamento, cores e tipografia, bem como a estrutura global da composição. Em resumo, o layout molda a organização visual da página.

Nos websites, o layout desempenha um papel crucial ao apresentar o conteúdo de maneira clara e organizada, proporcionando uma experiência amigável e intuitiva aos usuários. Além disso, o layout web deve ser responsivo, ou seja, adaptar-se a diferentes tamanhos de tela para garantir a visualização adequada tanto em dispositivos móveis quanto em desktops. Para implementar um layout eficiente, é recomendável utilizar sistemas de layout como CSS Flexbox ou Grid. Essas abordagens contribuem para a consistência e alinhamento dos elementos em todas as páginas do site.





#### Flexbox





#### Design Responsivo





#### Media Queries





##### Objetivos da Unidade:

- Organizando o Layout de um site
- Flexbox
- Design Responsivo
- Media Queries

