<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glow & Go Cosméticos</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      background: #fff8f3;
      font-family: 'Montserrat', Arial, sans-serif;
      background-image: url('wallpaper.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      position: relative;
    }
    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0; width: 100vw; height: 100vh;
      background: rgba(255, 248, 243, 0.88);
      z-index: -1;
      pointer-events: none;
    }
    header {
      background: linear-gradient(90deg, #be9759 70%, #e8c5e1 100%);
      color: #fff; padding: 0 32px;
      display: flex; align-items: center; justify-content: space-between;
      position: sticky; top: 0; z-index: 10; height: 80px;
      box-shadow: 0 2px 8px #be97592a;
    }
    .logo { display: flex; align-items: center; }
    .logo img {
      height: 65px;
      margin-right: 18px;
      filter: drop-shadow(0 2px 6px #be97598a);
    }
    .logo span {
      font-family:'Playfair Display',serif;
      font-size:1.37em;
      color: #fff;
      font-weight: bold;
      letter-spacing: 1px;
    }
    .nav { display: flex; gap: 28px; }
    .nav a {
      color: #fff; text-decoration: none; font-weight: bold;
      font-size: 1.02em; padding: 6px 12px; border-radius: 22px; transition: background .2s;
    }
    .nav a:hover { background: #e8c5e1aa; color: #be9759; }
    .banner {
      background: linear-gradient(120deg, #e8c5e1 65%, #fff8f3);
      padding: 54px 0; text-align: center;
    }
    .banner h1 {
      font-family: 'Playfair Display', serif; font-size: 2.8em; color: #be9759; margin-bottom: 12px;
    }
    .banner p {
      font-size: 1.28em; color: #7c5a36; margin-bottom: 28px;
    }
    .banner img {
      max-width: 230px; border-radius: 30px; box-shadow: 0 2px 24px #be97598a;
    }
    .produtos {
      max-width: 1100px; margin: 50px auto 0; padding: 0 18px;
    }
    .produtos-title {
      font-family: 'Playfair Display', serif; color: #be9759; font-size: 2.1em; text-align: center; margin-bottom: 32px;
    }
    .produtos-grid {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
      gap: 34px;
    }
    .produto-card {
      background: #fff; border-radius: 24px; box-shadow: 0 2px 16px #be97594d;
      padding: 22px 16px; text-align: center; position: relative;
      transition: box-shadow .25s;
      border: 2.5px solid #e8c5e1;
    }
    .produto-card:hover { box-shadow: 0 8px 32px #be97598a; border-color: #be9759; }
    .produto-card img {
      max-width: 220px; width: 100%; height: auto;
      border-radius: 20px; margin-bottom: 12px;
      display: block; margin-left: auto; margin-right: auto;
      object-fit: contain; background: none;
    }
    .produto-card h3 { color: #be9759; font-size: 1.13em; margin-bottom: 9px; }
    .produto-card p { color: #7c5a36; font-size: 0.97em; margin-bottom: 10px; }
    .preco { font-weight: bold; color: #be9759; font-size: 1.08em; }
    .botoes-produto {
      margin-top: 16px; display: flex; gap: 12px; justify-content: center;
    }
    .btn {
      background: linear-gradient(90deg,#be9759 65%,#e8c5e1 100%);
      color: #fff; border: none; border-radius: 22px; padding: 7px 20px;
      font-size: 1em; cursor: pointer; font-weight: bold; transition: background .22s, color .22s;
      box-shadow: 0 2px 6px #be97592a;
    }
    .btn:hover { background: #fff8f3; color: #be9759; border: 2px solid #be9759; }
    .info-produto {
      display: none;
      background: rgba(255,255,255,0.97);
      color: #7c5a36;
      border-radius: 18px;
      box-shadow: 0 2px 10px #be97594d;
      padding: 16px;
      margin-top: 10px;
      text-align: left;
      font-size: 0.99em;
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      width: 98%;
      z-index: 99;
      overflow: hidden;
    }
    .info-produto .info-bg {
      position: absolute;
      top: 10px; left: 10px;
      opacity: 0.18;
      width: 120px; height: auto;
      z-index: 0;
      pointer-events: none;
    }
    .info-produto .info-text {
      position: relative;
      z-index: 1;
    }
    .info-close {
      background: #e8c5e1;
      color: #be9759;
      border: none;
      border-radius: 12px;
      padding: 2px 8px;
      float: right;
      cursor: pointer;
      margin-bottom: 8px;
      font-size: 0.95em;
      z-index: 2;
      position: relative;
    }
    #carrinho-box {
      position: fixed; top: 80px; right: 28px; background: #fff; border-radius: 24px;
      box-shadow: 0 2px 18px #be97594d; padding: 18px 22px; width: 320px; max-width: 90vw;
      z-index: 20; display: none;
    }
    #carrinho-box h4 { color: #be9759; font-size: 1.13em; margin-bottom: 13px; }
    #carrinho-list { margin-bottom: 13px; }
    #carrinho-list li { color: #7c5a36; font-size: 1em; margin-bottom: 6px; }
    #carrinho-fechar { background: #e8c5e1; color: #be9759; border: none; border-radius: 16px; padding: 3px 11px; cursor: pointer; }
    #carrinho-btn {
      position: fixed; top: 20px; right: 30px; background: #be9759; color: #fff; border-radius: 50%;
      width: 48px; height: 48px; display: flex; align-items: center; justify-content: center; font-size: 1.5em; box-shadow: 0 2px 12px #be97594d; cursor: pointer; z-index: 21;
      border: 3px solid #e8c5e1;
    }
    .depoimentos {
      max-width: 950px; margin: 60px auto; padding: 0 18px;
    }
    .depoimentos-title {
      font-family: 'Playfair Display', serif; color: #be9759; font-size: 1.7em; text-align: center; margin-bottom: 22px;
    }
    .depoimentos-list {
      display: grid; grid-template-columns: repeat(auto-fit,minmax(280px,1fr)); gap: 22px;
    }
    .depoimento-card {
      background: #e8c5e1; border-radius: 20px; padding: 18px; color: #7c5a36;
      box-shadow: 0 2px 12px #be97594d; font-size: 1em; font-style: italic;
    }
    footer {
      background: linear-gradient(90deg, #e8c5e1 70%, #be9759 100%);
      color: #fff; text-align: center; padding: 24px 0; font-size: 1em; margin-top: 60px;
      border-radius: 32px 32px 0 0;
    }
    footer a { color: #fff; font-weight: bold; text-decoration: underline; }
    @media(max-width: 780px) {
      header { flex-direction: column; height: auto; padding: 18px 8px; }
      .nav { gap: 16px; }
      .banner h1 { font-size: 2em; }
      .produtos-title, .depoimentos-title { font-size: 1.35em; }
      #carrinho-box { right: 0; left: 0; margin: 0 auto; }
      .info-produto { width: 98%; }
      .info-produto .info-bg { width: 80px; }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="logo.png" alt="Glow & Go Cosméticos">
      <span>Glow & Go Cosméticos</span>
    </div>
    <nav class="nav">
      <a href="#produtos">Produtos</a>
      <a href="#depoimentos">Depoimentos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <div class="banner">
    <img src="banner-cosmeticos.png" alt="Banner Glow & Go">
    <h1>Beleza, Cuidado e Autoestima</h1>
    <p>Descubra fragrâncias e produtos que valorizam você.<br>
      <span style="color:#d13e00;font-weight:bold;">Entregas apenas por marcação ou encomenda.</span>
    </p>
  </div>

  <section class="produtos" id="produtos">
    <div class="produtos-title">Linha Paixão</div>
    <div class="produtos-grid">
      <!-- Produto 1 -->
      <div class="produto-card">
        <img src="produto1.png" alt="Paixão Cacau & Pimenta Rosa">
        <h3>Paixão Cacau & Pimenta Rosa - Loção & Óleo Deo Corporal</h3>
        <p>Combinação especial para pele sedosa e perfumada.<br>Hidratação 24h com toque exótico.</p>
        <span class="preco">8.000 Kz</span>
        <div class="botoes-produto">
          <button class="btn" onclick="adicionarCarrinho('Paixão Cacau & Pimenta Rosa', '8.000 Kz')">Adicionar ao carrinho</button>
          <button class="btn" onclick="mostrarInfo(0)">Informações</button>
          <a href="https://wa.me/244975777067?text=Quero+comprar+Cacau+Pimenta+Rosa" class="btn" target="_blank">Comprar</a>
        </div>
        <div class="info-produto" id="info-produto-0">
          <img src="info-bg.png" class="info-bg" alt="Glow & Go Cosméticos">
          <div class="info-text">
            <button class="info-close" onclick="fecharInfo(0)">X</button>
            <b>Transforme seu banho num ritual de beleza!</b><br>
            Fórmula com óleo de amêndoas, textura leve e aroma marcante. Hidrata profundamente, deixando a pele macia, sedosa e perfumada o dia todo.<br>
            Indicado para todos os tipos de pele.
          </div>
        </div>
      </div>
      <!-- Produto 2 -->
      <div class="produto-card">
        <img src="produto2.png" alt="Paixão Tentadora Hidratante & Óleo">
        <h3>Paixão Tentadora - Hidratante & Óleo Deo Corporal</h3>
        <p>Sensualidade e feminilidade em cada gota.<br>Fragrância envolvente e toque acetinado.</p>
        <span class="preco">8.000 Kz</span>
        <div class="botoes-produto">
          <button class="btn" onclick="adicionarCarrinho('Paixão Tentadora Hidratante & Óleo Deo Corporal', '8.000 Kz')">Adicionar ao carrinho</button>
          <button class="btn" onclick="mostrarInfo(1)">Informações</button>
          <a href="https://wa.me/244975777067?text=Quero+comprar+Tentadora" class="btn" target="_blank">Comprar</a>
        </div>
        <div class="info-produto" id="info-produto-1">
          <img src="info-bg.png" class="info-bg" alt="Glow & Go Cosméticos">
          <div class="info-text">
            <button class="info-close" onclick="fecharInfo(1)">X</button>
            <b>Desperte sua sensualidade!</b><br>
            Hidratante e óleo com fragrância marcante, toque aveludado e hidratação prolongada. Deixe-se envolver por um perfume inesquecível que valoriza sua autoestima.<br>
            Ideal para quem gosta de se destacar.
          </div>
        </div>
      </div>
      <!-- Produto 3 -->
      <div class="produto-card">
        <img src="produto3.png" alt="Paixão Inspiradora Óleo Deo Corporal (Rosas Brancas)">
        <h3>Paixão Inspiradora Óleo Deo Corporal (Rosas Brancas)</h3>
        <p>Leveza e elegância para sua pele.<br>Óleo perfumado com hidratação intensa.</p>
        <span class="preco">8.000 Kz</span>
        <div class="botoes-produto">
          <button class="btn" onclick="adicionarCarrinho('Paixão Inspiradora Óleo Deo Corporal (Rosas Brancas)', '8.000 Kz')">Adicionar ao carrinho</button>
          <button class="btn" onclick="mostrarInfo(2)">Informações</button>
          <a href="https://wa.me/244975777067?text=Quero+comprar+Inspiradora+Rosas+Brancas" class="btn" target="_blank">Comprar</a>
        </div>
        <div class="info-produto" id="info-produto-2">
          <img src="info-bg.png" class="info-bg" alt="Glow & Go Cosméticos">
          <div class="info-text">
            <button class="info-close" onclick="fecharInfo(2)">X</button>
            <b>Exalte o seu charme natural!</b><br>
            Óleo corporal que une hidratação intensa com a delicadeza das rosas brancas. Textura agradável, perfume sofisticado e efeito radiante na pele.<br>
            Perfeito para uso diário.
          </div>
        </div>
      </div>
      <!-- Produto 4 -->
      <div class="produto-card">
        <img src="produto4.png" alt="Paixão Flor de Baunilha Óleo Deo Corporal">
        <h3>Paixão Flor de Baunilha Óleo Deo Corporal</h3>
        <p>Hidratação profunda com aroma doce de baunilha.<br>Pele renovada e perfumada por 24h.</p>
        <span class="preco">8.000 Kz</span>
        <div class="botoes-produto">
          <button class="btn" onclick="adicionarCarrinho('Paixão Flor de Baunilha Óleo Deo Corporal', '8.000 Kz')">Adicionar ao carrinho</button>
          <button class="btn" onclick="mostrarInfo(3)">Informações</button>
          <a href="https://wa.me/244975777067?text=Quero+comprar+Flor+de+Baunilha" class="btn" target="_blank">Comprar</a>
        </div>
        <div class="info-produto" id="info-produto-3">
          <img src="info-bg.png" class="info-bg" alt="Glow & Go Cosméticos">
          <div class="info-text">
            <button class="info-close" onclick="fecharInfo(3)">X</button>
            <b>Proporcione momentos de puro cuidado!</b><br>
            Óleo corporal com aroma doce, hidratação prolongada e efeito calmante. Ideal para quem busca suavidade e bem-estar na rotina.<br>
            Experimente e sinta a diferença!
          </div>
        </div>
      </div>
    </div>
  </section>

  <div id="carrinho-btn" onclick="abrirCarrinho()" title="Ver carrinho">🛒</div>
  <div id="carrinho-box">
    <h4>Seu carrinho</h4>
    <ul id="carrinho-list"></ul>
    <button id="carrinho-fechar" onclick="fecharCarrinho()">Fechar</button>
    <a href="https://wa.me/244975777067?text=Quero+finalizar+minha+compra" class="btn" style="margin-top:12px;display:block;text-align:center;">Finalizar pelo WhatsApp</a>
  </div>

  <section class="depoimentos" id="depoimentos">
    <div class="depoimentos-title">O que dizem nossas clientes</div>
    <div class="depoimentos-list">
      <div class="depoimento-card">"Produtos maravilhosos, minha pele ficou super hidratada e o perfume é incrível!"<br><b>- Clarinha</b></div>
      <div class="depoimento-card">"Atendimento excelente e entrega rápida. Recomendo muito!"<br><b>- Carla</b></div>
      <div class="depoimento-card">"A Linha Paixão é tudo! Já quero experimentar outros produtos."<br><b>- Vanessa</b></div>
      <div class="depoimento-card">"Produtos testados e aprovados por quem entende de beleza.”<br><b>- Esteves Manuel</b></div>
      <div class="depoimento-card">"Cosméticos feitos para durar e cuidar.”<br><b>- Brénica</b></div>
    </div>
  </section>

  <footer id="contato">
    <div>
      <b>Glow & Go Cosméticos</b> • Huíla-Lubango/Angola<br>
      WhatsApp: <a href="https://wa.me/244975777067" target="_blank">+244 975 777 067</a> |
      <a href="https://wa.me/244921166145" target="_blank">+244 921 166 145</a><br>
      Instagram: <a href="https://www.instagram.com/iam_tekajr0?igsh=MWFydno0ZnRmNXFqYw==" target="_blank">@iam_tekajr0</a>
      <span style="margin-left:10px;"></span>
      <a href="https://www.instagram.com/i_lits23?igsh=MWFiMHRweHMyc2JqOA==" target="_blank">@I_lits23</a><br>
      Email: dadinhoa29@gmail.com <a href="mailto:dadinhoa29@gmail.com">dadinhoa29@gmail.com</a><br>
      Endereço: Senhora do Monte (Lubango), Rua da escola dos Sargentos<br>
      <span style="color:#fff8f3; font-size:0.95em;">Entregas apenas por marcação ou encomenda.</span>
    </div>
    <div style="margin-top:9px;font-size:0.93em;">© 2025 Glow & Go Cosméticos</div>
  </footer>

  <script>
    let carrinho = [];
    function adicionarCarrinho(nome, preco){
      carrinho.push({nome, preco});
      atualizarCarrinho();
      document.getElementById('carrinho-box').style.display = 'block';
    }
    function atualizarCarrinho(){
      const lista = document.getElementById('carrinho-list');
      lista.innerHTML = '';
      if(carrinho.length === 0){
        lista.innerHTML = '<li>Seu carrinho está vazio.</li>';
      } else {
        carrinho.forEach((prod,i)=>{
          lista.innerHTML += `<li>${prod.nome} <b>${prod.preco}</b> <button onclick="removerItem(${i})" style="margin-left:8px;font-size:0.9em;">remover</button></li>`;
        });
      }
    }
    function abrirCarrinho(){
      document.getElementById('carrinho-box').style.display = 'block';
      atualizarCarrinho();
    }
    function fecharCarrinho(){
      document.getElementById('carrinho-box').style.display = 'none';
    }
    function removerItem(i){
      carrinho.splice(i,1);
      atualizarCarrinho();
    }

    // Informações do produto
    function mostrarInfo(i){
      document.getElementById('info-produto-'+i).style.display = 'block';
    }
    function fecharInfo(i){
      document.getElementById('info-produto-'+i).style.display = 'none';
    }
  </script>
</body>
</html>
