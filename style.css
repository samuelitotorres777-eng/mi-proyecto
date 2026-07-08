@import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,500;0,9..144,600;0,9..144,700;1,9..144,500;1,9..144,600&family=Inter:wght@400;500;600;700;800&family=IBM+Plex+Mono:wght@500;600&display=swap');

:root{
  --ink:#0C3B36;
  --ink-70:rgba(12,59,54,.72);
  --ink-45:rgba(12,59,54,.45);
  --ocean:#146B8C;
  --coral:#F1502F;
  --coral-dark:#D6401F;
  --gold:#E8A93C;
  --mist:#F4F7F5;
  --mist-2:#E9F0EE;
  --paper:#FFFFFF;
  --line:rgba(12,59,54,.16);
  --shadow:0 16px 40px rgba(12,59,54,.14);
  --radius:20px;
}
*{box-sizing:border-box;}
html{scroll-behavior:smooth;}
html, body{max-width:100%;overflow-x:hidden;}
body{margin:0;background:var(--mist);color:var(--ink);font-family:'Inter',sans-serif;-webkit-font-smoothing:antialiased;}
h1,h2,h3{font-family:'Fraunces',serif;margin:0;color:var(--ink);letter-spacing:-.01em;}
p{margin:0;}
a{color:inherit;text-decoration:none;}
img{max-width:100%;display:block;}
button{font-family:inherit;cursor:pointer;border:none;background:none;color:inherit;}
:focus-visible{outline:3px solid var(--gold);outline-offset:3px;}
.mono{font-family:'IBM Plex Mono',monospace;letter-spacing:.06em;text-transform:uppercase;}
.wrap{max-width:1180px;margin:0 auto;padding:0 clamp(1.25rem,4vw,2.5rem);}
.eyebrow{font-family:'IBM Plex Mono',monospace;font-size:.72rem;letter-spacing:.14em;text-transform:uppercase;color:var(--coral);font-weight:600;}
section{position:relative;}
.section-pad{padding:clamp(3rem,7vw,5rem) 0;}
@media (prefers-reduced-motion: reduce){*{animation-duration:.001ms !important;animation-iteration-count:1 !important;transition-duration:.001ms !important;scroll-behavior:auto !important;}}

/* views */
.view{display:none;}
.view.active{display:block;}

/* ---------- NAV ---------- */
header{position:sticky;top:0;z-index:100;background:rgba(244,247,245,.9);backdrop-filter:blur(10px);border-bottom:1px solid var(--line);}
.nav{display:flex;align-items:center;justify-content:space-between;padding:1rem clamp(1.25rem,4vw,2.5rem);max-width:1180px;margin:0 auto;gap:1rem;}
.logo{display:flex;align-items:baseline;gap:.4rem;font-family:'Fraunces',serif;font-weight:700;font-size:1.4rem;color:var(--ink);flex-shrink:0;}
.logo span{font-family:'IBM Plex Mono',monospace;font-size:.6rem;font-weight:600;letter-spacing:.16em;text-transform:uppercase;color:var(--ocean);transform:translateY(-2px);}
.nav-links{display:flex;gap:1.4rem;list-style:none;margin:0;padding:0;}
.nav-links button{font-size:.86rem;font-weight:500;color:var(--ink-70);position:relative;padding:.3rem 0;white-space:nowrap;}
.nav-links button::after{content:"";position:absolute;left:0;bottom:0;width:0;height:2px;background:var(--coral);transition:width .25s ease;}
.nav-links button:hover{color:var(--ink);}
.nav-links button:hover::after, .nav-links button.active::after{width:100%;}
.nav-links button.active{color:var(--ink);font-weight:700;}
.nav-cta{display:flex;align-items:center;gap:.5rem;background:var(--ink);color:var(--mist);padding:.65rem 1.2rem;border-radius:100px;font-size:.84rem;font-weight:600;transition:transform .2s, background .2s;flex-shrink:0;}
.nav-cta:hover{background:var(--coral);transform:translateY(-1px);}
.burger{display:none;width:26px;height:20px;position:relative;flex-shrink:0;}
.burger span{position:absolute;left:0;width:100%;height:2px;background:var(--ink);border-radius:2px;transition:.25s;}
.burger span:nth-child(1){top:0;} .burger span:nth-child(2){top:9px;} .burger span:nth-child(3){top:18px;}
.burger.open span:nth-child(1){top:9px;transform:rotate(45deg);}
.burger.open span:nth-child(2){opacity:0;}
.burger.open span:nth-child(3){top:9px;transform:rotate(-45deg);}
.mobile-panel{display:none;flex-direction:column;gap:.2rem;padding:0 clamp(1.25rem,4vw,2.5rem) 1.3rem;}
.mobile-panel button{text-align:left;font-size:1rem;font-weight:500;padding:.6rem 0;border-bottom:1px solid var(--line);}
.mobile-panel.show{display:flex;}

/* ---------- HERO (inicio) ---------- */
.hero{
  background:radial-gradient(120% 90% at 85% 0%, rgba(232,169,60,.35), transparent 55%),
    linear-gradient(160deg, #0C3B36 0%, #0F4D50 38%, #146B8C 78%, #1C7C8C 100%);
  color:var(--mist);padding:clamp(3.5rem,8vw,6rem) 0 4.5rem;overflow:hidden;
}
.hero-inner{max-width:1180px;margin:0 auto;padding:0 clamp(1.25rem,4vw,2.5rem);display:grid;grid-template-columns:1.1fr .7fr;gap:3rem;align-items:end;}
.hero-copy .eyebrow{color:var(--gold);}
.hero-copy h1{color:#fff;font-size:clamp(2.3rem,5vw,3.7rem);line-height:1.03;font-weight:600;margin:.9rem 0 1.3rem;}
.hero-copy h1 em{font-style:italic;font-weight:500;color:var(--gold);}
.hero-copy p{font-size:1.04rem;line-height:1.55;color:rgba(244,247,245,.82);max-width:44ch;}
.hero-stats{display:flex;gap:2rem;margin-top:2rem;flex-wrap:wrap;}
.hero-stats div{border-left:2px solid rgba(232,169,60,.5);padding-left:.8rem;}
.hero-stats strong{display:block;font-family:'Fraunces',serif;font-size:1.4rem;color:#fff;}
.hero-stats span{font-size:.78rem;color:rgba(244,247,245,.7);}
.hero-flight{align-self:end;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.22);border-radius:var(--radius);padding:1.3rem;backdrop-filter:blur(6px);}
.hero-flight .route{display:flex;align-items:center;justify-content:space-between;font-family:'IBM Plex Mono',monospace;font-size:1.5rem;color:#fff;font-weight:600;}
.hero-flight .route .arrow{opacity:.6;font-size:1.05rem;}
.hero-flight .sub{font-size:.72rem;color:rgba(244,247,245,.65);margin-top:.3rem;letter-spacing:.08em;text-transform:uppercase;font-family:'IBM Plex Mono',monospace;}
.hero-flight .barcode{margin-top:1rem;height:30px;border-radius:4px;background:repeating-linear-gradient(90deg, rgba(255,255,255,.85) 0 2px, transparent 2px 5px, rgba(255,255,255,.5) 5px 6px, transparent 6px 9px);}

/* ---------- MENU DE CATEGORIAS (inicio) ---------- */
.menu-panel{max-width:1180px;margin:-3.2rem auto 0;padding:0 clamp(1.25rem,4vw,2.5rem);position:relative;z-index:5;}
.menu-grid{display:grid;grid-template-columns:repeat(6,1fr);gap:1rem;}
.menu-tile{
  background:var(--paper);border-radius:16px;box-shadow:var(--shadow);
  padding:1.5rem 1.1rem;display:flex;flex-direction:column;align-items:center;gap:.7rem;text-align:center;
  transition:transform .2s ease, box-shadow .2s ease;
}
.menu-tile:hover{transform:translateY(-5px);box-shadow:0 20px 40px rgba(12,59,54,.2);}
.menu-tile .icon{width:34px;height:34px;color:var(--ocean);}
.menu-tile strong{font-size:.92rem;font-weight:700;}
.menu-tile span{font-size:.72rem;color:var(--ink-45);font-family:'IBM Plex Mono',monospace;text-transform:uppercase;letter-spacing:.04em;}
@media (max-width:900px){.menu-grid{grid-template-columns:repeat(3,1fr);}}
@media (max-width:560px){.menu-grid{grid-template-columns:repeat(2,1fr);}}

/* ---------- WHY US ---------- */
.why-section{background:var(--ink);color:var(--mist);}
.why-section .eyebrow{color:var(--gold);}
.section-head{max-width:640px;margin:0 auto 2.4rem;text-align:left;}
.section-head h2{font-size:clamp(1.7rem,3.2vw,2.3rem);font-weight:600;margin-top:.6rem;line-height:1.1;}
.section-head p{color:var(--ink-70);margin-top:.8rem;font-size:1rem;line-height:1.55;}
.why-section .section-head h2{color:#fff;}
.why-section .section-head p{color:rgba(244,247,245,.72);}
.why-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:1.4rem;}
.why-card{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.14);border-radius:16px;padding:1.5rem 1.3rem;}
.why-card .icon{width:36px;height:36px;margin-bottom:1rem;color:var(--gold);}
.why-card h3{color:#fff;font-size:1.05rem;font-weight:600;margin-bottom:.5rem;}
.why-card p{font-size:.85rem;color:rgba(244,247,245,.68);line-height:1.5;}
@media (max-width:900px){.why-grid{grid-template-columns:1fr 1fr;}}
@media (max-width:560px){.why-grid{grid-template-columns:1fr;}}

/* ---------- TESTIMONIALS ---------- */
.testi-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.4rem;}
.testi-card{background:var(--paper);border-radius:16px;padding:1.5rem;box-shadow:0 8px 20px rgba(12,59,54,.08);display:flex;flex-direction:column;gap:.9rem;}
.testi-card .stars{color:var(--gold);letter-spacing:.15em;font-size:.88rem;}
.testi-card p.quote{font-family:'Fraunces',serif;font-style:italic;font-size:1rem;line-height:1.5;color:var(--ink);}
.testi-card .author{display:flex;align-items:center;gap:.7rem;}
.testi-card .avatar{width:36px;height:36px;border-radius:50%;background:var(--mist-2);display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-weight:600;color:var(--ocean);font-size:.85rem;}
.testi-card .author strong{display:block;font-size:.86rem;}
.testi-card .author span{font-size:.74rem;color:var(--ink-45);}
@media (max-width:900px){.testi-grid{grid-template-columns:1fr;}}

/* ---------- CATEGORY PAGE ---------- */
.cat-hero{background:linear-gradient(160deg, #0C3B36 0%, #146B8C 100%);color:#fff;padding:2.4rem 0 3.2rem;}
.back-btn{display:inline-flex;align-items:center;gap:.4rem;font-size:.82rem;font-weight:600;color:rgba(244,247,245,.8);margin-bottom:1.1rem;}
.back-btn:hover{color:#fff;}
.cat-hero .eyebrow{color:var(--gold);}
.cat-hero h2{color:#fff;font-size:clamp(1.9rem,3.6vw,2.6rem);margin-top:.5rem;}
.cat-hero p{color:rgba(244,247,245,.78);margin-top:.6rem;max-width:56ch;line-height:1.55;}

.filter-card{background:var(--paper);border-radius:var(--radius);box-shadow:var(--shadow);padding:1.5rem;margin-top:-2.2rem;position:relative;z-index:5;}
.filter-fields{display:grid;grid-template-columns:repeat(3,1fr) auto;gap:1rem;align-items:end;}
.field label{display:block;font-size:.68rem;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--ink-45);margin-bottom:.4rem;}
.field input, .field select{width:100%;padding:.72rem .85rem;border:1.5px solid var(--line);border-radius:10px;font-family:'Inter',sans-serif;font-size:.9rem;color:var(--ink);background:var(--mist);}
.field input:focus, .field select:focus{border-color:var(--ocean);}
.filter-btn{background:var(--coral);color:#fff;padding:.8rem 1.4rem;border-radius:10px;font-weight:700;font-size:.9rem;white-space:nowrap;transition:background .2s, transform .2s;}
.filter-btn:hover{background:var(--coral-dark);transform:translateY(-1px);}
@media (max-width:820px){.filter-fields{grid-template-columns:1fr 1fr;}.filter-btn{grid-column:1/-1;}}

.offer-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.5rem;margin-top:2.4rem;}
.offer-card{background:var(--paper);border-radius:16px;overflow:hidden;box-shadow:0 10px 26px rgba(12,59,54,.1);transition:transform .25s ease, box-shadow .25s ease;display:flex;flex-direction:column;}
.offer-card:hover{transform:translateY(-5px);box-shadow:0 18px 34px rgba(12,59,54,.18);}
.offer-card .photo{position:relative;height:170px;background:var(--mist-2);}
.offer-card .photo img{width:100%;height:100%;object-fit:cover;}
.offer-card .badge{position:absolute;top:.7rem;left:.7rem;background:var(--coral);color:#fff;font-family:'IBM Plex Mono',monospace;padding:.32rem .6rem;border-radius:8px;font-size:.68rem;font-weight:700;letter-spacing:.03em;}
.offer-card .body{padding:1.15rem 1.2rem .3rem;flex:1;display:flex;flex-direction:column;gap:.5rem;}
.offer-card h3{font-size:1.12rem;font-weight:600;}
.offer-card .desc{font-size:.85rem;color:var(--ink-70);line-height:1.5;}
.offer-card .tags{display:flex;gap:.4rem;flex-wrap:wrap;}
.offer-card .tags span{font-size:.66rem;font-family:'IBM Plex Mono',monospace;letter-spacing:.05em;text-transform:uppercase;background:var(--mist-2);color:var(--ink-70);padding:.24rem .5rem;border-radius:6px;}
.offer-card .price-row{display:flex;align-items:baseline;gap:.55rem;margin-top:.2rem;}
.offer-card .price-old{text-decoration:line-through;color:var(--ink-45);font-size:.82rem;}
.offer-card .price-new{font-family:'Fraunces',serif;font-size:1.3rem;font-weight:700;color:var(--ink);}
.offer-card .price-unit{font-size:.72rem;color:var(--ink-45);}
.offer-card .divider{border-top:2px dashed var(--line);margin:.9rem 1.2rem 0;}
.offer-card .cta-row{padding:.9rem 1.2rem 1.2rem;}
.offer-card .cotizar{width:100%;background:var(--ink);color:#fff;padding:.75rem;border-radius:10px;font-weight:700;font-size:.85rem;transition:background .2s;}
.offer-card .cotizar:hover{background:var(--coral);}
@media (max-width:900px){.offer-grid{grid-template-columns:1fr 1fr;}}
@media (max-width:600px){.offer-grid{grid-template-columns:1fr;}}

/* ---------- FOOTER ---------- */
footer{background:var(--ink);color:rgba(244,247,245,.75);padding:3.2rem 0 2rem;}
.footer-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr;gap:2.5rem;}
.footer-grid h4{color:#fff;font-family:'IBM Plex Mono',monospace;font-size:.72rem;letter-spacing:.1em;text-transform:uppercase;margin-bottom:1rem;font-weight:600;}
.footer-grid ul{list-style:none;margin:0;padding:0;display:flex;flex-direction:column;gap:.55rem;font-size:.86rem;}
.footer-grid ul button{color:rgba(244,247,245,.75);text-align:left;}
.footer-grid ul button:hover{color:#fff;}
.footer-brand .logo{color:#fff;}
.footer-brand p{margin-top:.9rem;font-size:.86rem;line-height:1.6;max-width:34ch;color:rgba(244,247,245,.65);}
.footer-bottom{border-top:1px solid rgba(255,255,255,.14);margin-top:2.6rem;padding-top:1.4rem;display:flex;justify-content:space-between;flex-wrap:wrap;gap:1rem;font-size:.78rem;color:rgba(244,247,245,.5);}
@media (max-width:760px){.footer-grid{grid-template-columns:1fr 1fr;}}
@media (max-width:520px){.footer-grid{grid-template-columns:1fr;}}

/* ---------- FLOATING WHATSAPP ---------- */
.wa-float{position:fixed;right:1.4rem;bottom:1.4rem;z-index:200;width:58px;height:58px;border-radius:50%;background:#25D366;display:flex;align-items:center;justify-content:center;box-shadow:0 10px 24px rgba(12,59,54,.35);animation:pulse 2.6s ease-in-out infinite;}
.wa-float:hover{background:#1FBD5A;}
@keyframes pulse{0%,100%{box-shadow:0 10px 24px rgba(12,59,54,.35);}50%{box-shadow:0 10px 24px rgba(37,211,102,.55), 0 0 0 8px rgba(37,211,102,.12);}}

@media (max-width:960px){
  .nav-links, .nav-cta{display:none;}
  .burger{display:block;}
  .hero-inner{grid-template-columns:1fr;}
  .why-grid{grid-template-columns:1fr 1fr;}
  .filter-fields{grid-template-columns:1fr 1fr;}
}

/* ---------- AJUSTES FINOS PARA CELULARES ---------- */
@media (max-width:480px){
  .nav{padding:.85rem 1.1rem;}
  .logo{font-size:1.2rem;}
  .hero{padding:2.4rem 0 3rem;}
  .hero-copy p{max-width:none;}
  .hero-stats{gap:1.3rem;}
  .hero-flight{padding:1.1rem;}
  .hero-flight .route{font-size:1.25rem;}
  .menu-panel{margin-top:-2.2rem;}
  .menu-tile{padding:1.2rem .7rem;}
  .why-card, .testi-card{padding:1.2rem 1.1rem;}
  .cat-hero{padding:2rem 0 2.4rem;}
  .filter-card{padding:1.2rem;margin-top:-1.6rem;}
  .filter-fields{grid-template-columns:1fr;}
  .offer-card .photo{height:150px;}
  .footer-bottom{flex-direction:column;align-items:flex-start;}
}
@media (max-width:360px){
  .menu-grid{grid-template-columns:1fr 1fr;gap:.7rem;}
  .hero-copy h1{font-size:1.9rem;}
}
@media (max-width:600px){
  .wa-float{width:52px;height:52px;right:1rem;bottom:1rem;}
  .wa-float svg{width:24px;height:24px;}
  .nav-cta, .search-btn, .filter-btn, .contact-submit, .offer-card .cotizar{min-height:44px;}
  .cookie-actions{flex-wrap:wrap;}
  .cookie-btn{flex:1;text-align:center;}
}

/* ---------- COOKIES ---------- */
.cookie-banner{
  position:fixed;left:0;right:0;bottom:0;z-index:300;
  background:var(--ink);color:var(--mist);
  padding:1.1rem clamp(1.25rem,4vw,2.5rem);
  display:flex;align-items:center;justify-content:space-between;gap:1.5rem;
  box-shadow:0 -10px 30px rgba(12,59,54,.25);
  transform:translateY(120%);transition:transform .4s ease;
}
.cookie-banner.show{transform:translateY(0);}
.cookie-text strong{display:block;font-family:'Fraunces',serif;font-size:1rem;margin-bottom:.3rem;color:#fff;}
.cookie-text p{font-size:.82rem;line-height:1.5;color:rgba(244,247,245,.75);max-width:62ch;}
.cookie-actions{display:flex;gap:.7rem;flex-shrink:0;}
.cookie-btn{padding:.7rem 1.3rem;border-radius:100px;font-size:.85rem;font-weight:700;white-space:nowrap;transition:.2s;}
.cookie-btn.accept{background:var(--coral);color:#fff;}
.cookie-btn.accept:hover{background:var(--coral-dark);}
.cookie-btn.reject{background:transparent;border:1.5px solid rgba(244,247,245,.35);color:rgba(244,247,245,.85);}
.cookie-btn.reject:hover{border-color:#fff;color:#fff;}
@media (max-width:700px){
  .cookie-banner{flex-direction:column;align-items:stretch;text-align:left;padding:1.1rem 1.25rem;}
  .cookie-actions{justify-content:flex-end;}
}
