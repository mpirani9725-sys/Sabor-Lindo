<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Royal Gourmet | Restaurante</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #111;
    color: white;
}

header {
    background: #080808;
    padding: 22px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #b58b35;
}

.logo {
    color: #d6aa50;
    font-size: 26px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 22px;
}

nav a:hover {
    color: #d6aa50;
}

.hero {
    min-height: 500px;
    display: flex;
    align-items: center;
    padding: 60px 10%;
    background:
    linear-gradient(90deg, #000 20%, #0008),
    url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?w=1600')
    center/cover;
}

.hero h1 {
    font-size: 52px;
    color: #e3b75e;
    margin-bottom: 20px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background: #d6aa50;
    color: #111;
    padding: 14px 28px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 65px 8%;
    text-align: center;
}

h2 {
    color: #d6aa50;
    font-size: 32px;
    margin-bottom: 35px;
}

.menu {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 25px;
}

.item {
    background: #202020;
    border-radius: 10px;
    overflow: hidden;
    transition: .3s;
}

.item:hover {
    transform: translateY(-7px);
}

.item img {
    width: 100%;
    height: 190px;
    object-fit: cover;
}

.item h3 {
    margin: 15px;
    color: #e3b75e;
}

.item p {
    padding: 0 15px;
    color: #ccc;
}

.price {
    display: block;
    color: #d6aa50;
    font-size: 21px;
    margin: 18px;
}

.about {
    background: #1b1b1b;
    line-height: 1.8;
}

.contact {
    line-height: 2;
}

footer {
    background: #080808;
    padding: 25px;
    text-align: center;
    color: #aaa;
    border-top: 1px solid #b58b35;
}

@media(max-width: 600px) {
    header {
        flex-direction: column;
        gap: 18px;
    }

    nav a {
        margin: 0 7px;
        font-size: 13px;
    }

    .hero h1 {
        font-size: 36px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">ROYAL GOURMET</div>
    <nav>
        <a href="#inicio">Início</a>
        <a href="#cardapio">Cardápio</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<div class="hero" id="inicio">
    <div>
        <h1>Uma experiência<br>de sabor!</h1>
        <p>Sabores especiais para momentos inesquecíveis.</p>
        <a href="#cardapio" class="btn">Ver cardápio</a>
    </div>
</div>

<section id="cardapio">
    <h2>Nosso Cardápio</h2>

    <div class="menu">

        <div class="item">
            <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?w=600">
            <h3>Pizza Especial</h3>
            <p>Pizza artesanal com queijo e ingredientes selecionados.</p>
            <span class="price">R$ 49,90</span>
        </div>

        <div class="item">
            <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=600">
            <h3>Hambúrguer Gourmet</h3>
            <p>Hambúrguer artesanal com queijo e molho especial.</p>
            <span class="price">R$ 35,90</span>
        </div>

        <div class="item">
            <img src="https://images.unsplash.com/photo-1546833999-b9f581a1996d?w=600">
            <h3>Prato Executivo</h3>
            <p>Uma combinação deliciosa de sabores e temperos.</p>
            <span class="price">R$ 39,90</span>
        </div>

        <div class="item">
            <img src="https://images.unsplash.com/photo-1551024506-0bccd828d307?w=600">
            <h3>Sobremesa Especial</h3>
            <p>Uma sobremesa irresistível para finalizar sua refeição.</p>
            <span class="price">R$ 19,90</span>
        </div>

    </div>
</section>

<section class="about" id="sobre">
    <h2>Sobre Nós</h2>
    <p>
        O Royal Gourmet nasceu para proporcionar uma experiência
        gastronômica única. Trabalhamos com ingredientes selecionados,
        qualidade e muito carinho em cada prato.
    </p>
</section>

<section class="contact" id="contato">
    <h2>Entre em Contato</h2>
    <p>📍 Endereço: Rua Principal, 100 - Centro</p>
    <p>📞 Telefone: (11) 99999-9999</p>
    <p>🕒 Funcionamento: Terça a Domingo, das 18h às 23h</p>
    <br>
    <a class="btn"
       href="https://wa.me/5511999999999"
       target="_blank">
       Fazer pedido pelo WhatsApp
    </a>
</section>

<footer>
    <p>© 2026 Royal Gourmet - Todos os direitos reservados.</p>
</footer>

</body>
</html>