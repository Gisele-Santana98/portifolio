ATIVIDADE 1.0

1) Estilizando elementos com classes CSS
Você está trabalhando no desenvolvimento de uma página web e precisa aplicar estilos específicos a diferentes elementos usando classes CSS. Seu desafio é criar uma classe chamada "texto-destaque" no arquivo HTML para um elemento <p>e, em seguida, estilizar essa classe no arquivo CSS para alterar a cor do texto. Use sua criatividade para escolher cores que tornem o texto destacado, mas ainda legível e harmonioso com o design geral da página.

2) Destacando títulos com CSS
Imagine que você está desenvolvendo um blog e precisa destacar os títulos das postagens. Crie uma classe CSS chamada "titulo-blog" e aplique-a a elementos <h1>no seu arquivo HTML. Em seguida, personalize essa classe no arquivo CSS para mudar a cor do texto, para dar mais destaque.

3) Estilos situacionais com classes CSS
Você está trabalhando em um site de notícias e precisa aplicar um estilo diferente para notícias urgentes. Crie uma classe CSS chamada "urgente" e aplique-a a elementos <p>que contêm notícias urgentes. No CSS, faça com que o texto desses parágrafos seja vermelho, para chamar a atenção do leitor.

4) Entendendo e aplicando o reset CSS
Você está trabalhando em um projeto de site e notou que o layout está um pouco desorganizado devido aos estilos padrões aplicados pelo navegador. Sua tarefa é aplicar um "reset CSS" para remover esses estilos padrão. Comece criando um arquivo CSS e utilize o seletor universal * para definir a margin e o padding de todos os elementos para 0. Teste o efeito dessa mudança no layout do seu site.

5) Inspecionando elementos e entendimento do modelo de caixa
Como quem trabalha com front-end, você precisa entender como os estilos são aplicados aos elementos da sua página. Use as ferramentas de desenvolvimento (DevTools) do navegador para inspecionar o modelo de caixa de um elemento do seu site. Preste atenção nas propriedades margin, border, padding e content. Descreva como essas propriedades estão afetando o elemento selecionado.

6) Aplicando o modelo de caixa na prática
Agora que você entendeu o modelo de caixa CSS, aplique esse conhecimento no seu projeto. Selecione um elemento específico (por exemplo, um parágrafo) e ajuste as propriedades de margin, border, padding e content. Observe como cada alteração afeta o posicionamento e a aparência do elemento na página.

ATIVIDADE 1.1

1) Ajustando a altura da tela com CSS
Você está desenvolvendo um site e deseja que ele ocupe 100% da altura da tela do usuário, sem deixar espaços em branco acima ou abaixo do conteúdo. Para isso, você precisa ajustar o elemento body do seu CSS para garantir que ele preencha toda a altura da tela. Utilize a propriedade height e o valor 100vh para conseguir este efeito. Teste o resultado usando a ferramenta "Inspecionar" do navegador para verificar se o body realmente ocupa toda a altura da tela.

2) Controlando o tamanho de elementos com Box Sizing
Imagine que você está trabalhando em um projeto web e precisa garantir que todos os elementos filhos dentro do body não ultrapassem os limites, especialmente ao adicionar bordas e paddings. Para isso, você deve utilizar a propriedade box-sizing com o valor border-box no elemento body. Após aplicar esta configuração, inspecione o layout para garantir que nenhum elemento filho ultrapasse o limite do body e os seus próprios tamanhos definidos, mesmo ao adicionar bordas e paddings.

3) Criando um layout sem scroll
Você recebeu um design do Figma para um site que deve caber em uma única tela, sem necessidade de scroll. O design inclui dois blocos de conteúdo sobre um fundo preto. O desafio é criar um layout CSS que reproduza essa estrutura, garantindo que todo o conteúdo caiba em uma tela, sem scroll. Utilize as propriedades CSS adequadas para posicionar os blocos de conteúdo lado a lado e centralizá-los na página, mantendo o design conforme especificado no Figma.

4) Flexbox: alinhando textos e imagens
Você está desenvolvendo um site e precisa posicionar textos e uma imagem lado a lado, adaptando-se a diferentes tamanhos de tela. Utilize Flexbox para alinhar um bloco de texto à esquerda e uma imagem à direita dentro de um <main>.

<main class="container">
  <p class="texto">Texto aqui...</p>
  <img class="imagem">
</main>

.container {
  display: flex;
  justify-content: space-between;
}

5) Flexbox: Centralização vertical
Seu desafio é centralizar verticalmente o conteúdo de um container usando Flexbox. Você tem uma <div> com a classe .container contendo vários itens.

<div class="container">
  <div>Item 1</div>
  <div>Item 2</div>
  <!-- Mais itens aqui -->
</div>

.container {
  display: flex;
  align-items: center;
  height: 300px; /* Altura ajustável conforme necessário */
}

6) Flexbox: respdonsividade e alinhamento
Crie uma página web responsiva onde os elementos se ajustam em diferentes tamanhos de tela, evitando margens fixas. Utilize Flexbox para alternar entre dispor elementos em uma linha ou coluna.

<div class="responsivo-container">
  <div>Conteúdo 1</div>
  <div>Conteúdo 2</div>
  <!-- Mais conteúdos -->
</div>

.responsivo-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}

ATIVIDADE 1.2

1) Espaçamento e margens com Flexbox
Aqui, o objetivo é ajustar o espaçamento entre a seção de texto e a imagem para criar uma aparência semelhante ao design do Figma. Use a propriedade justify-content: space-between; em Flexbox para espaçar os elementos e adicione margens para evitar que os elementos fiquem colados nas bordas da tela.

.apresentacao {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 10%;
}

2) Definindo o tamanho da seção de texto
Nesta atividade, você irá ajustar o tamanho de uma seção de texto para que corresponda às especificações do design no Figma. Você vai adicionar uma nova classe chamada apresentacao__conteudo à tag <section> no HTML e, em seguida, definir a largura dessa seção no CSS usando a propriedade width. O valor específico da largura deve ser retirado do projeto no Figma.

3) Ajustando tamanhos de títulos e textos
O objetivo aqui é modificar o tamanho dos textos de títulos e parágrafos para que correspondam ao design no Figma. Você vai criar classes específicas para o título (apresentacao__conteudo__titulo) e para o texto (apresentacao__conteudo__texto) no HTML. Depois, no CSS, você usará a propriedade font-size para definir os tamanhos de fonte para estas classes, com os valores retirados do Figma.

4) Importando e aplicando fontes do Google Fonts
Nesta atividade, você irá importar as fontes "Krona One" e "Montserrat" do Google Fonts para o seu projeto web. Primeiro, você precisa pesquisar essas fontes no Google Fonts e utilizar a opção de @import para incluí-las no arquivo CSS. Em seguida, você aplicará essas fontes aos elementos de texto específicos na sua página, como títulos e parágrafos, usando a propriedade font-family.

5) Personalizando fontes de títulos e textos
Depois de importar as fontes, você irá personalizar o estilo dos títulos e textos da página para que correspondam ao design no Figma. Você modificará a propriedade font-family para os elementos de título e texto no CSS, aplicando as fontes "Krona One" e "Montserrat" respectivamente. O objetivo é garantir que o estilo visual da página web esteja alinhado com o design proposto.

ATIVIDADE 1.3

1) Espaçamento e tamanho dos botões
Aqui, o desafio é ajustar o espaçamento e o tamanho dos botões. Após ter alinhado os botões horizontalmente com Flexbox, você precisa garantir que eles tenham um tamanho adequado e um espaçamento consistente entre si, conforme o design do projeto. Altere o CSS para ajustar o tamanho dos botões e adicione margem para criar o espaçamento correto.

2) Melhorando a visibilidade dos botões
Nesta atividade, seu foco será na acessibilidade e visibilidade dos botões. Guilherme mencionou a dificuldade em enxergar os botões. Portanto, aumente o tamanho da fonte, altere as cores e adicione efeitos como sombra ou borda para torná-los mais visíveis e atrativos. Use suas habilidades em CSS para melhorar a estética e a acessibilidade dos botões na página.

3) Criando uma classe comum para botões
Nesta atividade, você irá criar uma classe CSS comum para os botões "Instagram" e "GitHub" no seu projeto HTML. Essa classe terá propriedades de estilo que farão os botões se parecerem com os do design no Figma, incluindo cor de fundo, tamanho do texto, e arredondamento dos vértices.

4) Ajustando o espaçamento interno dos botões
O objetivo desta atividade é ajustar o espaçamento interno dos botões para que eles correspondam ao design no Figma. Você vai utilizar a propriedade padding para definir o espaço entre o texto do botão e suas bordas, garantindo que o layout seja consistente e visualmente agradável.

5) Importando e aplicando a fonte correta
Nesta atividade, você se concentrará em ajustar a fonte dos botões. Vai importar a fonte Montserrat com o peso 600 do Google Fonts e aplicá-la aos botões, garantindo que o texto corresponda exatamente ao design no Figma. Além disso, você removerá o sublinhado padrão dos links e ajustará a cor do texto.

ATIVIDADE 1.4

1) Adicionando um subtítulo à página
Imagine que você está desenvolvendo uma página web para compartilhar suas redes sociais. Você precisa adicionar um subtítulo "Acesse minhas redes:" acima dos links para Instagram e Github. Sua tarefa é editar o arquivo index.html para incluir esse subtítulo. Lembre-se de usar a tag <h2> para o subtítulo e colocá-lo dentro da <div> que já contém os links.

2) Alterando a disposição dos elementos com Flexbox
Agora que o subtítulo foi adicionado, você percebe que ele está alinhado à esquerda dos botões, ao invés de acima deles. Isso aconteceu porque os elementos estão dispostos horizontalmente. Sua missão é alterar a disposição dos elementos (subtítulo e botões) para uma disposição vertical. Edite o arquivo style.css, modificando a propriedade flex-direction para column dentro da classe .apresentacao__links. Isso mudará a direção do Flexbox, alinhando os elementos verticalmente.

3) Ajustando o alinhamento e o espaçamento dos elementos
Após modificar a direção do Flexbox, você observa que os elementos (texto e botões) estão muito próximos uns dos outros e alinhados à esquerda. Para melhorar a estética da página, você precisa centralizar esses elementos verticalmente e adicionar um espaçamento entre eles. No arquivo style.css, dentro da classe .apresentacao__links, adicione a propriedade align-items: center para centralizar os elementos. Em seguida, insira a propriedade gap com o valor de 32px para adicionar o espaçamento entre cada elemento.

4) Criando uma classe para o subtítulo
Você está desenvolvendo uma página web e decidiu que o subtítulo "Acesse minhas redes:" precisa de uma estilização específica. Para isso, você vai criar uma classe CSS para este subtítulo. No arquivo index.html, encontre a tag <h2> que contém o subtítulo e adicione uma classe chamada apresentacao__links__subtitulo. Sua tarefa é inserir essa classe na tag <h2> de forma correta.

5) Estilizando o subtítulo
Agora que você criou uma classe para o subtítulo, é hora de estilizá-lo. No arquivo style.css, adicione a classe .apresentacao__links__subtitulo e configure as propriedades de estilo. Utilize a fonte 'Krona One', com um peso de fonte (font-weight) de 400 e um tamanho de fonte (font-size) de 24px. Ajuste a fonte para ser 'sans-serif' sem aspas. Sua tarefa é escrever o código CSS para aplicar essas configurações ao subtítulo.

6) Modificando o estilo dos botões
Os botões da sua página precisam de um novo visual. No arquivo style.css, encontre a classe .apresentacao__links__link e faça as seguintes alterações: remova o fundo ciano, mude a cor do texto para branco (#F6F6F6), adicione uma borda sólida de 2px na cor ciano (#22D4FD), altere a largura para 378px, e ajuste o border-radius para 8px. Sua tarefa é alterar o código CSS para refletir estas mudanças, criando botões com bordas ciano, texto branco, e cantos menos arredondados.

ATIVIDADE 1.5

1) Organizando ícones nas redes sociais
Imagine que você está trabalhando em um projeto pessoal onde deseja incluir links para suas redes sociais com ícones correspondentes. Você já tem um link para o GitHub com um ícone, mas precisa adicionar outros dois: LinkedIn e Twitch. Utilize o seguinte trecho de código HTML como ponto de partida:

<main class="apresentacao">
    <section class="apresentacao__conteudo">
        <div class="apresentacao__links">
            <h2 class="apresentacao__links__subtitulo">Acesse minhas redes:</h2>
            <a class="apresentacao__links__link" href="https://github.com/seunome">
                <img src="./assets/github.png">
                Github
            </a>
            <!-- Adicione os links do LinkedIn e Twitch aqui -->
        </div>
    </section>
    <img src="./assets/imagem.png" alt="Foto da Joana Santos programando">
</main>
<footer></footer>
</body>
</html>

2) Centralizando ícones e textos nos botões
Imagine que você está trabalhando em um projeto de site onde precisa alinhar ícones de redes sociais com seus respectivos textos dentro de botões. O desafio é utilizar Flexbox para centralizar tanto o ícone quanto o texto dentro dos botões. Comece acessando o arquivo style.css e encontre a classe .apresentacao__links__link. Sua tarefa é adicionar as propriedades display: flex, justify-content: center e gap: 16px nesta classe, respeitando a ordem e posição corretas entre as outras propriedades existentes.

3) Espaçamento entre ícones e textos
Neste desafio, você precisa ajustar o espaçamento entre os ícones e os textos dentro dos botões de redes sociais no mesmo projeto do site. Primeiro, consulte o Figma do projeto para identificar o valor exato do espaçamento em pixels entre o ícone e o texto. Depois, volte ao arquivo style.css e adicione a propriedade gap com o valor encontrado no Figma à classe .apresentacao__links__link. Certifique-se de que o gap esteja posicionado corretamente dentro da declaração da classe.

4) Personalizando o efeito Hover
Você está desenvolvendo uma página de portfólio e quer criar um efeito visual atraente. O objetivo é fazer com que, ao passar o mouse sobre os botões, eles se destaquem com uma borda azul. Para isso, utilize a classe .apresentacao__links__link já existente no seu código CSS. Seu desafio é adicionar o efeito Hover a essa classe, fazendo com que a borda do botão mude para a cor azul (#0000FF) quando o cursor passar sobre ele.

5) Alterando o cursor e o fundo dos botões
Na sua página de portfólio, você observou que, ao passar o mouse sobre um botão, o cursor se transforma em uma mão com o indicador levantado. Além disso, você deseja que o fundo do botão mude para um tom de preto levemente mais claro (#272727) ao passar o mouse. Seu desafio é editar a classe .apresentacao__links__link:hover no seu arquivo CSS para alterar o cursor para o estilo 'pointer' e mudar a cor de fundo do botão ao passar o mouse sobre ele.

ATIVIDADE 1.6

1) Personalizando o rodapé do seu site
Imagine que você está desenvolvendo um site e chegou a hora de personalizar o rodapé. O desafio é criar um rodapé estilizado com as seguintes características: deve ter um fundo azul claro (#22D4FD), texto em preto (#000000), e o texto deve ser centralizado e usar a fonte 'Montserrat', tamanho 24px e peso 400. Além disso, o rodapé deve ter um padding de 24px. Use o HTML e CSS fornecidos como base e aplique as modificações necessárias.

2) Ajustando o espaçamento interno da apresentação
Você ficou responsável por ajustar o layout de uma seção de apresentação em um site. Atualmente, os elementos estão muito próximos das bordas, o que prejudica a estética do site. Sua tarefa é substituir a propriedade margin por padding na classe .apresentacao do CSS, testando valores de porcentagem para encontrar o espaçamento ideal. Comece com 5% e ajuste conforme necessário para obter um visual equilibrado.

3) Removendo o height para adaptar o layout
Seu site está enfrentando um problema de layout: a propriedade height: 100vh no body está impedindo que o conteúdo se ajuste corretamente na tela, especialmente com a adição de novos elementos como um rodapé. Sua missão é comentar a linha que define height: 100vh no CSS e verificar o impacto dessa mudança no layout do site. Observe como o conteúdo e o rodapé se adaptam à nova configuração.

4) Estilizando o cabeçalho com CSS
Você está criando um site e chegou a hora de estilizar o cabeçalho para que ele fique visível e atraente, similar ao projeto no Figma. Você precisa adicionar estilo ao cabeçalho no arquivo style.css, de forma que os links "Home" e "Sobre mim" fiquem alinhados horizontalmente e com uma aparência moderna. Considere usar propriedades como font-size, color, margin, padding, e display. Tente também adicionar um hover para alterar a cor dos links quando o mouse passar por cima.

5) Ajustando o espaçamento interno dos links
Com base no estilo atual do cabeçalho, percebe-se que os links podem estar muito próximos um do outro ou da borda do cabeçalho, o que pode afetar a legibilidade e a estética do site. Sua tarefa é ajustar o espaçamento interno (padding) dos links "Home" e "Sobre mim" para garantir que eles tenham um espaçamento adequado em torno do texto. Isso tornará o cabeçalho mais atraente e fácil de usar.

DESAFIO

Agora que você aprendeu a criar outras páginas com HTML, queremos te desafiar!

Crie mais uma página em seu projeto e construa nela o seu currículo.

Você pode seguir a estrutura dos currículos tradicionais, com suas informações no topo e sua estrutura dividida em seções, ou você pode soltar sua criatividade e fazer algo totalmente diferente, fica a seu critério.

É importante que nessa página currículo você adicione uma imagem sua e crie pelo menos uma lista HTML, que contenha suas experiências de trabalho ou estudos.

Além disso, pode ser interessante adicionar outros projetos caso você tenha.

Lembre-se: não tenha medo de personalizar esta página, afinal é o seu currículo e quanto mais tiver “a sua cara”, melhor.

Agora é sua vez de criar, topa o desafio?


    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Currículo</h1>
            <p class="apresentacao__conteudo__texto">
                Apresentação e informações principais
            </p>
            <h2 class="apresentacao__conteudo__titulo">Experiências</h2>
            <p class="apresentacao__conteudo__texto">
            <ul class="apresentacao__conteudo__texto">
                <li> Empresa tal (2020 - 2021) - fazia isso e aquilo </li>
                <li> Empresa tal (2021 - 2023) - fazia isso e aquilo </li>
            </ul>
            </p>
            <h2 class="apresentacao__conteudo__titulo">Estudos</h2>
            <div class="apresentacao__conteudo__texto">
            <ul class="apresentacao__conteudo__texto">
                <li>Curso tal - Alura Cursos <a href="linkdocertificado">com certificado</a> </li>
                <li>Curso tal - Alura Cursos <a href="linkdocertificado">com certificado</a></li>
                <li>Curso tal - Alura Cursos <a href="linkdocertificado">com certificado</a></li>
            </ul>
            </div>    
        </section>
        <img src="./assets/imagem.png" alt="Foto da Joana Santos programando">
    </main> 

E a única adição no CSS foi a estilização dos links de certificado, como no seguinte bloco de código:


.apresentacao__conteudo__texto a{
    text-decoration: none;
    color: #22D4FD;
}

Caso queira entender melhor como funcionam as listas HTML, você pode consultar a

ATIVIDADE 1.7

1) Estilizando o cabeçalho com CSS
Imagine que você trabalha com desenvolvimento front-end trabalhando em um projeto de website. O seu desafio é estilizar o cabeçalho da página de acordo com as especificações fornecidas. Utilize o arquivo style.css para aplicar as propriedades CSS no cabeçalho.

2) Ajustando o espaçamento do conteúdo
Agora, como quem trabalha com desenvolvimento, seu próximo desafio é ajustar o espaçamento do conteúdo da página para que se alinhe corretamente com o cabeçalho.

3) Criando e navegando para a página "Sobre mim"
Você está trabalhando em um projeto de site pessoal e precisa adicionar uma página "Sobre mim". Para isso, você deve criar um novo arquivo HTML, chamado about.html, e configurar um link no menu de navegação do seu site principal (index.html) para redirecionar para esta nova página. Além disso, ajuste o cabeçalho da página about.html para que o título da aba seja “Sobre mim” e adicione um <h1> com o texto "Sobre mim" no corpo da nova página. Certifique-se de que a navegação entre a página principal e a página "Sobre mim" esteja funcionando corretamente.

4) Ajustando a estilização após reorganização de arquivos
Você percebeu que, após mover o arquivo styles.css para uma nova pasta chamada "styles", a estilização do seu site foi perdida. Para corrigir isso, você deve atualizar o caminho do arquivo CSS no seu arquivo index.html. Além disso, no arquivo styles.css, você deve remover o sublinhado dos links no cabeçalho do site. Após estas correções, verifique se a estilização foi aplicada corretamente e se os links do cabeçalho não estão mais sublinhados.

5) Estruturando a página "Sobre mim" com cabeçalho e rodapé
Nesta atividade, você irá estruturar a página "Sobre mim" do seu projeto, reutilizando o cabeçalho e o rodapé da página inicial (index.html). Primeiro, copie o <header> e o <footer> do index.html e cole-os no arquivo about.html. Em seguida, adicione uma seção <main> vazia entre o <header> e o <footer>. Por fim, verifique se a estrutura copiada está funcionando corretamente no navegador, com os links de navegação e o texto do rodapé aparecendo.

6) Importando e corrigindo o caminho do arquivo CSS na página "Sobre mim"
O objetivo desta atividade é importar o arquivo de estilos styles.css na página "Sobre mim" e corrigir o caminho do arquivo para refletir a estrutura de pastas atual. No arquivo about.html, adicione a tag <link> para importar o styles.css. Lembre-se de que o arquivo CSS foi movido para uma pasta chamada "styles", então o caminho do href na tag <link> precisa ser atualizado para "./styles/styles.css". Após essa correção, salve o arquivo e recarregue a página no navegador para verificar se os estilos foram aplicados corretamente.

ATIVIDADE 1.8

