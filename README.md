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
css
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







##### Objetivos da Unidade:

- Tabelas em HTML
- Estrutura da tabela em HTML
- Tabelas e CSS
- Formulários em HTML
- Tags de formulários
- Tags de bloco e CSS
- Content, Padding, Border e Margin
- Regras de estado em CSS
- Rich Media: Áudio e Vídeo




_________________

## Unidade IV







##### Objetivos da Unidade:

- Organizando o Layout de um site
- Flexbox
- Design Responsivo
- Media Queries

