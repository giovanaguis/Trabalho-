# Trabalho-
giovana gomes
Código do style.css

/* ===================================
   CONFIGURAÇÃO GERAL
   =================================== */

body {

    font-family: "Poppins", sans-serif;
    background-color: white;
    color: #222;
    transition: 0.3s;
   
}

/* ===================================
   HEADER
   =================================== */
.hero{

    width: 100%;
    height: 180px;   
    background-image: url("../img/banner.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

/* ===================================
   NAVBAR
   =================================== */

.navbar {

    background-color: #222;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    position: sticky;
    top: 0;
    z-index: 1000;
}


/* ===================================
   LOGO
   =================================== */

.logo {

    font-size: 24px;
    font-weight: 700;

}


/* ===================================
   MENU
   =================================== */

.menu {

    display: flex;
    gap: 30px;
    list-style: none;

}


.menu a {

    color: white;
    font-size: 16px;
    font-weight: 500;
    transition: 0.3s;

}


.menu a:hover {

    opacity: 0.7;
    color: gold;

}


/* ===================================
   BOTÕES
   =================================== */

button {

    padding: 10px 18px;
    border-radius: 8px;
    background-color: #eee;
    color: #222;
    transition: 0.3s;

}


button:hover {

    transform: scale(1.05);

}


/* ===================================
   CONTEÚDO
   =================================== */

main {

    max-width: 1200px;
    margin: auto;
    padding: 60px 20px;
}


.titulo-secao {

    font-size: 40px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 14px;
    flex-wrap: wrap;

}


/* ===================================
   TÍTULO DO HEADER
   =================================== */

.hero-conteudo {

    text-align: center;
    padding: 0 20px;

}

.hero-titulo {

    font-size: 42px;
    font-weight: 700;
    color: white;
    text-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
    margin-bottom: 10px;

}

.hero-subtitulo {

    font-size: 16px;
    font-weight: 400;
    color: rgba(255, 255, 255, 0.85);
    margin-bottom: 0;

}


/* ===================================
   BADGE (selo pequeno)
   =================================== */

.badge {

    font-size: 13px;
    font-weight: 600;
    background-color: gold;
    color: #222;
    padding: 5px 12px;
    border-radius: 999px;
    vertical-align: middle;

}


/* ===================================
   TAGS
   =================================== */

.tags {

    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 45px;

}

.tag {

    font-size: 13px;
    font-weight: 500;
    padding: 8px 16px;
    border-radius: 999px;
    background-color: #f0f0f0;
    color: #444;
    transition: 0.3s;

}

.tag:hover {

    transform: translateY(-2px);
    background-color: #e2e2e2;

}

.tag-destaque {

    background-color: #222;
    color: white;

}


/* ===================================
   CARDS
   =================================== */

.cards {

    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
    margin-bottom: 55px;

}

.card {

    position: relative;
    background-color: #f8f8f8;
    border-radius: 16px;
    padding: 30px 24px;
    text-align: center;
    transition: 0.3s;
    border: 1px solid rgba(0, 0, 0, 0.06);

}

.card:hover {

    transform: translateY(-6px);
    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.1);

}

.card-icone {

    font-size: 34px;
    margin-bottom: 14px;

}

.card h3 {

    font-size: 20px;
    margin-bottom: 10px;

}

.card p {

    font-size: 14px;
    color: #666;
    margin-bottom: 0;

}

.card-destaque {

    background-color: #222;
    color: white;
    transform: scale(1.03);

}

.card-destaque p {

    color: rgba(255, 255, 255, 0.75);

}

.card-selo {

    position: absolute;
    top: -12px;
    right: 20px;
    background-color: gold;
    color: #222;
    font-size: 11px;
    font-weight: 700;
    text-transform: uppercase;
    padding: 5px 12px;
    border-radius: 999px;

}


/* ===================================
   ESTATÍSTICAS
   =================================== */

.stats {

    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 20px;
    text-align: center;
    background-color: #222;
    color: white;
    border-radius: 16px;
    padding: 40px 20px;
    margin-bottom: 55px;

}

.stat-numero {

    display: block;
    font-size: 34px;
    font-weight: 700;
    color: gold;

}

.stat-label {

    display: block;
    font-size: 13px;
    color: rgba(255, 255, 255, 0.7);
    margin-top: 6px;

}


/* ===================================
   BARRA DE PROGRESSO
   =================================== */

.progresso-bloco {

    margin-bottom: 55px;

}

.progresso-bloco h2 {

    font-size: 22px;
    margin-bottom: 16px;

}

.barra-progresso {

    width: 100%;
    height: 26px;
    background-color: #eee;
    border-radius: 999px;
    overflow: hidden;

}

.barra-preenchida {

    height: 100%;
    background: linear-gradient(90deg, gold, #ffb347);
    color: #222;
    font-size: 12px;
    font-weight: 700;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding-right: 12px;
    border-radius: 999px;
    transition: width 0.6s ease;

}


/* ===================================
   CITAÇÃO
   =================================== */

.citacao {

    font-size: 22px;
    font-style: italic;
    font-weight: 500;
    padding: 30px;
    border-left: 4px solid gold;
    background-color: #f8f8f8;
    border-radius: 0 16px 16px 0;
    margin-bottom: 55px;

}

.citacao cite {

    display: block;
    margin-top: 12px;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    color: #777;

}


/* ===================================
   FAQ / ACCORDION
   =================================== */

.faq h2 {

    font-size: 22px;
    margin-bottom: 20px;

}

.faq-item {

    background-color: #f8f8f8;
    border-radius: 12px;
    padding: 16px 20px;
    margin-bottom: 12px;
    transition: 0.3s;

}

.faq-item summary {

    cursor: pointer;
    font-weight: 600;
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;

}

.faq-item summary::-webkit-details-marker {

    display: none;

}

.faq-item summary::after {

    content: "+";
    font-size: 20px;
    font-weight: 400;
    color: gold;
    transition: 0.3s;

}

.faq-item[open] summary::after {

    content: "−";

}

.faq-item p {

    margin-top: 12px;
    margin-bottom: 0;
    font-size: 14px;
    color: #666;

}


p {

    margin-bottom: 30px;

}

footer {

    background-color: #222;
    color: white;
    padding: 50px 20px 0;
    transition: 0.3s;

}

.footer-conteudo {

    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 30px;
    padding-bottom: 35px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);

}

.footer-info .logo {

    color: white;

}

.footer-texto {

    margin-top: 8px;
    margin-bottom: 0;
    font-size: 14px;
    color: rgba(255, 255, 255, 0.6);

}

.redes {

    display: flex;
    justify-content: center;
    gap: 14px;

}

.rede-icone {

    display: flex;
    justify-content: center;
    align-items: center;
    width: 42px;
    height: 42px;
    border-radius: 50%;
    background-color: rgba(255, 255, 255, 0.08);
    color: white;
    transition: 0.3s;

}

.rede-icone svg {

    width: 20px;
    height: 20px;

}

.rede-icone:hover {

    background-color: gold;
    color: #222;
    transform: translateY(-4px);

}

.footer-baixo {

    max-width: 1200px;
    margin: 0 auto;
    text-align: center;
    padding: 22px 0;
    font-size: 13px;
    color: rgba(255, 255, 255, 0.5);

}

.footer-baixo p {

    margin-bottom: 0;

}


/* ===================================
   FOOTER - MODO ESCURO
   =================================== */

.escuro footer {

    background-color: #0a0a0a;

}

.escuro .footer-conteudo {

    border-bottom-color: rgba(255, 255, 255, 0.06);

}

.escuro .rede-icone {

    background-color: rgba(255, 255, 255, 0.05);

}

.escuro .rede-icone:hover {

    background-color: gold;
    color: #111;

}


/* ===================================
   MODO ESCURO
   =================================== */

.escuro {

    background-color: #222;
    color: white;

}


.escuro .navbar {

    background-color: #111;

}


.escuro button {

    background-color: #444;
    color: white;

}


/* ===================================
   MODO ESCURO - COMPONENTES NOVOS
   =================================== */

.escuro .badge {

    background-color: gold;
    color: #111;

}

.escuro .tag {

    background-color: #2c2c2c;
    color: #ddd;

}

.escuro .tag:hover {

    background-color: #3a3a3a;

}

.escuro .tag-destaque {

    background-color: gold;
    color: #111;

}

.escuro .card {

    background-color: #2a2a2a;
    border-color: rgba(255, 255, 255, 0.08);

}

.escuro .card p {

    color: #aaa;

}

.escuro .card:hover {

    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.4);

}

.escuro .card-destaque {

    background-color: #111;

}

.escuro .stats {

    background-color: #111;
    border: 1px solid rgba(255, 255, 255, 0.06);

}

.escuro .barra-progresso {

    background-color: #2c2c2c;

}

.escuro .citacao {

    background-color: #2a2a2a;
    color: #eee;

}

.escuro .citacao cite {

    color: #999;

}

.escuro .faq-item {

    background-color: #2a2a2a;

}

.escuro .faq-item p {

    color: #aaa;

}


/* ===================================
   NAVBAR - AÇÕES (cadastro + tema)
   =================================== */

.navbar-acoes {

    display: flex;
    align-items: center;
    gap: 14px;

}

.botao-cadastro {

    background-color: gold;
    color: #222;
    font-weight: 600;
    font-size: 14px;
    padding: 10px 20px;
    border-radius: 8px;
    transition: 0.3s;

}

.botao-cadastro:hover {

    transform: scale(1.05);
    filter: brightness(1.05);

}


/* ===================================
   CARROSSEL DE IMAGENS
   =================================== */

.carrossel-secao {

    margin-bottom: 55px;

}

.carrossel-secao h2 {

    font-size: 22px;
    margin-bottom: 16px;

}

.carrossel {

    position: relative;
    width: 100%;
    height: 400px;
    border-radius: 16px;
    overflow: hidden;

}

.carrossel-slides {

    display: flex;
    width: 100%;
    height: 100%;
    transition: transform 0.5s ease;

}

.carrossel-slide {

    min-width: 100%;
    height: 100%;
    object-fit: cover;

}

.carrossel-seta {

    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.4);
    color: white;
    border: none;
    width: 42px;
    height: 42px;
    border-radius: 50%;
    font-size: 16px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: 0.3s;

}

.carrossel-seta:hover {

    background-color: gold;
    color: #222;

}

.carrossel-anterior {

    left: 16px;

}

.carrossel-proximo {

    right: 16px;

}

.carrossel-pontos {

    position: absolute;
    bottom: 16px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    gap: 8px;

}

.carrossel-ponto {

    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: rgba(255, 255, 255, 0.5);
    border: none;
    cursor: pointer;
    padding: 0;
    transition: 0.3s;

}

.carrossel-ponto.ativo {

    background-color: gold;
    transform: scale(1.3);

}


/* ===================================
   VÍDEO
   =================================== */

.video-secao {

    margin-bottom: 55px;

}

.video-secao h2 {

    font-size: 22px;
    margin-bottom: 16px;

}

.video-wrapper {

    border-radius: 16px;
    overflow: hidden;
    line-height: 0;

}

.video-wrapper video {

    width: 100%;
    display: block;

}


/* ===================================
   MÚSICA
   =================================== */

.musica-secao {

    margin-bottom: 55px;

}

.musica-secao h2 {

    font-size: 22px;
    margin-bottom: 16px;

}

.player-musica {

    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    background-color: #f8f8f8;
    border-radius: 16px;
    padding: 24px;

}

.player-info {

    display: flex;
    align-items: center;
    gap: 16px;

}

.player-icone {

    width: 52px;
    height: 52px;
    border-radius: 50%;
    background-color: gold;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
    flex-shrink: 0;

}

.player-titulo {

    font-weight: 600;
    margin-bottom: 2px;

}

.player-artista {

    font-size: 13px;
    color: #777;
    margin-bottom: 0;

}

.player-musica audio {

    max-width: 100%;

}


/* ===================================
   WHATSAPP FLUTUANTE
   =================================== */

.whatsapp-flutuante {

    position: fixed;
    bottom: 24px;
    left: 24px;
    width: 56px;
    height: 56px;
    background-color: #25d366;
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.25);
    z-index: 999;
    transition: 0.3s;

}

.whatsapp-flutuante svg {

    width: 28px;
    height: 28px;

}

.whatsapp-flutuante:hover {

    transform: scale(1.1);

}


/* ===================================
   BOTÃO VOLTAR AO TOPO
   =================================== */

.botao-topo {

    position: fixed;
    bottom: 24px;
    right: 24px;
    width: 48px;
    height: 48px;
    background-color: #222;
    color: white;
    border: none;
    border-radius: 50%;
    font-size: 20px;
    cursor: pointer;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.25);
    z-index: 999;
    opacity: 0;
    visibility: hidden;
    transform: translateY(10px);
    transition: 0.3s;

}

.botao-topo.visivel {

    opacity: 1;
    visibility: visible;
    transform: translateY(0);

}

.botao-topo:hover {

    background-color: gold;
    color: #222;

}


/* ===================================
   HERO SECUNDÁRIO (páginas internas)
   =================================== */

.hero-secundaria {

    height: 220px;

}

.hero-secundaria .hero-titulo {

    font-size: 34px;

}


/* ===================================
   MODO ESCURO - COMPONENTES NOVOS (2)
   =================================== */

.escuro .botao-cadastro {

    background-color: gold;
    color: #111;

}

.escuro .carrossel-seta {

    background-color: rgba(255, 255, 255, 0.15);

}

.escuro .player-musica {

    background-color: #2a2a2a;

}

.escuro .player-artista {

    color: #999;

}

.escuro .botao-topo {

    background-color: #f0f0f0;
    color: #222;

}

.escuro .botao-topo:hover {

    background-color: gold;
    color: #111;

}


/* ===================================
   FORMULÁRIOS (Cadastro / Contato)
   =================================== */

.form-secao {

    max-width: 620px;
    margin: 0 auto 55px;

}

.form-cartao {

    background-color: #f8f8f8;
    border-radius: 16px;
    padding: 36px;

}

.campo {

    margin-bottom: 20px;

}

.campo label {

    display: block;
    font-size: 14px;
    font-weight: 600;
    margin-bottom: 8px;

}

.campo input,
.campo textarea {

    width: 100%;
    padding: 12px 14px;
    border-radius: 8px;
    border: 1px solid #ddd;
    background-color: white;
    font-family: "Poppins", sans-serif;
    font-size: 14px;
    color: #222;
    transition: 0.3s;

}

.campo input:focus,
.campo textarea:focus {

    outline: none;
    border-color: gold;

}

.campo textarea {

    resize: vertical;
    min-height: 120px;

}

.campo-checkbox {

    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 14px;

}

.campo-checkbox input {

    width: auto;

}

.botao-enviar {

    width: 100%;
    background-color: #222;
    color: white;
    font-weight: 600;
    font-size: 15px;
    padding: 14px;
    border-radius: 8px;
    transition: 0.3s;

}

.botao-enviar:hover {

    background-color: gold;
    color: #222;
    transform: none;

}

.form-sucesso {

    display: none;
    text-align: center;
    background-color: #eafaf0;
    color: #1a7f4b;
    border-radius: 12px;
    padding: 20px;
    margin-top: 16px;
    font-weight: 500;

}

.form-sucesso.visivel {

    display: block;

}


/* ===================================
   TIMELINE (História)
   =================================== */

.timeline {

    position: relative;
    max-width: 720px;
    margin: 0 auto 55px;
    padding-left: 30px;
    border-left: 3px solid gold;

}

.timeline-item {

    position: relative;
    padding-bottom: 40px;

}

.timeline-item:last-child {

    padding-bottom: 0;

}

.timeline-item::before {

    content: "";
    position: absolute;
    left: -39px;
    top: 4px;
    width: 14px;
    height: 14px;
    border-radius: 50%;
    background-color: gold;
    border: 3px solid white;

}

.timeline-ano {

    display: inline-block;
    font-size: 13px;
    font-weight: 700;
    color: #222;
    background-color: gold;
    padding: 4px 12px;
    border-radius: 999px;
    margin-bottom: 10px;

}

.timeline-item h3 {

    font-size: 18px;
    margin-bottom: 6px;

}

.timeline-item p {

    font-size: 14px;
    color: #666;
    margin-bottom: 0;

}


/* ===================================
   PÁGINA SOBRE
   =================================== */

.sobre-intro {

    max-width: 720px;
    margin: 0 auto 45px;
    text-align: center;
    font-size: 16px;
    color: #555;

}

.valores {

    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-bottom: 55px;

}


/* ===================================
   MAPA (Contato)
   =================================== */

.mapa-wrapper {

    border-radius: 16px;
    overflow: hidden;
    line-height: 0;
    margin-bottom: 55px;

}

.mapa-wrapper iframe {

    width: 100%;
    height: 350px;
    border: 0;
    display: block;

}

.info-contato {

    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 20px;
    margin-bottom: 45px;
    text-align: center;

}

.info-contato-item {

    background-color: #f8f8f8;
    border-radius: 16px;
    padding: 24px;

}

.info-contato-item .card-icone {

    margin-bottom: 8px;

}

.info-contato-item h3 {

    font-size: 15px;
    margin-bottom: 4px;

}

.info-contato-item p {

    font-size: 13px;
    color: #666;
    margin-bottom: 0;

}


/* ===================================
   MODO ESCURO - PÁGINAS NOVAS
   =================================== */

.escuro .form-cartao {

    background-color: #2a2a2a;

}

.escuro .campo input,
.escuro .campo textarea {

    background-color: #1c1c1c;
    border-color: #444;
    color: white;

}

.escuro .botao-enviar {

    background-color: #f0f0f0;
    color: #222;

}

.escuro .botao-enviar:hover {

    background-color: gold;

}

.escuro .form-sucesso {

    background-color: #133b26;
    color: #6fe3a3;

}

.escuro .timeline {

    border-left-color: gold;

}

.escuro .timeline-item::before {

    border-color: #111;

}

.escuro .timeline-item p {

    color: #aaa;

}

.escuro .sobre-intro {

    color: #bbb;

}

.escuro .info-contato-item {

    background-color: #2a2a2a;

}

.escuro .info-contato-item p {

    color: #aaa;

}
