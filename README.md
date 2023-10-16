<h2 class="titulo-centralizado">Sobre a Barbearia Alura</h2>
<h3 class="titulo-centralizado">Benefícios</h3>
.titulo-principal {
    padding-left: 20px;
}
.titulo-centralizado {
    text-align: center
}
<p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. 
Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

<p><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

<p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
<div class="beneficios">
    <h2>Benefícios</h2>

    <ul>
        <li class="itens">Atendimento aos Clientes</li>
        <li class="itens">Espaço diferenciado</li>
        <li class="itens">Localização</li>
        <li class="itens">Profissionais Qualificados</li>
    </ul>

    <img src="beneficios.jpg" class="imagembeneficios">
</div>
body {

}

.principal{
    background: #CCCCCC;
    padding: 30px;
}
.itens {
    font-style: italic;
}

.beneficios {
    background: #FFFFFF;
    padding: 20px;
}

h2 {
    text-align: center;
}
ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}
imagembeneficios {
    width: 50%;
}
<div class="caixa">
    <h1><img src="logo.png"></h1>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="produtos.html">Produtos</a></li>
            <li><a href="contato.html">Contato</a></li>
        </ul>
    </nav>
</div>
header {
    background: #BBBBBB;
    padding: 20px 0;
}

.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}
kkkk
nav {
    position: absolute;
    top: 110px;
    right: 0;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}
<main>
    <ul class="produtos">
        <li>
            <h2>Cabelo</h2>
            <img src="cabelo.jpg">
            <p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
            <p class="produto-preco">R$ 25,00</p>
        </li>
        <li>
            <h2>Barba</h2>
            <img src="barba.jpg">
            <p class="produto-descricao">Corte e desenho profissional de barba</p>
            <p class="produto-preco">R$ 18,00</p>
        </li>
        <li>
            <h2>Cabelo + Barba</h2>
            <img src="cabelo+barba.jpg">
            <p class="produto-descricao">Pacote completo de cabelo e barba</p>
            <p class="produto-preco">R$ 35,00</p>
        </li>
    </ul>
</main>
.produtos {
    width: 940px;
    margin: 0 auto;
    padding: 50px 0;
}

.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
}

.produtos h2 {
    font-size: 30px;
    font-weight: bold;
}

.produto-descricao {
    font-size: 18px;
}

.produto-preco {
    font-size: 22px;
    font-weight: bold;
    margin-top: 10px;
}
.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
    border: 2px solid #000000;
    border-radius: 10px;
}
nav a:hover {
    color: #C78C19;
    text-decoration: underline;
}
.produtos li:hover {
    border-color: #C78C19;
}
.produtos li:active {
    border-color: #088C19;  
}
.produtos li:hover h2 {
    font-size: 34px;
}
<footer>
    <img src="logo-branco.png">
    <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
</footer>
footer {
    text-align: center;
    background: url("bg.jpg");
    padding: 40px 0;
}

.copyright {
    color: #FFFFFF;
    font-size: 13px;
    margin: 20px 0 0;
}
