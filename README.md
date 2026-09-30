<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Investigación y estrategia de ingreso al mercado peruano para una categoría Yonige-ya: contexto, oportunidad, etapas y cuatro piezas de contenido.">
<title>Yonige-ya | Estrategia de ingreso al mercado peruano</title>
<style>
  :root{
    --ink:#10131a;
    --muted:#616978;
    --paper:#f7f3ed;
    --white:#fffdf9;
    --red:#c92e3a;
    --red-dark:#8e1e29;
    --red-soft:#f7d9dc;
    --gold:#c69a54;
    --line:#e6dfd5;
    --shadow:0 20px 60px rgba(22,22,30,.10);
    --radius:22px;
  }
  *{box-sizing:border-box;scroll-behavior:smooth}
  body{
    margin:0;
    color:var(--ink);
    background:linear-gradient(180deg,#fbf8f3 0%,#f4eee6 100%);
    font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Arial,sans-serif;
    line-height:1.6;
  }
  a{color:inherit}
  .topbar{
    position:sticky;top:0;z-index:50;
    backdrop-filter:blur(16px);
    background:rgba(251,248,243,.88);
    border-bottom:1px solid rgba(201,46,58,.10);
  }
  .nav{
    width:min(1180px,92%);margin:auto;
    display:flex;align-items:center;justify-content:space-between;
    padding:14px 0;
  }
  .brand{display:flex;gap:10px;align-items:center;font-weight:800;letter-spacing:.04em}
  .brand-mark{width:34px;height:34px;border-radius:50%;background:var(--red);display:grid;place-items:center;color:#fff;font-size:18px;box-shadow:0 6px 18px rgba(201,46,58,.25)}
  .navlinks{display:flex;gap:20px;font-size:13px;color:var(--muted);font-weight:650}
  .navlinks a{text-decoration:none}
  .navlinks a:hover{color:var(--red)}
  .hero{
    position:relative;overflow:hidden;
    padding:90px 0 72px;
    background:
      radial-gradient(circle at 85% 12%, rgba(201,46,58,.14), transparent 28%),
      radial-gradient(circle at 12% 76%, rgba(198,154,84,.12), transparent 24%),
      linear-gradient(135deg,#fffdf9 0%,#f7eee9 55%,#f3e7df 100%);
  }
  .hero:before{content:"";position:absolute;inset:0;background:linear-gradient(90deg,transparent 0 48%,rgba(201,46,58,.035) 48% 49%,transparent 49% 100%);pointer-events:none}
  .wrap{width:min(1180px,92%);margin:auto;position:relative}
  .eyebrow{display:inline-flex;align-items:center;gap:9px;background:#fff;border:1px solid var(--line);border-radius:999px;padding:7px 13px;color:var(--red-dark);font-weight:800;font-size:12px;letter-spacing:.08em;text-transform:uppercase;box-shadow:0 8px 22px rgba(30,20,15,.05)}
  .hero-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:48px;align-items:center}
  h1{font-size:clamp(42px,6vw,76px);line-height:.98;letter-spacing:-.055em;margin:22px 0 18px;max-width:820px}
  h1 span{color:var(--red)}
  .lead{font-size:20px;line-height:1.55;color:#373d49;max-width:720px;margin:0 0 28px}
  .mini-note{font-size:12px;color:var(--muted);max-width:720px}
  .hero-card{background:rgba(255,253,249,.82);border:1px solid rgba(201,46,58,.12);border-radius:30px;padding:26px;box-shadow:var(--shadow);position:relative}
  .jp{font-size:58px;line-height:1;font-weight:800;margin-bottom:8px}
  .hero-card h3{margin:6px 0 10px;font-size:25px}
  .hero-card p{margin:0;color:var(--muted)}
  .hero-card .pill-row{display:flex;flex-wrap:wrap;gap:8px;margin-top:18px}
  .pill{font-size:12px;font-weight:800;padding:7px 10px;border-radius:999px;background:#f6ebdc;border:1px solid #ead9bf;color:#6a4b22}
  .section{padding:82px 0}
  .section.alt{background:rgba(255,255,255,.55);border-top:1px solid rgba(0,0,0,.03);border-bottom:1px solid rgba(0,0,0,.03)}
  .section-head{max-width:830px;margin-bottom:36px}
  .kicker{color:var(--red);font-weight:850;font-size:12px;letter-spacing:.1em;text-transform:uppercase;margin-bottom:10px}
  h2{font-size:clamp(30px,4vw,48px);line-height:1.08;letter-spacing:-.04em;margin:0 0 14px}
  .section-head p{font-size:17px;color:var(--muted);margin:0}
  .grid-2{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:22px}
  .grid-3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:22px}
  .card{background:var(--white);border:1px solid var(--line);border-radius:var(--radius);padding:26px;box-shadow:0 12px 36px rgba(31,26,21,.06)}
  .card h3{margin:0 0 8px;font-size:20px;line-height:1.2}
  .card p{margin:0;color:var(--muted)}
  .card strong{color:var(--ink)}
  .accent{border-top:5px solid var(--red)}
  .definition{display:grid;grid-template-columns:.7fr 1.3fr;gap:30px;align-items:stretch}
  .definition .quote{background:linear-gradient(145deg,var(--red-dark),var(--red));color:#fff;border-radius:28px;padding:34px;display:flex;flex-direction:column;justify-content:center;box-shadow:0 18px 42px rgba(142,30,41,.20)}
  .quote small{opacity:.78;text-transform:uppercase;letter-spacing:.12em;font-weight:800}
  .quote .big{font-size:32px;line-height:1.12;font-weight:900;letter-spacing:-.03em;margin-top:12px}
  .quote p{margin:16px 0 0;color:#fdeef0}
  .meaning-list{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:18px}
  .meaning-item{padding:14px;border-radius:16px;background:#faf5ef;border:1px solid var(--line)}
  .meaning-item b{display:block;font-size:18px}
  .two-col-list{display:grid;grid-template-columns:1fr 1fr;gap:16px}
  .list{padding:0;margin:10px 0 0;display:grid;gap:8px}
  .list li{list-style:none;position:relative;padding-left:24px;color:#505765}
  .list li:before{content:"✓";position:absolute;left:0;color:var(--red);font-weight:900}
  .x-list li:before{content:"×"}
  .process{display:grid;grid-template-columns:repeat(5,1fr);gap:12px;align-items:stretch}
  .step{background:#fff;border:1px solid var(--line);border-radius:18px;padding:20px;position:relative;box-shadow:0 10px 28px rgba(30,20,15,.05)}
  .step:not(:last-child):after{content:"→";position:absolute;right:-12px;top:50%;transform:translateY(-50%);font-size:23px;font-weight:900;color:var(--gold);z-index:3}
  .num{width:34px;height:34px;border-radius:50%;display:grid;place-items:center;background:var(--red);color:#fff;font-weight:900;font-size:13px;margin-bottom:12px}
  .step h3{font-size:16px;margin:0 0 6px}
  .step p{font-size:13px;color:var(--muted);margin:0}
  .opportunity{display:grid;grid-template-columns:1fr 1fr;gap:24px}
  .contrast{background:#fff;border:1px solid var(--line);border-radius:24px;padding:28px}
  .contrast .label{font-weight:850;color:var(--muted);font-size:12px;text-transform:uppercase;letter-spacing:.09em}
  .contrast h3{font-size:25px;margin:8px 0 8px}
  .contrast ul{margin:14px 0 0;padding:0;display:grid;gap:10px}
  .contrast li{list-style:none;padding:13px 15px;border-radius:14px;background:#faf8f5;border:1px solid #eee8df}
  .contrast.highlight{background:linear-gradient(135deg,#fff7f7,#fffdf9);border-color:#f1c6cb}
  .strategy-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:24px}
  .strategy{background:#fff;border:1px solid var(--line);border-radius:26px;overflow:hidden;box-shadow:0 12px 38px rgba(34,27,21,.07)}
  .strategy-top{padding:20px 24px;background:linear-gradient(135deg,#161a21,#2c3038);color:#fff;display:flex;justify-content:space-between;gap:20px;align-items:flex-start}
  .strategy-top .tag{font-size:11px;font-weight:900;letter-spacing:.1em;text-transform:uppercase;opacity:.74}
  .strategy-top h3{font-size:25px;margin:5px 0 0;letter-spacing:-.03em}
  .strategy-top .icon{font-size:28px}
  .strategy-body{padding:24px}
  .meta{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:18px}
  .meta-card{background:#faf7f2;border:1px solid var(--line);border-radius:15px;padding:13px}
  .meta-card b{display:block;font-size:11px;text-transform:uppercase;letter-spacing:.08em;color:var(--muted);margin-bottom:4px}
  .meta-card span{font-size:14px;font-weight:750}
  .copy{background:#11151c;color:#fff;border-radius:18px;padding:20px;margin-top:18px;position:relative;overflow:hidden}
  .copy:before{content:"“";position:absolute;right:10px;top:-30px;font-size:130px;color:rgba(255,255,255,.06);font-weight:900}
  .copy p{margin:0;position:relative;z-index:1;font-size:16px;line-height:1.58}
  .cta{display:inline-flex;align-items:center;gap:7px;margin-top:16px;padding:11px 14px;border-radius:12px;background:var(--red);color:#fff;font-weight:850;text-decoration:none;font-size:13px}
  .funnel{display:grid;grid-template-columns:repeat(5,1fr);gap:10px}
  .funnel .f{padding:18px;border-radius:18px;text-align:center;border:1px solid var(--line);font-weight:800;background:#fff}
  .funnel .f b{display:block;color:var(--red);font-size:12px;text-transform:uppercase;letter-spacing:.08em;margin-bottom:6px}
  .sources{display:grid;gap:12px}
  .source{display:flex;gap:12px;align-items:flex-start;padding:15px 16px;border-radius:16px;background:#fff;border:1px solid var(--line)}
  .source-badge{min-width:32px;height:32px;border-radius:10px;background:#f6e1e3;color:var(--red-dark);display:grid;place-items:center;font-weight:900;font-size:12px}
  .source a{font-weight:800;text-decoration:none;color:#2a313c}
  .source p{margin:4px 0 0;font-size:13px;color:var(--muted)}
  .final-callout{margin-top:34px;background:linear-gradient(135deg,var(--red-dark),var(--red));color:#fff;border-radius:30px;padding:36px;display:grid;grid-template-columns:1.2fr .8fr;gap:28px;align-items:center;box-shadow:0 22px 48px rgba(142,30,41,.18)}
  .final-callout h3{font-size:30px;line-height:1.1;margin:0 0 10px}
  .final-callout p{margin:0;color:#fdeff0}
  .final-badge{justify-self:end;background:rgba(255,255,255,.10);border:1px solid rgba(255,255,255,.20);border-radius:20px;padding:24px;text-align:center}
  .final-badge .jp2{font-size:48px;line-height:1;font-weight:900}
  footer{padding:34px 0 54px;color:var(--muted);font-size:12px}
  .footer-line{height:1px;background:var(--line);margin-bottom:18px}
  .note{font-size:12px;color:var(--muted);margin-top:16px}
  @media(max-width:980px){
    .navlinks{display:none}
    .hero-grid,.definition,.opportunity,.final-callout{grid-template-columns:1fr}
    .grid-3{grid-template-columns:1fr 1fr}
    .process{grid-template-columns:1fr 1fr}
    .step:not(:last-child):after{display:none}
    .funnel{grid-template-columns:1fr 1fr}
    .final-badge{justify-self:start}
  }
  @media(max-width:680px){
    .section{padding:60px 0}
    .hero{padding:70px 0 54px}
    .grid-2,.grid-3,.strategy-grid,.two-col-list,.meaning-list{grid-template-columns:1fr}
    .meta{grid-template-columns:1fr}
    .process{grid-template-columns:1fr}
    .funnel{grid-template-columns:1fr}
    h1{font-size:46px}
  }
</style>
</head>
<body>

<header class="topbar">
  <nav class="nav">
    <div class="brand"><div class="brand-mark">夜</div><div>YONIGE-YA · PERÚ</div></div>
    <div class="navlinks">
      <a href="#que-es">Qué es</a>
      <a href="#usuarios">Usuarios</a>
      <a href="#producto">Servicio</a>
      <a href="#peru">Perú</a>
      <a href="#estrategias">Estrategias</a>
      <a href="#fuentes">Fuentes</a>
    </div>
  </nav>
</header>

<section class="hero">
  <div class="wrap hero-grid">
    <div>
      <div class="eyebrow">Investigación + estrategia de contenido</div>
      <h1>No se trata de <span>desaparecer.</span><br>Se trata de empezar de nuevo.</h1>
      <p class="lead">Propuesta de introducción de la categoría <strong>Yonige-ya (夜逃げ屋)</strong> al mercado peruano: definición, usuarios, propuesta de valor, oportunidad cultural y cuatro estrategias de contenido conectadas.</p>
      <div class="mini-note">Documento planteado para presentación académica / marketing. La tendencia de “48 horas” se utiliza como contexto cultural, no como producto ni como incentivo para ocultar el paradero de una persona.</div>
    </div>
    <aside class="hero-card">
      <div class="jp">夜逃げ屋</div>
      <h3>Yonige-ya</h3>
      <p>Categoría japonesa asociada a salidas y mudanzas discretas en situaciones especiales.</p>
      <div class="pill-row">
        <span class="pill">Urgencia</span>
        <span class="pill">Privacidad</span>
        <span class="pill">Logística</span>
        <span class="pill">Orientación</span>
      </div>
    </aside>
  </div>
</section>

<section class="section" id="que-es">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">01 · Definición</div>
      <h2>¿Qué es realmente un Yonige-ya?</h2>
      <p>El término japonés <strong>夜逃げ (yonige)</strong> significa literalmente una huida o partida durante la noche. <strong>夜逃げ屋 (yonige-ya)</strong> se usa para referirse a operadores que ayudan con este tipo de salida. El uso moderno puede abarcar mudanzas y apoyos para circunstancias especiales.</p>
    </div>

    <div class="definition">
      <div class="quote">
        <small>Idea central</small>
        <div class="big">No es una empresa para “desaparecer por diversión”.</div>
        <p>Es una categoría de servicio que puede combinar logística de mudanza, discreción y orientación para situaciones en las que una mudanza convencional no resuelve todo el problema.</p>
      </div>
      <div class="card">
        <h3>Significado del término</h3>
        <div class="meaning-list">
          <div class="meaning-item"><b>夜</b><span>noche</span></div>
          <div class="meaning-item"><b>逃げ</b><span>huida / escape</span></div>
          <div class="meaning-item"><b>屋</b><span>establecimiento / negocio especializado</span></div>
        </div>
        <p style="margin-top:20px">Kotobank define <strong>夜逃げ</strong> como marcharse o desaparecer discretamente durante la noche y define <strong>夜逃げ屋</strong> como un negocio que ayuda a organizar este tipo de salida, incluyendo casos vinculados con deudas, violencia y stalking.</p>
      </div>
    </div>
  </div>
</section>

<section class="section alt" id="usuarios">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">02 · Público y necesidad</div>
      <h2>¿Quién utiliza este tipo de servicio?</h2>
      <p>Los casos documentados por operadores japoneses muestran que la categoría se relaciona con personas que enfrentan circunstancias especiales y necesitan una salida rápida, discreta y organizada.</p>
    </div>
    <div class="grid-2">
      <div class="card accent">
        <h3>Situaciones frecuentes</h3>
        <ul class="list">
          <li>Violencia doméstica (DV).</li>
          <li>Stalking o acoso.</li>
          <li>Problemas familiares.</li>
          <li>Endeudamiento o presión financiera.</li>
          <li>Problemas de vivienda o cambios urgentes.</li>
          <li>Necesidad de trasladar pertenencias con discreción.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Insight de negocio</h3>
        <p style="font-size:24px;line-height:1.25;color:var(--ink);font-weight:850;margin-bottom:15px">“Necesito salir de donde estoy, pero no sé cómo hacerlo de forma segura, rápida y organizada.”</p>
        <p>El valor no está en “desaparecer”, sino en <strong>resolver el proceso de salida</strong> cuando una mudanza tradicional no es suficiente.</p>
      </div>
    </div>
  </div>
</section>

<section class="section" id="producto">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">03 · Propuesta de servicio</div>
      <h2>¿Qué vende realmente la categoría?</h2>
      <p>La propuesta se entiende mejor como una combinación de <strong>mudanza + discreción + rapidez + planificación + acompañamiento</strong>, según el operador y el caso.</p>
    </div>
    <div class="grid-3">
      <div class="card">
        <h3>Antes</h3>
        <ul class="list">
          <li>Orientación inicial.</li>
          <li>Evaluación de la situación.</li>
          <li>Planificación del traslado.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Durante</h3>
        <ul class="list">
          <li>Embalaje y traslado.</li>
          <li>Logística rápida.</li>
          <li>Manejo discreto de pertenencias.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Después</h3>
        <ul class="list">
          <li>Instalación / cambio de entorno.</li>
          <li>Orientación posterior, según servicio.</li>
          <li>Coordinación con profesionales cuando corresponde.</li>
        </ul>
      </div>
    </div>
    <p class="note">Importante: la oferta concreta depende de la empresa. Algunas declaran coordinación con abogados u otros especialistas; esto no convierte al operador logístico en un sustituto de las autoridades o de la asesoría legal.</p>
  </div>
</section>

<section class="section alt" id="peru">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">04 · Oportunidad en Perú</div>
      <h2>La tendencia de las 48 horas es contexto, no producto</h2>
      <p>En septiembre de 2026, medios peruanos reportaron nuevamente el llamado “reto de las 48 horas”, una dinámica de redes donde adolescentes se ausentan y cortan la comunicación con sus familias. Esa conversación permite introducir una categoría desconocida, pero las dos ideas deben mantenerse claramente separadas.</p>
    </div>
    <div class="opportunity">
      <div class="contrast">
        <div class="label">Tendencia peruana</div>
        <h3>“Desaparecer por 48 horas”</h3>
        <ul>
          <li>Dinámica difundida en redes.</li>
          <li>Implica cortar comunicación y ocultar el paradero.</li>
          <li>Puede provocar una emergencia familiar y riesgos para menores.</li>
        </ul>
      </div>
      <div class="contrast highlight">
        <div class="label">Categoría Yonige-ya</div>
        <h3>“Cambiar de entorno cuando es necesario”</h3>
        <ul>
          <li>Servicio especializado de salida / mudanza.</li>
          <li>Prioriza organización, discreción y respuesta a situaciones especiales.</li>
          <li>Puede incluir orientación y coordinación profesional.</li>
        </ul>
      </div>
    </div>

    <div style="margin-top:28px" class="card">
      <h3>Oportunidad de mercado</h3>
      <p>En Perú, “mudanza” suele percibirse como transporte de pertenencias. La oportunidad consiste en introducir una categoría más amplia: <strong>“mudanza de emergencia y discreta”</strong>, con una propuesta entendible para el consumidor local.</p>
    </div>
  </div>
</section>

<section class="section" id="entrada">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">05 · Ruta de entrada</div>
      <h2>¿Cómo entraría la categoría al mercado peruano?</h2>
      <p>La lógica recomendada es educar primero, generar identificación después y convertir al final.</p>
    </div>
    <div class="process">
      <div class="step"><div class="num">1</div><h3>Descubrimiento</h3><p>“¿Qué es un Yonige-ya?”</p></div>
      <div class="step"><div class="num">2</div><h3>Educación</h3><p>“Una mudanza normal no siempre es suficiente.”</p></div>
      <div class="step"><div class="num">3</div><h3>Identificación</h3><p>“¿Alguna vez has necesitado empezar de nuevo?”</p></div>
      <div class="step"><div class="num">4</div><h3>Confianza</h3><p>“Así funciona el servicio.”</p></div>
      <div class="step"><div class="num">5</div><h3>Conversión</h3><p>“Consulta / conoce la solución.”</p></div>
    </div>
  </div>
</section>

<section class="section alt" id="estrategias">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">06 · Contenido</div>
      <h2>Las 4 estrategias y sus piezas</h2>
      <p>La campaña inicial combina educación, entretenimiento, inspiración y promoción para construir la categoría paso a paso.</p>
    </div>

    <div class="strategy-grid">
      <article class="strategy">
        <div class="strategy-top">
          <div><div class="tag">Estrategia 01</div><h3>Educativa</h3></div><div class="icon">📚</div>
        </div>
        <div class="strategy-body">
          <div class="meta">
            <div class="meta-card"><b>Objetivo</b><span>Introducir y explicar la categoría.</span></div>
            <div class="meta-card"><b>Formato</b><span>TikTok / Instagram Reel · 30–45 s</span></div>
          </div>
          <p><strong>Pieza: “¿Qué es un Yonige-ya?”</strong></p>
          <p>Video corto que presenta el concepto japonés y explica que se trata de una solución de mudanza / salida para situaciones especiales, no de un reto viral.</p>
          <div class="copy"><p>“¿Sabías que en Japón existe un tipo de empresa que ayuda a personas a realizar mudanzas en situaciones especiales? Se llaman Yonige-ya. No es desaparecer. Es poder cambiar de entorno cuando realmente lo necesitas.”</p></div>
          <a class="cta" href="#fuentes">Ver fuentes →</a>
        </div>
      </article>

      <article class="strategy">
        <div class="strategy-top">
          <div><div class="tag">Estrategia 02</div><h3>Entretenimiento</h3></div><div class="icon">🎯</div>
        </div>
        <div class="strategy-body">
          <div class="meta">
            <div class="meta-card"><b>Objetivo</b><span>Generar interacción y curiosidad.</span></div>
            <div class="meta-card"><b>Formato</b><span>TikTok / Reel interactivo</span></div>
          </div>
          <p><strong>Pieza: “¿Te mudarías en 24 horas?”</strong></p>
          <p>Una dinámica de elección rápida: solo puedes llevar cinco cosas. La interacción desemboca en una reflexión sobre la diferencia entre un juego y una necesidad real.</p>
          <div class="copy"><p>“Imagínate que mañana tienes que dejar tu casa. Tienes 24 horas. Solo puedes llevar 5 cosas. ¿Cuáles eliges? Para algunos es un juego; para otros, mudarse rápidamente es una necesidad real.”</p></div>
          <a class="cta" href="#fuentes">Ver contexto →</a>
        </div>
      </article>

      <article class="strategy">
        <div class="strategy-top">
          <div><div class="tag">Estrategia 03</div><h3>Inspiracional</h3></div><div class="icon">✨</div>
        </div>
        <div class="strategy-body">
          <div class="meta">
            <div class="meta-card"><b>Objetivo</b><span>Conectar emocionalmente con el público.</span></div>
            <div class="meta-card"><b>Formato</b><span>Reel emocional · 45–60 s</span></div>
          </div>
          <p><strong>Pieza: “Empezar de nuevo también es avanzar.”</strong></p>
          <p>Una historia breve muestra a una persona que deja su antigua vivienda y llega a un nuevo espacio. El foco está en la transformación y la posibilidad de una nueva etapa.</p>
          <div class="copy"><p>“Hay momentos en los que cambiar de lugar no significa escapar. Significa elegir una nueva etapa. Dejar atrás un lugar, organizar tus cosas, cerrar una etapa y comenzar otra.”</p></div>
          <a class="cta" href="#fuentes">Ver referencias →</a>
        </div>
      </article>

      <article class="strategy">
        <div class="strategy-top">
          <div><div class="tag">Estrategia 04</div><h3>Promocional</h3></div><div class="icon">📣</div>
        </div>
        <div class="strategy-body">
          <div class="meta">
            <div class="meta-card"><b>Objetivo</b><span>Presentar la marca y convertir interés.</span></div>
            <div class="meta-card"><b>Formato</b><span>Video de lanzamiento</span></div>
          </div>
          <p><strong>Pieza: “Una nueva forma de mudarte.”</strong></p>
          <p>Video que muestra planificación, embalaje, traslado y nuevo espacio, y presenta la categoría como una alternativa profesional para situaciones especiales.</p>
          <div class="copy"><p>“En Japón existe una categoría especializada en mudanzas para situaciones especiales. Ahora queremos llevar esa experiencia al Perú. Una mudanza diferente necesita una solución diferente.”</p></div>
          <a class="cta" href="#fuentes">Ver contexto →</a>
        </div>
      </article>
    </div>
  </div>
</section>

<section class="section" id="concepto">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">07 · Concepto creativo</div>
      <h2>Una idea paraguas para toda la campaña</h2>
      <p>La comunicación evita apropiarse del lenguaje de “desaparecer” como promesa de servicio y lo reconduce hacia el problema real que la categoría busca resolver.</p>
    </div>
    <div class="final-callout">
      <div>
        <h3>“No se trata de desaparecer.<br>Se trata de empezar de nuevo.”</h3>
        <p>Conecta la conversación peruana con el concepto Yonige-ya y permite construir una propuesta de valor local basada en rapidez, discreción, organización y cambio de entorno.</p>
      </div>
      <div class="final-badge">
        <div class="jp2">夜逃げ屋</div>
        <div style="margin-top:8px;font-weight:850">De Japón → Perú</div>
      </div>
    </div>
  </div>
</section>

<section class="section alt" id="fuentes">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">08 · Fuentes verificadas</div>
      <h2>Referencias utilizadas</h2>
      <p>La investigación combina diccionarios japoneses, sitios de operadores Yonige-ya y cobertura reciente en Perú. Los enlaces se mantienen para facilitar la revisión académica.</p>
    </div>
    <div class="sources">
      <div class="source">
        <div class="source-badge">01</div>
        <div><a href="https://kotobank.jp/word/%E5%A4%9C%E9%80%83%E3%81%92-654704" target="_blank" rel="noopener">Kotobank — 夜逃げ (Yonige)</a><p>Definición japonesa de 夜逃げ como partida o escape discreto durante la noche.</p></div>
      </div>
      <div class="source">
        <div class="source-badge">02</div>
        <div><a href="https://kotobank.jp/word/%E5%A4%9C%E9%80%83%E3%81%92%E5%B1%8B-654705" target="_blank" rel="noopener">Kotobank — 夜逃げ屋 (Yonige-ya)</a><p>Define el término y menciona su uso en situaciones como deudas, violencia y stalking.</p></div>
      </div>
      <div class="source">
        <div class="source-badge">03</div>
        <div><a href="https://www.soudan24.info/detaileria.html" target="_blank" rel="noopener">Yonige-ya TSC — servicios y áreas de atención</a><p>Describe mudanzas urgentes, DV, stalking, divorcio, vivienda, apoyo y coordinación con profesionales.</p></div>
      </div>
      <div class="source">
        <div class="source-badge">04</div>
        <div><a href="https://www.soudan24.info/yonigeya1.html" target="_blank" rel="noopener">Yonige-ya TSC —相談・支援 / consulta y apoyo</a><p>Detalla相談, mudanza, apoyo de emergencia y la advertencia de que la salida nocturna no siempre es la mejor solución.</p></div>
      </div>
      <div class="source">
        <div class="source-badge">05</div>
        <div><a href="https://www.infobae.com/peru/2026/09/29/el-reto-de-las-48-horas-la-peligrosa-tendencia-viral-que-impulsa-a-adolescentes-a-desaparecer-de-sus-casas/" target="_blank" rel="noopener">Infobae Perú — Reto de las 48 horas</a><p>Reportaje de septiembre de 2026 sobre el reto viral y su impacto en familias y menores.</p></div>
      </div>
      <div class="source">
        <div class="source-badge">06</div>
        <div><a href="https://latinanoticias.pe/peru/alerta-por-peligroso-reto-viral-de-jovenes-que-se-desaparecen-por-48-horas-video_20260926/" target="_blank" rel="noopener">Latina Noticias — alerta por el reto de las 48 horas</a><p>Cobertura peruana del 26 de septiembre de 2026 sobre la circulación del desafío.</p></div>
      </div>
    </div>

    <div class="card" style="margin-top:24px">
      <h3>Nota metodológica</h3>
      <p>Las afirmaciones sobre el significado de “Yonige-ya” y los servicios de empresas japonesas están basadas en fuentes enlazadas. La aplicación al mercado peruano —incluidos insight, concepto creativo y piezas— es una propuesta estratégica elaborada a partir de ese contexto y no una afirmación de que exista actualmente una categoría regulada o consolidada de “Yonige-ya” en Perú.</p>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <div class="footer-line"></div>
    <div>Proyecto de investigación y estrategia de contenido · Yonige-ya · Mercado peruano · 2026</div>
    <div style="margin-top:5px">Documento conceptual para fines de marketing y presentación.</div>
  </div>
</footer>

</body>
</html>
