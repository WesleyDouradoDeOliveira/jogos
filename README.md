
<style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Barlow:wght@400;500;600;700&display=swap');
*{box-sizing:border-box;margin:0;padding:0;}
.lp{font-family:'Barlow',sans-serif;background:#0a0a0f;color:#fff;width:100%;max-width:420px;margin:0 auto;overflow-x:hidden;}

.hero{padding:32px 18px 28px;position:relative;overflow:hidden;}
.glow1{position:absolute;top:-80px;right:-80px;width:240px;height:240px;background:rgba(0,200,80,0.06);border-radius:50%;pointer-events:none;}
.glow2{position:absolute;bottom:-60px;left:-60px;width:200px;height:200px;background:rgba(80,40,200,0.05);border-radius:50%;pointer-events:none;}

.badge{display:inline-flex;align-items:center;gap:6px;background:rgba(0,200,80,0.1);border:1px solid rgba(0,200,80,0.25);color:#00c850;font-size:10px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;padding:5px 12px;border-radius:20px;margin-bottom:16px;}
.dot{width:6px;height:6px;background:#00c850;border-radius:50%;animation:blink 1.4s ease-in-out infinite;flex-shrink:0;}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:.25;}}

.hero-title{font-family:'Bebas Neue',sans-serif;font-size:44px;line-height:1.0;color:#fff;letter-spacing:.5px;margin-bottom:14px;}
.hero-title span{color:#00c850;}
.hero-sub{font-size:14px;color:rgba(255,255,255,0.58);line-height:1.7;margin-bottom:22px;}

.btn-main{display:block;width:100%;background:#00c850;color:#000;font-family:'Barlow',sans-serif;font-weight:700;font-size:15px;padding:16px 18px;border-radius:10px;border:none;cursor:pointer;text-align:center;margin-bottom:10px;}
.btn-sec{display:block;width:100%;background:transparent;color:rgba(255,255,255,0.6);font-family:'Barlow',sans-serif;font-weight:600;font-size:14px;padding:13px 18px;border-radius:10px;border:1px solid rgba(255,255,255,0.13);cursor:pointer;text-align:center;}

.stats{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:8px;margin-top:22px;}
.stat{background:#111119;border:1px solid rgba(255,255,255,0.07);border-radius:10px;padding:12px 8px;text-align:center;}
.stat-n{font-family:'Bebas Neue',sans-serif;font-size:20px;color:#00c850;display:block;letter-spacing:.5px;}
.stat-l{font-size:9px;color:rgba(255,255,255,0.38);text-transform:uppercase;letter-spacing:.8px;margin-top:3px;display:block;line-height:1.3;}

.proof{background:#0f0f18;border-top:1px solid rgba(255,255,255,0.06);border-bottom:1px solid rgba(255,255,255,0.06);padding:16px 18px;display:flex;flex-direction:column;gap:11px;}
.proof-item{display:flex;align-items:center;gap:10px;font-size:13px;color:rgba(255,255,255,0.52);}
.pi{color:#00c850;font-size:16px;flex-shrink:0;}

.sec{padding:32px 18px;}
.sec-tag{font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#00c850;margin-bottom:8px;}
.sec-title{font-family:'Bebas Neue',sans-serif;font-size:30px;color:#fff;line-height:1.05;margin-bottom:8px;}
.sec-title span{color:#00c850;}
.sec-desc{font-size:13px;color:rgba(255,255,255,0.48);line-height:1.65;margin-bottom:22px;}

.steps{display:flex;flex-direction:column;gap:10px;}
.step{background:#111119;border:1px solid rgba(255,255,255,0.07);border-radius:12px;padding:16px 14px;display:flex;align-items:center;gap:14px;}
.step-icon{width:42px;height:42px;min-width:42px;border-radius:10px;background:rgba(0,200,80,0.1);border:1px solid rgba(0,200,80,0.2);display:flex;align-items:center;justify-content:center;color:#00c850;font-size:20px;}
.step-body h3{font-size:14px;font-weight:700;color:#fff;margin-bottom:3px;}
.step-body p{font-size:12px;color:rgba(255,255,255,0.48);line-height:1.55;}

.benefits-sec{background:#060609;}
.benefits{display:flex;flex-direction:column;gap:9px;}
.ben{display:flex;align-items:flex-start;gap:11px;background:#0e0e16;border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 13px;}
.ben-check{width:22px;height:22px;min-width:22px;border-radius:50%;background:rgba(0,200,80,0.12);border:1px solid rgba(0,200,80,0.25);display:flex;align-items:center;justify-content:center;margin-top:1px;color:#00c850;font-size:12px;}
.ben-text strong{display:block;font-size:13px;color:#fff;margin-bottom:2px;font-weight:700;}
.ben-text p{font-size:12px;color:rgba(255,255,255,0.48);line-height:1.5;}

.social-sec{background:#0a0a0f;}
.testis{display:flex;flex-direction:column;gap:11px;}
.tcard{background:#111119;border:1px solid rgba(255,255,255,0.07);border-radius:12px;padding:16px 14px;}
.stars{color:#f5a623;font-size:12px;letter-spacing:3px;margin-bottom:9px;}
.ttext{font-size:13px;color:rgba(255,255,255,0.62);line-height:1.65;margin-bottom:13px;font-style:italic;}
.tauthor{display:flex;align-items:center;gap:10px;}
.tavatar{width:34px;height:34px;min-width:34px;border-radius:50%;background:rgba(0,200,80,0.16);display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;color:#00c850;}
.tname{font-size:13px;font-weight:600;color:#fff;}
.trole{font-size:11px;color:rgba(255,255,255,0.32);}

.cta-sec{background:#0a1a0f;padding:40px 18px 36px;text-align:center;position:relative;overflow:hidden;}
.cta-sec::before{content:'';position:absolute;inset:0;background:radial-gradient(ellipse at 50% 0%,rgba(0,200,80,0.08) 0%,transparent 65%);pointer-events:none;}
.cta-sec h2{font-family:'Bebas Neue',sans-serif;font-size:36px;color:#fff;margin-bottom:10px;line-height:1.05;position:relative;}
.cta-sec h2 span{color:#00c850;}
.cta-sec p{font-size:13px;color:rgba(255,255,255,0.48);max-width:300px;margin:0 auto 22px;line-height:1.65;position:relative;}
.urgency{margin-top:14px;font-size:11px;color:rgba(255,255,255,0.28);letter-spacing:.3px;}

.footer{background:#060608;border-top:1px solid rgba(255,255,255,0.05);padding:18px;text-align:center;}
.footer-brand{font-family:'Bebas Neue',sans-serif;font-size:20px;color:#fff;letter-spacing:1px;margin-bottom:5px;}
.footer-brand span{color:#00c850;}
.footer-legal{font-size:10px;color:rgba(255,255,255,0.18);line-height:1.6;}
</style>

<div class="lp">

  <div class="hero">
    <div class="glow1"></div>
    <div class="glow2"></div>
    <div class="badge"><span class="dot"></span> Vagas abertas agora</div>
    <div class="hero-title">Jogue onde<br>o <span>dinheiro</span><br>cai de verdade</div>
    <p class="hero-sub">Grupo exclusivo com as melhores plataformas verificadas, estratégias diárias e suporte 1:1 para você lucrar toda semana.</p>
    <button class="btn-main" onclick="sendPrompt('Quero uma LP mobile assim para meu grupo de iGaming')">Entrar no Grupo Agora →</button>
    <button class="btn-sec">Ver como funciona</button>
    <div class="stats">
      <div class="stat"><span class="stat-n">4.8K+</span><span class="stat-l">Membros ativos</span></div>
      <div class="stat"><span class="stat-n">R$2,3M</span><span class="stat-l">Pagos aos membros</span></div>
      <div class="stat"><span class="stat-n">97%</span><span class="stat-l">Taxa de aprovação</span></div>
    </div>
  </div>

  <div class="proof">
    <div class="proof-item"><i class="ti ti-shield-check pi" aria-hidden="true"></i> Plataformas verificadas e testadas</div>
    <div class="proof-item"><i class="ti ti-clock pi" aria-hidden="true"></i> Saque confirmado em até 10 minutos</div>
    <div class="proof-item"><i class="ti ti-bolt pi" aria-hidden="true"></i> Estratégias novas todo dia no grupo</div>
    <div class="proof-item"><i class="ti ti-lock pi" aria-hidden="true"></i> Acesso 100% privado e exclusivo</div>
  </div>

  <div class="sec">
    <p class="sec-tag">Como funciona</p>
    <h2 class="sec-title">4 passos para<br><span>começar a lucrar</span></h2>
    <p class="sec-desc">Sem enrolação. Entra, aplica e já vê resultado na primeira semana.</p>
    <div class="steps">
      <div class="step">
        <div class="step-icon"><i class="ti ti-user-plus" aria-hidden="true"></i></div>
        <div class="step-body"><h3>Entre no grupo</h3><p>Acesso imediato após confirmação. Sem espera.</p></div>
      </div>
      <div class="step">
        <div class="step-icon"><i class="ti ti-device-mobile" aria-hidden="true"></i></div>
        <div class="step-body"><h3>Receba as plataformas</h3><p>Todo dia envio análise de odds e a estratégia do dia.</p></div>
      </div>
      <div class="step">
        <div class="step-icon"><i class="ti ti-cash" aria-hidden="true"></i></div>
        <div class="step-body"><h3>Saque seus ganhos</h3><p>Plataformas que pagam rápido, sem burocracia nenhuma.</p></div>
      </div>
      <div class="step">
        <div class="step-icon"><i class="ti ti-trending-up" aria-hidden="true"></i></div>
        <div class="step-body"><h3>Escale os resultados</h3><p>Com suporte 1:1 você aumenta os ganhos progressivamente.</p></div>
      </div>
    </div>
  </div>

  <div class="sec benefits-sec">
    <p class="sec-tag">O que você recebe</p>
    <h2 class="sec-title">Tudo em<br><span>um lugar só</span></h2>
    <p class="sec-desc" style="margin-bottom:20px;">Acesso completo ao ecossistema de quem já está lucrando.</p>
    <div class="benefits">
      <div class="ben"><div class="ben-check"><i class="ti ti-check" aria-hidden="true"></i></div><div class="ben-text"><strong>Plataformas verificadas todo dia</strong><p>Só indico o que eu mesmo testei e confirmei o pagamento.</p></div></div>
      <div class="ben"><div class="ben-check"><i class="ti ti-check" aria-hidden="true"></i></div><div class="ben-text"><strong>Estratégias exclusivas</strong><p>Métodos com anos de experiência no mercado de iGaming.</p></div></div>
      <div class="ben"><div class="ben-check"><i class="ti ti-check" aria-hidden="true"></i></div><div class="ben-text"><strong>Alertas em tempo real</strong><p>Notificação imediata quando surge uma oportunidade quente.</p></div></div>
      <div class="ben"><div class="ben-check"><i class="ti ti-check" aria-hidden="true"></i></div><div class="ben-text"><strong>Suporte direto comigo</strong><p>Pode me chamar a qualquer hora para tirar dúvida.</p></div></div>
      <div class="ben"><div class="ben-check"><i class="ti ti-check" aria-hidden="true"></i></div><div class="ben-text"><strong>Comunidade de 4.800 membros</strong><p>Pessoas reais compartilhando resultados todo dia.</p></div></div>
      <div class="ben"><div class="ben-check"><i class="ti ti-check" aria-hidden="true"></i></div><div class="ben-text"><strong>Bônus de boas-vindas</strong><p>Guia completo exclusivo para quem entra agora.</p></div></div>
    </div>
  </div>

  <div class="sec social-sec">
    <p class="sec-tag">Resultados reais</p>
    <h2 class="sec-title">Quem entrou<br><span>já está lucrando</span></h2>
    <p class="sec-desc" style="margin-bottom:20px;">Depoimentos de membros reais do grupo.</p>
    <div class="testis">
      <div class="tcard">
        <div class="stars">★★★★★</div>
        <p class="ttext">"Na primeira semana já recuperei o valor do grupo. As plataformas indicadas pagam de verdade e o saque cai rapidíssimo."</p>
        <div class="tauthor"><div class="tavatar">MR</div><div><div class="tname">Marcos R.</div><div class="trole">Membro há 3 meses</div></div></div>
      </div>
      <div class="tcard">
        <div class="stars">★★★★★</div>
        <p class="ttext">"Já fui enganado por vários grupos. Esse é diferente. Primeiro saque em menos de 15 minutos. Suporte incrível."</p>
        <div class="tauthor"><div class="tavatar">JP</div><div><div class="tname">João P.</div><div class="trole">Membro há 5 meses</div></div></div>
      </div>
      <div class="tcard">
        <div class="stars">★★★★★</div>
        <p class="ttext">"Eram 23h quando entrei, tentei uma estratégia e saquei R$380 ainda naquela noite. Mudou minha vida financeira."</p>
        <div class="tauthor"><div class="tavatar">AL</div><div><div class="tname">Ana L.</div><div class="trole">Membro há 2 meses</div></div></div>
      </div>
    </div>
  </div>

  <div class="cta-sec">
    <h2>Sua vez de<br><span>lucrar de verdade</span></h2>
    <p>As vagas são limitadas para manter a qualidade. Garanta a sua antes que feche.</p>
    <button class="btn-main" style="max-width:360px;margin:0 auto;" onclick="sendPrompt('Quero uma LP mobile assim para meu grupo de iGaming')">Quero Entrar Agora →</button>
    <p class="urgency">⏳ Restam apenas 12 vagas esta semana</p>
  </div>

  <div class="footer">
    <div class="footer-brand">GRUPO<span>WIN</span></div>
    <p class="footer-legal">© 2025 · Resultados podem variar · Jogue com responsabilidade · +18</p>
  </div>

</div>
