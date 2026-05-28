[index.html](https://github.com/user-attachments/files/28355657/index.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Jansen Sandes · Sandes Comunicação Integrada</title>
<meta name="description" content="Cartão de visitas digital de Jansen Sandes — 25+ anos de assessoria de imprensa em Salvador, Bahia." />
<meta name="theme-color" content="#0F2545" />
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Inter:wght@300;400;500;600;700;800&family=Playfair+Display:wght@500;700;900&display=swap" rel="stylesheet" />
<style>
  :root {
    --navy: #0F2545; --navy-deep: #081428; --navy-soft: #1A3360;
    --ivory: #FAF5EC; --ivory-warm: #F3EEDF;
    --terracotta: #B85C38; --terracotta-deep: #8E4327; --terracotta-light: #D67A52;
    --charcoal: #111111; --gray: #6B7280; --gray-soft: #9CA3AF;
    --line: rgba(15,37,69,0.10);
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  html, body { background: var(--ivory); color: var(--charcoal); font-family: 'Inter', sans-serif; -webkit-font-smoothing: antialiased; line-height: 1.5; min-height: 100vh; }
  body { background: radial-gradient(circle at 15% 8%, rgba(184,92,56,0.08) 0%, transparent 38%), radial-gradient(circle at 90% 92%, rgba(15,37,69,0.06) 0%, transparent 48%), var(--ivory); background-attachment: fixed; position: relative; overflow-x: hidden; }
  body::before { content: ''; position: fixed; top: -120px; left: -120px; width: 280px; height: 280px; background: linear-gradient(135deg, transparent 48%, var(--navy) 48%, var(--navy-soft) 52%, transparent 52%); pointer-events: none; z-index: 0; opacity: 0.18; }
  body::after { content: ''; position: fixed; bottom: -120px; right: -120px; width: 240px; height: 240px; background: linear-gradient(135deg, transparent 48%, var(--terracotta) 48%, var(--terracotta-light) 52%, transparent 52%); pointer-events: none; z-index: 0; opacity: 0.16; }
  .container { max-width: 480px; margin: 0 auto; padding: 32px 24px 56px; min-height: 100vh; display: flex; flex-direction: column; position: relative; z-index: 1; }
  .brand-strip { text-align: center; margin-bottom: 8px; }
  .brand-wordmark { font-family: 'Playfair Display', serif; font-weight: 900; font-size: 22px; letter-spacing: 0.06em; color: var(--navy); }
  .brand-tagline { font-size: 9px; text-transform: uppercase; letter-spacing: 0.32em; color: var(--gray); font-weight: 600; margin-top: 4px; }
  .display-title { font-family: 'Anton', sans-serif; font-size: clamp(64px, 18vw, 96px); line-height: 0.92; text-align: center; margin: 28px 0 8px; letter-spacing: 0.04em; text-transform: uppercase; color: var(--navy); text-shadow: 0 2px 0 rgba(15,37,69,0.06), 0 8px 16px rgba(15,37,69,0.18); }
  .display-title::after { content: ''; display: block; width: 64px; height: 4px; background: var(--terracotta); margin: 12px auto 0; border-radius: 2px; }
  .display-sub { text-align: center; font-size: 11px; text-transform: uppercase; letter-spacing: 0.32em; color: var(--terracotta); font-weight: 700; margin-bottom: 28px; }
  .photo-card { position: relative; width: 100%; aspect-ratio: 3/4; max-height: 380px; border-radius: 14px; overflow: hidden; background: linear-gradient(180deg, var(--navy-soft) 0%, var(--navy) 50%, var(--navy-deep) 100%); margin-bottom: 24px; box-shadow: 0 0 0 1px rgba(15,37,69,0.25), 0 30px 50px -20px rgba(15,37,69,0.45); display: flex; align-items: center; justify-content: center; }
  .photo-card::before { content: ''; position: absolute; inset: 0; background: linear-gradient(180deg, transparent 55%, rgba(8,20,40,0.85) 100%); z-index: 2; }
  .photo-card::after { content: ''; position: absolute; top: 16px; right: 16px; width: 40px; height: 40px; border-top: 2px solid var(--terracotta); border-right: 2px solid var(--terracotta); opacity: 0.7; z-index: 3; }
  .photo-card-initials { font-family: 'Playfair Display', serif; font-weight: 700; font-size: 120px; color: var(--ivory); line-height: 1; z-index: 1; text-shadow: 0 8px 24px rgba(0,0,0,0.5); opacity: 0.95; }
  .photo-card-caption { position: absolute; bottom: 20px; left: 20px; right: 20px; z-index: 3; color: var(--ivory); }
  .photo-card-name { font-family: 'Anton', sans-serif; font-size: 32px; letter-spacing: 0.02em; text-transform: uppercase; line-height: 1; margin-bottom: 4px; color: var(--ivory); }
  .photo-card-role { font-size: 11px; text-transform: uppercase; letter-spacing: 0.22em; color: var(--terracotta-light); font-weight: 600; }
  .pitch { text-align: center; font-size: 15px; color: var(--charcoal); line-height: 1.65; max-width: 380px; margin: 0 auto 32px; }
  .pitch strong { color: var(--navy); font-weight: 700; }
  .ornament { display: flex; align-items: center; justify-content: center; margin: 8px 0 20px; gap: 14px; }
  .ornament-line { flex: 1; height: 1px; background: linear-gradient(to right, transparent, var(--navy), transparent); max-width: 90px; opacity: 0.3; }
  .ornament-diamond { width: 8px; height: 8px; background: var(--terracotta); transform: rotate(45deg); }
  .section-label { text-align: center; font-size: 10px; text-transform: uppercase; letter-spacing: 0.32em; color: var(--gray); font-weight: 700; margin-bottom: 16px; }
  .cta-badge { position: relative; display: flex; align-items: center; justify-content: center; gap: 14px; background: var(--navy); color: var(--ivory); padding: 20px 24px; border-radius: 14px; text-decoration: none; font-weight: 700; font-size: 16px; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 14px; transition: all 0.25s; box-shadow: inset 0 1px 0 rgba(255,255,255,0.08), 0 12px 30px -12px rgba(15,37,69,0.55); border: 1px solid var(--navy-deep); }
  .cta-badge::before { content: ''; position: absolute; inset: 6px; border: 1px solid rgba(184,92,56,0.35); border-radius: 9px; pointer-events: none; }
  .cta-badge:hover { background: var(--navy-deep); transform: translateY(-2px); }
  .cta-badge svg { width: 24px; height: 24px; fill: var(--ivory); flex-shrink: 0; }
  .action-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 28px; }
  .action { display: flex; align-items: center; justify-content: center; gap: 10px; background: transparent; color: var(--navy); padding: 14px 12px; border-radius: 12px; text-decoration: none; font-weight: 600; font-size: 13px; text-transform: uppercase; letter-spacing: 0.08em; transition: all 0.2s; border: 1.5px solid rgba(15,37,69,0.2); }
  .action:hover { background: var(--ivory-warm); border-color: var(--navy); transform: translateY(-2px); }
  .action svg { width: 16px; height: 16px; fill: var(--navy); flex-shrink: 0; }
  .social-list { display: flex; flex-direction: column; gap: 8px; margin-bottom: 28px; }
  .social-link { display: flex; align-items: center; gap: 14px; padding: 14px 16px; background: rgba(255,255,255,0.6); border: 1px solid var(--line); border-radius: 12px; text-decoration: none; color: var(--charcoal); transition: all 0.2s; }
  .social-link:hover { background: var(--ivory-warm); border-color: var(--navy); transform: translateX(2px); }
  .social-icon { width: 40px; height: 40px; border-radius: 10px; background: var(--navy); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .social-icon svg { width: 20px; height: 20px; fill: var(--ivory); }
  .social-meta { flex: 1; min-width: 0; }
  .social-label { font-size: 10px; text-transform: uppercase; letter-spacing: 0.18em; color: var(--gray); font-weight: 700; margin-bottom: 2px; }
  .social-handle { font-size: 15px; font-weight: 600; color: var(--navy); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .social-arrow { width: 18px; height: 18px; fill: var(--terracotta); flex-shrink: 0; }
  .save-contact { display: flex; align-items: center; justify-content: center; gap: 10px; background: var(--terracotta); color: var(--ivory); padding: 16px 24px; border-radius: 14px; font-weight: 700; font-size: 14px; text-transform: uppercase; letter-spacing: 0.12em; border: none; cursor: pointer; width: 100%; transition: all 0.25s; box-shadow: 0 10px 28px -10px rgba(184,92,56,0.55); font-family: inherit; }
  .save-contact:hover { background: var(--terracotta-deep); transform: translateY(-2px); }
  .save-contact svg { width: 18px; height: 18px; fill: var(--ivory); }
  .footer { margin-top: auto; padding-top: 40px; text-align: center; font-size: 11px; color: var(--gray-soft); letter-spacing: 0.06em; }
  .footer .promise { font-family: 'Playfair Display', serif; font-style: italic; font-size: 14px; color: var(--gray); margin-bottom: 12px; letter-spacing: 0; }
  .footer .location { text-transform: uppercase; letter-spacing: 0.22em; font-weight: 600; }
  .toast { position: fixed; bottom: 24px; left: 50%; transform: translateX(-50%) translateY(120%); background: var(--navy); color: var(--ivory); padding: 12px 20px; border-radius: 10px; font-size: 12px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.1em; transition: transform 0.3s; z-index: 100; pointer-events: none; }
  .toast.show { transform: translateX(-50%) translateY(0); }
</style>
</head>
<body>
  <div class="container">
    <header class="brand-strip">
      <div class="brand-wordmark">SANDES</div>
      <div class="brand-tagline">Comunicação Integrada</div>
    </header>

    <h1 class="display-title">CONTATO</h1>
    <div class="display-sub">Jansen Sandes · Press Office</div>

    <div class="photo-card" role="img" aria-label="Jansen Sandes">
      <div class="photo-card-initials">JS</div>
      <div class="photo-card-caption">
        <div class="photo-card-name">Jansen Sandes</div>
        <div class="photo-card-role">Jornalista · Assessor de Imprensa</div>
      </div>
    </div>

    <p class="pitch">
      <strong>25+ anos</strong> de redação e bastidor, trabalhando com artistas da Bahia e do Brasil. Relacionamento sólido com as redações baianas. Pauta personalizada. Imprensa certa.
    </p>

    <div class="ornament" aria-hidden="true">
      <div class="ornament-line"></div>
      <div class="ornament-diamond"></div>
      <div class="ornament-line"></div>
    </div>
    <div class="section-label">Fale comigo agora</div>

    <a class="cta-badge" href="https://wa.me/5571999852742?text=Ol%C3%A1%2C%20Jansen!%20Vim%20pelo%20seu%20cart%C3%A3o%20digital%20e%20gostaria%20de%20conversar%20sobre%20assessoria%20de%20imprensa." target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M17.5 14.4c-.3-.1-1.7-.8-2-.9-.3-.1-.5-.1-.7.1-.2.3-.8.9-.9 1.1-.2.2-.3.2-.6.1-.3-.1-1.2-.4-2.3-1.4-.9-.8-1.4-1.7-1.6-2-.2-.3 0-.5.1-.6.1-.1.3-.3.4-.5.1-.2.2-.3.3-.5.1-.2 0-.4 0-.5 0-.1-.7-1.6-.9-2.2-.2-.6-.5-.5-.7-.5h-.6c-.2 0-.5.1-.8.4-.3.3-1.1 1-1.1 2.5 0 1.5 1.1 2.9 1.2 3.1.2.2 2.2 3.3 5.3 4.6.7.3 1.3.5 1.7.6.7.2 1.4.2 1.9.1.6-.1 1.7-.7 1.9-1.4.2-.7.2-1.2.2-1.4-.1-.1-.3-.2-.6-.3M12 2C6.5 2 2 6.5 2 12c0 1.8.5 3.5 1.3 5L2 22l5.1-1.3c1.5.8 3.1 1.2 4.9 1.2 5.5 0 10-4.5 10-10S17.5 2 12 2"/></svg>
      Conversar no WhatsApp
    </a>

    <div class="action-grid">
      <a class="action" href="tel:+5571999852742" aria-label="Ligar">
        <svg viewBox="0 0 24 24"><path d="M6.6 10.8c1.4 2.8 3.7 5.1 6.5 6.5l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.5.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1H7c.6 0 1 .4 1 1 0 1.2.2 2.4.6 3.5.1.3.1.7-.2 1l-2.8 2.3z"/></svg>
        Ligar
      </a>
      <a class="action" href="mailto:Jansensandes@gmail.com?subject=Contato%20via%20cart%C3%A3o%20digital">
        <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg>
        E-mail
      </a>
    </div>

    <div class="section-label">Onde me encontrar</div>
    <div class="social-list">
      <a class="social-link" href="https://instagram.com/sandescomunica" target="_blank" rel="noopener">
        <div class="social-icon"><svg viewBox="0 0 24 24"><path d="M12 2.2c3.2 0 3.6 0 4.8.1 1.2.1 1.8.2 2.2.4.6.2 1 .5 1.4.9.4.4.7.9.9 1.4.2.4.4 1 .4 2.2.1 1.2.1 1.6.1 4.8s0 3.6-.1 4.8c-.1 1.2-.2 1.8-.4 2.2-.2.6-.5 1-.9 1.4-.4.4-.9.7-1.4.9-.4.2-1 .4-2.2.4-1.2.1-1.6.1-4.8.1s-3.6 0-4.8-.1c-1.2-.1-1.8-.2-2.2-.4-.6-.2-1-.5-1.4-.9-.4-.4-.7-.9-.9-1.4-.2-.4-.4-1-.4-2.2C2.2 15.6 2.2 15.2 2.2 12s0-3.6.1-4.8c.1-1.2.2-1.8.4-2.2.2-.6.5-1 .9-1.4.4-.4.9-.7 1.4-.9.4-.2 1-.4 2.2-.4C8.4 2.2 8.8 2.2 12 2.2M12 0C8.7 0 8.3 0 7.1.1 5.8.1 5 .3 4.2.6c-.8.3-1.5.8-2.2 1.4C1.4 2.7.9 3.4.6 4.2.3 5 .1 5.8.1 7.1 0 8.3 0 8.7 0 12s0 3.7.1 4.9c.1 1.3.3 2.1.6 2.9.3.8.8 1.5 1.4 2.2.7.7 1.4 1.1 2.2 1.4.8.3 1.6.5 2.9.6 1.2.1 1.6.1 4.9.1s3.7 0 4.9-.1c1.3-.1 2.1-.3 2.9-.6.8-.3 1.5-.8 2.2-1.4.7-.7 1.1-1.4 1.4-2.2.3-.8.5-1.6.6-2.9.1-1.2.1-1.6.1-4.9s0-3.7-.1-4.9c-.1-1.3-.3-2.1-.6-2.9-.3-.8-.8-1.5-1.4-2.2C21.3 1.4 20.6.9 19.8.6 19 .3 18.2.1 16.9.1 15.7 0 15.3 0 12 0z"/><path d="M12 5.8c-3.4 0-6.2 2.8-6.2 6.2s2.8 6.2 6.2 6.2 6.2-2.8 6.2-6.2-2.8-6.2-6.2-6.2zm0 10.2c-2.2 0-4-1.8-4-4s1.8-4 4-4 4 1.8 4 4-1.8 4-4 4zM18.4 4.2c-.8 0-1.5.7-1.5 1.5s.7 1.5 1.5 1.5 1.5-.7 1.5-1.5-.7-1.5-1.5-1.5z"/></svg></div>
        <div class="social-meta"><div class="social-label">Instagram · Sandes</div><div class="social-handle">@sandescomunica</div></div>
        <svg class="social-arrow" viewBox="0 0 24 24"><path d="M8.6 16.6 13.2 12 8.6 7.4 10 6l6 6-6 6z"/></svg>
      </a>
      <a class="social-link" href="https://instagram.com/Jansensandes" target="_blank" rel="noopener">
        <div class="social-icon"><svg viewBox="0 0 24 24"><path d="M12 2.2c3.2 0 3.6 0 4.8.1 1.2.1 1.8.2 2.2.4.6.2 1 .5 1.4.9.4.4.7.9.9 1.4.2.4.4 1 .4 2.2.1 1.2.1 1.6.1 4.8s0 3.6-.1 4.8c-.1 1.2-.2 1.8-.4 2.2-.2.6-.5 1-.9 1.4-.4.4-.9.7-1.4.9-.4.2-1 .4-2.2.4-1.2.1-1.6.1-4.8.1s-3.6 0-4.8-.1c-1.2-.1-1.8-.2-2.2-.4-.6-.2-1-.5-1.4-.9-.4-.4-.7-.9-.9-1.4-.2-.4-.4-1-.4-2.2C2.2 15.6 2.2 15.2 2.2 12s0-3.6.1-4.8c.1-1.2.2-1.8.4-2.2.2-.6.5-1 .9-1.4.4-.4.9-.7 1.4-.9.4-.2 1-.4 2.2-.4C8.4 2.2 8.8 2.2 12 2.2M12 0C8.7 0 8.3 0 7.1.1 5.8.1 5 .3 4.2.6c-.8.3-1.5.8-2.2 1.4C1.4 2.7.9 3.4.6 4.2.3 5 .1 5.8.1 7.1 0 8.3 0 8.7 0 12s0 3.7.1 4.9c.1 1.3.3 2.1.6 2.9.3.8.8 1.5 1.4 2.2.7.7 1.4 1.1 2.2 1.4.8.3 1.6.5 2.9.6 1.2.1 1.6.1 4.9.1s3.7 0 4.9-.1c1.3-.1 2.1-.3 2.9-.6.8-.3 1.5-.8 2.2-1.4.7-.7 1.1-1.4 1.4-2.2.3-.8.5-1.6.6-2.9.1-1.2.1-1.6.1-4.9s0-3.7-.1-4.9c-.1-1.3-.3-2.1-.6-2.9-.3-.8-.8-1.5-1.4-2.2C21.3 1.4 20.6.9 19.8.6 19 .3 18.2.1 16.9.1 15.7 0 15.3 0 12 0z"/><path d="M12 5.8c-3.4 0-6.2 2.8-6.2 6.2s2.8 6.2 6.2 6.2 6.2-2.8 6.2-6.2-2.8-6.2-6.2-6.2zm0 10.2c-2.2 0-4-1.8-4-4s1.8-4 4-4 4 1.8 4 4-1.8 4-4 4zM18.4 4.2c-.8 0-1.5.7-1.5 1.5s.7 1.5 1.5 1.5 1.5-.7 1.5-1.5-.7-1.5-1.5-1.5z"/></svg></div>
        <div class="social-meta"><div class="social-label">Instagram · Pessoal</div><div class="social-handle">@Jansensandes</div></div>
        <svg class="social-arrow" viewBox="0 0 24 24"><path d="M8.6 16.6 13.2 12 8.6 7.4 10 6l6 6-6 6z"/></svg>
      </a>
      <a class="social-link" href="https://www.linkedin.com/in/jansen-sandes-928624277?utm_source=share_via&utm_content=profile&utm_medium=member_ios" target="_blank" rel="noopener">
        <div class="social-icon"><svg viewBox="0 0 24 24"><path d="M20.5 2h-17A1.5 1.5 0 0 0 2 3.5v17A1.5 1.5 0 0 0 3.5 22h17a1.5 1.5 0 0 0 1.5-1.5v-17A1.5 1.5 0 0 0 20.5 2zM8 19H5v-9h3zM6.5 8.25A1.75 1.75 0 1 1 8.3 6.5a1.78 1.78 0 0 1-1.8 1.75zM19 19h-3v-4.74c0-1.42-.6-1.93-1.38-1.93A1.74 1.74 0 0 0 13 14.19a.66.66 0 0 0 0 .14V19h-3v-9h2.9v1.3a3.11 3.11 0 0 1 2.7-1.4c1.55 0 3.36.86 3.36 3.66z"/></svg></div>
        <div class="social-meta"><div class="social-label">LinkedIn</div><div class="social-handle">in/jansen-sandes</div></div>
        <svg class="social-arrow" viewBox="0 0 24 24"><path d="M8.6 16.6 13.2 12 8.6 7.4 10 6l6 6-6 6z"/></svg>
      </a>
    </div>

    <button class="save-contact" onclick="saveContact()" type="button">
      <svg viewBox="0 0 24 24"><path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6z"/></svg>
      Salvar contato no celular
    </button>

    <footer class="footer">
      <div class="promise">"A história certa para a imprensa certa."</div>
      <div class="location">Salvador · Bahia · Brasil</div>
    </footer>
  </div>

  <div class="toast" id="toast" role="status" aria-live="polite">Contato baixado</div>

<script>
  function saveContact() {
    const vcard = "BEGIN:VCARD\r\nVERSION:3.0\r\nN:Sandes;Jansen;;;\r\nFN:Jansen Sandes\r\nORG:Sandes Comunicacao Integrada\r\nTITLE:Jornalista - Assessor de Imprensa\r\nTEL;TYPE=CELL,VOICE:+5571999852742\r\nEMAIL;TYPE=INTERNET:Jansensandes@gmail.com\r\nURL;TYPE=WhatsApp:https://wa.me/5571999852742\r\nURL;TYPE=Instagram:https://instagram.com/Jansensandes\r\nURL;TYPE=LinkedIn:https://www.linkedin.com/in/jansen-sandes-928624277\r\nURL;TYPE=Instagram-Profissional:https://instagram.com/sandescomunica\r\nADR;TYPE=WORK:;;Salvador;BA;;;Brasil\r\nNOTE:Assessoria de imprensa - Pauta personalizada - Imprensa certa\r\nEND:VCARD\r\n";
    const blob = new Blob([vcard], { type: 'text/vcard;charset=utf-8' });
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url; a.download = 'Jansen_Sandes.vcf';
    document.body.appendChild(a); a.click(); document.body.removeChild(a);
    setTimeout(() => URL.revokeObjectURL(url), 1500);
    const t = document.getElementById('toast');
    t.classList.add('show');
    setTimeout(() => t.classList.remove('show'), 2200);
  }
</script>
</body>
</html>
