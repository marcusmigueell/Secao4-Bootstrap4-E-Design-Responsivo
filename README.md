# Secao4-Bootstrap4-E-Design-Responsivo

Criei o <header> para criar o cabeçalho da página.
    - class="navbar-brand" é referente a imagem do cabeçalho e o width="142", pois, defini 142px para a largura da imagem.
    - <button class="navbar-toggler" data-toggle="collapse" data-target="#nav-principal"></button> é usado para quando for em telas menores a barra de navegação esconda e apareça apenas esse botão, e ao clicar aparecerá as opções de navegação, ou seja, é a responsividade da barra de navegação. data-target="#nav-principal" é o mesmo id que criei para referenciar o que será mostrado ao clicar no botão.
    -  <span class="navbar-toggler-icon"></span> apenas para criar o ícone do botão em telas menores. É usado dentro do <button></button>
    - <div class="collapse navbar-collapse" id="nav-principal"></div> aqui conterá os itens que aparecerá ao clicar no botão quando estiver em telas menores, ou seja, o que foi criando no item anterior.
    - navbar-nav é a barra de navegação
    - ml-auto é para deixar os itens no canto direito da tela, assim, ml = margin left "margem esquerda" sendo automática empurra todos os itens para o canto direito da tela.
    - navbar-item são os itens da navegação
    - navbar-link é o link da navegação
    temos que especificar o que é cada coisa na navegação.
    - btn btn-outline-light é para cirar um botão entrar e o light significa que o botão terá um tom claro.
</header>

Criei a <section> que será o corpo do site
    - usamos a class="row" para deixar como flexbox
    - dentro da <div class="row"> dividi o corpo da página em 2 div's a primeira será a de textos e a segunda com uma imagem. E para essa divisão coloquei 6 colunas para cada div com o código <div class="col-md-6 d-flex">, e o d-flex foi para converter em flexbox essa <div>
    - class="align-self-center" usado para centralizar o texto.
    - class="display-4" usado para mudar o tamanho do <h1>
    - ao criar o <form> deixei uma margem superior e inferior igual a 4 com essa classe class="mt-4 mb-4"
    - class="input-group input-group-lg" agrupei o form e defini o tamanho como lg.
    - type="text" placeholder="Seu e-mail" criei uma caixa de texto com a escrita "Seu e-mail" dentro da caixa
    - criei um botão agrupado na caixa de texto para com o texto "cadastre-se".
    - usei dois ícones, o ícone do android e do IOS em forma de botão, para chamar o ícone no fontawesome usei
        <i class="fab fa-apple fa-lg"></i>
        <i class="fab fa-android fa-lg"></i>
        fa-lg é pra aumentar o tamanho do ícone
    - coloquei a imagem de uma mulher ao lado do texto e essa classe class="col-md-6 d-none d-md-block" significa, col-md-6 é porque foi dividido a área em 2 blocos de 6 colunas cada d-none juntamente com d-md-block significa que a imagem irá aparecer a partir do tamanho md de tela, se for menor que md como sm, ou seja, em telas menores com o d-none a imagem não aparecerá.
</section>