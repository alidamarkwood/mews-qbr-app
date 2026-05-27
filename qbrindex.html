<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mews QBR · Jorge</title>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@700;800;900&family=Barlow:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root {
  --pink:#FF83DA;--pink-d:#d44fb0;--pink-l:#fff0fb;--pink-m:#ffd6f5;
  --black:#0d0d0d;--white:#fff;
  --g50:#fafafa;--g100:#f4f4f5;--g150:#ebebed;--g200:#e4e4e7;
  --g300:#d1d1d6;--g400:#a0a0ab;--g500:#71717a;--g600:#52525b;
  --g700:#3f3f46;--g900:#18181b;
  --green:#16a34a;--green-l:#dcfce7;
  --red:#dc2626;--red-l:#fee2e2;
  --amber:#d97706;--amber-l:#fef3c7;
  --blue:#2563eb;--blue-l:#dbeafe;
  --r:12px;--rs:8px;--rxs:6px;
  --sh:0 1px 3px rgba(0,0,0,.07),0 1px 2px rgba(0,0,0,.04);
  --sh2:0 4px 16px rgba(0,0,0,.08);
  --sh3:0 8px 32px rgba(0,0,0,.12);
}
*{margin:0;padding:0;box-sizing:border-box}
html,body{height:100%;font-family:'Barlow',sans-serif;background:var(--g50);color:var(--g900);overflow:hidden}

/* LOADER */
#loader{position:fixed;inset:0;background:var(--white);display:flex;flex-direction:column;align-items:center;justify-content:center;z-index:9999;transition:opacity .5s}
.ld-logo{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:3rem;letter-spacing:6px;text-transform:uppercase;color:var(--black);margin-bottom:.5rem}
.ld-logo span{color:var(--pink)}
.ld-sub{font-size:.72rem;color:var(--g400);letter-spacing:2px;text-transform:uppercase;margin-bottom:2rem}
.ld-track{width:220px;height:2px;background:var(--g200);border-radius:99px;overflow:hidden}
.ld-bar{height:100%;background:linear-gradient(90deg,var(--pink),var(--pink-d));border-radius:99px;width:0;transition:width .2s ease}
.ld-lbl{font-size:.68rem;color:var(--g400);margin-top:.75rem;letter-spacing:.5px}

/* APP SHELL */
#app{display:none;height:100vh;flex-direction:column}
.topbar{height:56px;background:var(--white);border-bottom:1px solid var(--g200);padding:0 1.5rem;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;box-shadow:var(--sh)}
.tb-left{display:flex;align-items:center;gap:1.25rem}
.brand{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.3rem;letter-spacing:4px;text-transform:uppercase;color:var(--black)}
.brand em{color:var(--pink);font-style:normal}
.vdiv{width:1px;height:18px;background:var(--g200)}
.acct-pill{display:flex;align-items:center;gap:.5rem;background:var(--pink-l);border:1px solid var(--pink-m);padding:.28rem .8rem;border-radius:99px;font-size:.76rem;font-weight:600;color:var(--g700)}
.acct-dot{width:6px;height:6px;border-radius:50%;background:var(--pink);animation:blink 2s infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.3}}
.tb-right{display:flex;align-items:center;gap:.65rem}
.period-pill{background:var(--g100);border:1px solid var(--g200);padding:.28rem .8rem;border-radius:99px;font-size:.7rem;color:var(--g500);font-weight:500}
.btn-pink{background:var(--pink);color:var(--black);border:none;cursor:pointer;padding:.42rem 1rem;border-radius:99px;font-size:.74rem;font-weight:700;font-family:'Barlow',sans-serif;letter-spacing:.3px;text-transform:uppercase;transition:all .15s}
.btn-pink:hover{background:var(--pink-d);transform:translateY(-1px)}

/* LAYOUT */
.layout{display:flex;flex:1;overflow:hidden}

/* SIDEBAR */
.sidebar{width:196px;min-width:196px;background:var(--white);border-right:1px solid var(--g200);padding:1.25rem 0;display:flex;flex-direction:column;overflow-y:auto}
.nav-grp{font-size:.6rem;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--g400);padding:0 1.1rem;margin:1rem 0 .35rem}
.nav-grp:first-child{margin-top:0}
.ni{display:flex;align-items:center;gap:.6rem;padding:.55rem 1.1rem;font-size:.8rem;font-weight:500;color:var(--g500);cursor:pointer;border-left:3px solid transparent;transition:all .12s}
.ni:hover{color:var(--g900);background:var(--g50)}
.ni.active{color:var(--black);border-left-color:var(--pink);background:var(--pink-l);font-weight:700}
.ni-icon{font-size:.85rem;width:15px;text-align:center;opacity:.65}
.ni.active .ni-icon{opacity:1}

/* CONTENT */
.content{flex:1;overflow-y:auto;padding:1.5rem;scrollbar-width:thin;scrollbar-color:var(--g200) transparent}

/* SF BAR */
.sf-bar{display:flex;align-items:center;gap:.65rem;background:var(--white);border:1px solid var(--g200);border-radius:var(--r);padding:.8rem 1.1rem;margin-bottom:1.5rem;box-shadow:var(--sh)}
.sf-lbl{font-size:.68rem;font-weight:700;color:var(--g500);white-space:nowrap;text-transform:uppercase;letter-spacing:.5px}
.sf-ipt{flex:1;background:var(--g50);border:1px solid var(--g200);border-radius:var(--rxs);padding:.45rem .8rem;font-size:.8rem;color:var(--g900);font-family:'Barlow',sans-serif;outline:none;transition:border-color .15s}
.sf-ipt:focus{border-color:var(--pink)}
.data-status{font-size:.68rem;color:var(--g400);white-space:nowrap}
.data-status.live{color:var(--green);font-weight:600}

/* SECTIONS */
.sec{display:none}.sec.active{display:block}

/* SECTION HEADER */
.sec-hdr{display:flex;align-items:flex-end;justify-content:space-between;margin-bottom:1.25rem}
.sec-title{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.7rem;text-transform:uppercase;letter-spacing:1px;color:var(--black);line-height:1}
.sec-sub{font-size:.75rem;color:var(--g400);margin-top:.25rem}

/* CARDS */
.card{background:var(--white);border:1px solid var(--g200);border-radius:var(--r);padding:1.25rem;box-shadow:var(--sh);transition:box-shadow .15s}
.card:hover{box-shadow:var(--sh2)}
.c-lbl{font-size:.62rem;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--g400);margin-bottom:.45rem}
.c-val{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:2rem;color:var(--black);line-height:1}
.c-delta{font-size:.72rem;font-weight:500;margin-top:.35rem;display:flex;align-items:center;gap:.25rem}
.up{color:var(--green)}.dn{color:var(--red)}.warn{color:var(--amber)}.muted{color:var(--g400)}

/* GRIDS */
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:.85rem;margin-bottom:1.1rem}
.g3{display:grid;grid-template-columns:repeat(3,1fr);gap:.85rem;margin-bottom:1.1rem}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:1.1rem;margin-bottom:1.1rem}
.g2-3{display:grid;grid-template-columns:2fr 1fr;gap:1.1rem;margin-bottom:1.1rem}

/* PINK BAR */
.pbar{width:28px;height:3px;background:var(--pink);border-radius:99px;margin-bottom:.85rem}

/* TIERS */
.tier{display:inline-flex;align-items:center;gap:.3rem;padding:.2rem .65rem;border-radius:99px;font-size:.63rem;font-weight:700;text-transform:uppercase;letter-spacing:.5px}
.t-top{background:var(--pink-l);color:var(--pink-d);border:1px solid var(--pink-m)}
.t-strong{background:var(--blue-l);color:var(--blue);border:1px solid #bfdbfe}
.t-dev{background:var(--amber-l);color:var(--amber);border:1px solid #fde68a}
.t-grow{background:var(--red-l);color:var(--red);border:1px solid #fecaca}

/* HEALTH RING */
.ring-wrap{display:flex;align-items:center;gap:1.75rem}
.ring-box{position:relative;width:96px;height:96px;flex-shrink:0}
.ring-box svg{transform:rotate(-90deg)}
.rbg{fill:none;stroke:var(--g100);stroke-width:9}
.rfill{fill:none;stroke:var(--pink);stroke-width:9;stroke-linecap:round;stroke-dasharray:283;stroke-dashoffset:283;transition:stroke-dashoffset 1.6s cubic-bezier(.4,0,.2,1)}
.ring-ctr{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center}
.ring-n{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.4rem;color:var(--black);line-height:1}
.ring-t{font-size:.52rem;color:var(--g400);font-weight:700;text-transform:uppercase;letter-spacing:.5px}
.dim-list{flex:1;display:flex;flex-direction:column;gap:.6rem}
.dim-row{display:flex;align-items:center;gap:.6rem}
.dim-n{font-size:.7rem;color:var(--g500);width:95px;flex-shrink:0}
.dim-trk{flex:1;height:4px;background:var(--g100);border-radius:99px;overflow:hidden}
.dim-b{height:100%;border-radius:99px;transition:width 1.1s ease}
.dim-s{font-size:.7rem;color:var(--g600);width:22px;text-align:right;font-weight:600}

/* BAR CHART */
.bchart{display:flex;align-items:flex-end;gap:.35rem;height:68px}
.bcol{flex:1;display:flex;flex-direction:column;align-items:center;gap:.2rem}
.bbar{width:100%;border-radius:3px 3px 0 0;min-height:3px;transition:height .8s ease}
.bval{font-size:.58rem;color:var(--g400)}

/* PROGRESS BARS */
.prog{margin-bottom:.9rem}
.prog-hd{display:flex;justify-content:space-between;margin-bottom:.3rem}
.prog-lbl{font-size:.76rem;color:var(--g600)}
.prog-val{font-size:.76rem;font-weight:700;color:var(--g900)}
.prog-trk{height:6px;background:var(--g100);border-radius:99px;overflow:hidden}
.prog-fill{height:100%;border-radius:99px;transition:width 1.1s ease}

/* BENCH */
.bench-row{padding:.8rem 0;border-bottom:1px solid var(--g100)}
.bench-row:last-child{border-bottom:none;padding-bottom:0}
.bench-m{font-size:.78rem;font-weight:600;color:var(--g700);margin-bottom:.45rem}
.bench-lines{display:flex;flex-direction:column;gap:.28rem}
.bench-line{display:flex;align-items:center;gap:.55rem}
.bench-tag{font-size:.6rem;color:var(--g400);width:52px;flex-shrink:0;font-weight:500}
.bench-trk{flex:1;height:5px;background:var(--g100);border-radius:99px;overflow:hidden}
.bench-fill{height:100%;border-radius:99px}
.b-you{background:var(--pink)}
.b-peer{background:var(--g300)}
.b-top{background:var(--black)}
.bench-num{font-size:.7rem;font-weight:600;color:var(--g700);width:48px;text-align:right}

/* OTA CHART */
.ota-donut-wrap{display:flex;align-items:center;gap:2rem}
.ota-donut{position:relative;width:120px;height:120px;flex-shrink:0}
.ota-donut svg{transform:rotate(-90deg)}
.ota-ctr{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center}
.ota-pct{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.6rem;color:var(--black);line-height:1}
.ota-tag{font-size:.55rem;color:var(--g400);font-weight:700;text-transform:uppercase;letter-spacing:.5px}
.ota-legend{flex:1;display:flex;flex-direction:column;gap:.5rem}
.ota-row{display:flex;align-items:center;gap:.6rem}
.ota-dot{width:8px;height:8px;border-radius:2px;flex-shrink:0}
.ota-lbl{font-size:.74rem;color:var(--g600);flex:1}
.ota-val{font-size:.74rem;font-weight:700;color:var(--g900)}
.leakage-box{background:var(--amber-l);border:1px solid #fde68a;border-radius:var(--rs);padding:.85rem 1rem;margin-top:1rem}
.leak-lbl{font-size:.62rem;font-weight:700;color:var(--amber);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.3rem}
.leak-txt{font-size:.76rem;color:var(--g700);line-height:1.5}
.leak-num{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.3rem;color:var(--amber)}

/* INSIGHT BOX */
.insight{background:var(--pink-l);border:1px solid var(--pink-m);border-radius:var(--rs);padding:.8rem;margin-top:.85rem}
.ins-lbl{font-size:.6rem;font-weight:700;color:var(--pink-d);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.25rem}
.ins-txt{font-size:.73rem;color:var(--g700);line-height:1.55}

/* ACTION ITEMS */
.act-row{display:flex;align-items:flex-start;gap:.85rem;padding:.85rem 0;border-bottom:1px solid var(--g100)}
.act-row:last-child{border-bottom:none;padding-bottom:0}
.act-chk{width:20px;height:20px;border-radius:50%;border:2px solid var(--g300);flex-shrink:0;margin-top:1px;display:flex;align-items:center;justify-content:center;font-size:.62rem;cursor:pointer;transition:all .2s}
.act-chk.done{background:var(--green);border-color:var(--green);color:#fff}
.act-chk.pending{border-color:var(--amber);background:var(--amber-l)}
.act-chk.overdue{border-color:var(--red);background:var(--red-l);color:var(--red);font-weight:700}
.act-body{flex:1}
.act-title{font-size:.82rem;color:var(--g900);margin-bottom:.22rem;font-weight:500}
.act-meta{font-size:.68rem;color:var(--g400);display:flex;gap:.85rem}
.tag{display:inline-block;padding:.1rem .45rem;border-radius:4px;font-size:.62rem;font-weight:700;text-transform:uppercase;letter-spacing:.3px}
.tg-done{background:var(--green-l);color:var(--green)}
.tg-pend{background:var(--amber-l);color:var(--amber)}
.tg-over{background:var(--red-l);color:var(--red)}

/* XSELL GRID */
.xs-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:.85rem}
.xs-card{background:var(--white);border:1.5px solid var(--g200);border-radius:var(--r);padding:1.2rem;display:flex;flex-direction:column;box-shadow:var(--sh);transition:all .15s;position:relative;overflow:hidden}
.xs-card::after{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:var(--pink);transform:scaleX(0);transform-origin:left;transition:transform .2s}
.xs-card:hover{border-color:var(--pink);box-shadow:0 4px 20px rgba(255,131,218,.15);transform:translateY(-2px)}
.xs-card:hover::after{transform:scaleX(1)}
.xs-tag{font-size:.6rem;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--pink-d);margin-bottom:.35rem}
.xs-title{font-size:.86rem;font-weight:700;color:var(--black);margin-bottom:.45rem}
.xs-desc{font-size:.73rem;color:var(--g500);line-height:1.55;flex:1;margin-bottom:.65rem}
.xs-stat{font-size:.7rem;font-weight:600;color:var(--g700);background:var(--g50);border:1px solid var(--g200);border-radius:var(--rxs);padding:.35rem .6rem;margin-bottom:.65rem}
.xs-mlot{font-size:.65rem;color:var(--g400);margin-bottom:.75rem}
.xs-impact{font-size:.7rem;color:var(--red);background:var(--red-l);border:1px solid #fecaca;border-radius:var(--rxs);padding:.3rem .6rem;margin-bottom:.75rem;line-height:1.4}
.btn-more{width:100%;background:transparent;border:1.5px solid var(--pink);color:var(--pink-d);padding:.5rem;border-radius:99px;font-size:.72rem;font-weight:700;cursor:pointer;font-family:'Barlow',sans-serif;text-transform:uppercase;letter-spacing:.5px;transition:all .15s}
.btn-more:hover,.btn-more.clicked{background:var(--pink);color:var(--black)}

/* PAYMENTS */
.pay-row{display:flex;justify-content:space-between;align-items:flex-start;padding:.6rem 0;border-bottom:1px solid var(--g100)}
.pay-row:last-child{border-bottom:none}
.pay-n{font-size:.78rem;color:var(--g600)}
.pay-sub{font-size:.65rem;color:var(--g400);margin-top:.1rem}
.pay-v{font-size:.84rem;font-weight:700;color:var(--black)}
.pay-badge{font-size:.62rem;padding:.12rem .4rem;border-radius:4px;font-weight:700}

/* ROI */
.roi-row{display:flex;align-items:flex-start;justify-content:space-between;padding:.65rem 0;border-bottom:1px solid var(--g100)}
.roi-row:last-child{border-bottom:none}
.roi-n{font-size:.8rem;color:var(--g600)}
.roi-s{font-size:.66rem;color:var(--g400);margin-top:.1rem}
.roi-v{font-size:.86rem;font-weight:700;color:var(--black)}

/* FK STATS */
.fk-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:.65rem}
.fk-card{background:var(--g50);border:1px solid var(--g200);border-radius:var(--rs);padding:.8rem;text-align:center}
.fk-n{font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.4rem;color:var(--pink-d)}
.fk-l{font-size:.64rem;color:var(--g500);margin-top:.1rem}

/* ADOPTION CARDS */
.adp-card{background:var(--white);border:1.5px solid var(--g200);border-radius:var(--r);padding:1rem;box-shadow:var(--sh)}
.adp-card.gap{opacity:.65;border-style:dashed}
.adp-hd{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:.3rem}
.adp-prod{font-size:.62rem;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--g400)}
.adp-val{font-family:'Barlow Condensed',sans-serif;font-weight:700;font-size:.95rem;text-transform:uppercase;color:var(--black)}
.adp-det{font-size:.7rem;color:var(--g400);margin-top:.25rem}

/* CHAT PANEL */
.chat-panel{width:330px;min-width:330px;border-left:1px solid var(--g200);background:var(--white);display:flex;flex-direction:column}
.chat-hd{padding:.85rem 1rem;border-bottom:1px solid var(--g100);flex-shrink:0}
.chat-tabs{display:flex;gap:.35rem;margin-bottom:.5rem}
.chat-tab{flex:1;padding:.35rem .5rem;border-radius:99px;font-size:.68rem;font-weight:700;text-align:center;cursor:pointer;border:1.5px solid var(--g200);color:var(--g500);transition:all .15s;text-transform:uppercase;letter-spacing:.3px}
.chat-tab.active{background:var(--pink);border-color:var(--pink);color:var(--black)}
.chat-mode-label{font-size:.62rem;color:var(--g400);letter-spacing:.5px}
.online{display:flex;align-items:center;gap:.3rem;font-size:.65rem;color:var(--green);font-weight:600;float:right;margin-top:-1.1rem}
.online::before{content:'';width:5px;height:5px;border-radius:50%;background:var(--green);animation:blink 2s infinite}
.chat-msgs{flex:1;overflow-y:auto;padding:.85rem;display:flex;flex-direction:column;gap:.6rem;scrollbar-width:thin;scrollbar-color:var(--g200) transparent}
.msg{max-width:91%;padding:.6rem .85rem;font-size:.77rem;line-height:1.55;animation:msgIn .25s ease}
@keyframes msgIn{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:none}}
.msg.ai{background:var(--g50);border:1px solid var(--g200);border-radius:3px 10px 10px 10px;color:var(--g900);align-self:flex-start}
.msg.user{background:var(--pink);color:var(--black);border-radius:10px 3px 10px 10px;align-self:flex-end;font-weight:600}
.msg.jorge{background:linear-gradient(135deg,#0d0d0d 0%,#1a1a2e 100%);color:#e2e8f0;border-radius:3px 10px 10px 10px;align-self:flex-start;border:1px solid #2d3748}
.msg.jorge strong{color:var(--pink)}
.msg-from{font-size:.58rem;color:var(--g400);margin-bottom:.6rem;font-weight:700;text-transform:uppercase;letter-spacing:.5px}
.chips{display:flex;flex-wrap:wrap;gap:.3rem;margin-top:.45rem}
.chip{background:var(--white);border:1px solid var(--g200);padding:.25rem .6rem;border-radius:99px;font-size:.66rem;color:var(--g600);cursor:pointer;font-weight:500;transition:all .12s}
.chip:hover{border-color:var(--pink);color:var(--pink-d);background:var(--pink-l)}
.typing-w{background:var(--g50);border:1px solid var(--g200);border-radius:3px 10px 10px 10px;padding:.6rem .85rem;display:flex;gap:.28rem;align-items:center;align-self:flex-start}
.td{width:5px;height:5px;border-radius:50%;background:var(--g300);animation:td 1.2s infinite}
.td:nth-child(2){animation-delay:.2s}.td:nth-child(3){animation-delay:.4s}
@keyframes td{0%,80%,100%{opacity:.3;transform:scale(.8)}40%{opacity:1;transform:scale(1)}}
.chat-ft{padding:.65rem;border-top:1px solid var(--g100);display:flex;gap:.45rem;flex-shrink:0}
.chat-ipt{flex:1;background:var(--g50);border:1px solid var(--g200);border-radius:99px;padding:.5rem .9rem;font-size:.76rem;color:var(--g900);font-family:'Barlow',sans-serif;outline:none;transition:border-color .15s}
.chat-ipt:focus{border-color:var(--pink)}
.chat-ipt::placeholder{color:var(--g400)}
.chat-btn{background:var(--pink);border:none;cursor:pointer;width:32px;height:32px;border-radius:50%;display:flex;align-items:center;justify-content:center;color:var(--black);font-size:.85rem;font-weight:900;transition:background .15s;flex-shrink:0}
.chat-btn:hover{background:var(--pink-d)}

/* TOAST */
.toast{position:fixed;bottom:1.25rem;right:1.25rem;background:var(--white);border:1.5px solid var(--pink-m);border-radius:var(--r);padding:.85rem 1rem;max-width:300px;z-index:999;transform:translateY(110px);opacity:0;transition:all .4s cubic-bezier(.34,1.56,.64,1);box-shadow:0 8px 32px rgba(255,131,218,.2)}
.toast.show{transform:translateY(0);opacity:1}
.toast-hd{display:flex;align-items:center;gap:.45rem;margin-bottom:.4rem}
.toast-icon{width:26px;height:26px;border-radius:5px;background:#4A154B;display:flex;align-items:center;justify-content:center;font-size:.8rem}
.toast-from{font-size:.7rem;font-weight:700;color:var(--black)}
.toast-ch{font-size:.62rem;color:var(--g400)}
.toast-body{font-size:.74rem;color:var(--g600);line-height:1.5}
.toast-body strong{color:var(--black)}
.toast-time{font-size:.6rem;color:var(--g400);margin-top:.35rem}

/* DATA SOURCE BADGE */
.ds-badge{display:inline-flex;align-items:center;gap:.3rem;font-size:.58rem;color:var(--g400);background:var(--g100);border:1px solid var(--g200);padding:.1rem .45rem;border-radius:99px;font-weight:600;text-transform:uppercase;letter-spacing:.3px;margin-left:.5rem;vertical-align:middle}

/* QUERY INDICATOR */
.query-chip{display:inline-flex;align-items:center;gap:.3rem;font-size:.6rem;color:var(--blue);background:var(--blue-l);border:1px solid #bfdbfe;padding:.12rem .5rem;border-radius:99px;font-weight:600;margin-bottom:.75rem}

@media(max-width:1300px){.g4{grid-template-columns:repeat(2,1fr)}.xs-grid{grid-template-columns:repeat(2,1fr)}.chat-panel{width:290px;min-width:290px}}
</style>
</head>
<body>

<!-- LOADER -->
<div id="loader">
  <div class="ld-logo">MEWS<em>.</em>QBR</div>
  <div class="ld-sub">Powered by Jorge</div>
  <div class="ld-track"><div class="ld-bar" id="lBar"></div></div>
  <div class="ld-lbl" id="lLbl">Connecting to Salesforce...</div>
</div>

<!-- APP -->
<div id="app" style="display:none;height:100vh;flex-direction:column">

  <!-- TOPBAR -->
  <div class="topbar">
    <div class="tb-left">
      <div class="brand">MEWS<em>.</em>QBR</div>
      <div class="vdiv"></div>
      <div class="acct-pill"><div class="acct-dot"></div><span id="acctName">The Lakeview Hotel Group</span></div>
    </div>
    <div class="tb-right">
      <div class="period-pill">📅 Last 90 Days · Feb 26 – May 26, 2026</div>
      <button class="btn-pink" onclick="exportPDF()">↓ Export PDF</button>
    </div>
  </div>

  <!-- LAYOUT -->
  <div class="layout">

    <!-- SIDEBAR -->
    <nav class="sidebar">
      <div class="nav-grp">Overview</div>
      <div class="ni active" onclick="go('overview')"><span class="ni-icon">◈</span>Dashboard</div>
      <div class="nav-grp">Performance</div>
      <div class="ni" onclick="go('revenue')"><span class="ni-icon">↗</span>Revenue</div>
      <div class="ni" onclick="go('adoption')"><span class="ni-icon">⊡</span>Product Adoption</div>
      <div class="ni" onclick="go('roi')"><span class="ni-icon">◷</span>ROI & Time Saved</div>
      <div class="ni" onclick="go('ota')"><span class="ni-icon">🌐</span>OTA & Distribution</div>
      <div class="ni" onclick="go('payments')"><span class="ni-icon">💳</span>Payments</div>
      <div class="ni" onclick="go('benchmark')"><span class="ni-icon">⊞</span>Benchmarks</div>
      <div class="nav-grp">Actions</div>
      <div class="ni" onclick="go('actions')"><span class="ni-icon">✓</span>Action Items</div>
      <div class="ni" onclick="go('xsell')"><span class="ni-icon">✦</span>Opportunities</div>
    </nav>

    <!-- CONTENT -->
    <div class="content">

      <!-- SF BAR -->
      <div class="sf-bar">
        <span class="sf-lbl">🔗 Salesforce</span>
        <input class="sf-ipt" id="sfUrl" type="text" value="https://mews.lightning.force.com/lightning/r/Account/001QC000007NDHYYA4/view" placeholder="Paste Salesforce account URL...">
        <button class="btn-pink" onclick="loadAcct()">Pull Data</button>
        <span class="data-status live" id="dataStatus">● Live · 5 sources</span>
      </div>

      <!-- ═══════════════ OVERVIEW ═══════════════ -->
      <div class="sec active" id="s-overview">
        <div class="sec-hdr">
          <div><div class="sec-title">Business Review</div><div class="sec-sub">Q2 2026 · The Lakeview Hotel Group · 3 properties</div></div>
          <span class="tier t-strong">Strong Performance</span>
        </div>
        <div class="g4">
          <div class="card"><div class="c-lbl">Current ARR <span class="ds-badge">Salesforce</span></div><div class="c-val">$124k</div><div class="c-delta up">↑ +8.3% vs last quarter</div></div>
          <div class="card"><div class="c-lbl">Health Score</div><div class="c-val">74<span style="font-size:1rem;color:var(--g400)">/100</span></div><div class="c-delta up">↑ +6 pts this quarter</div></div>
          <div class="card"><div class="c-lbl">OTA Dependency <span class="ds-badge">Databricks</span></div><div class="c-val">62<span style="font-size:1rem;color:var(--g400)">%</span></div><div class="c-delta warn">⚠ Above peer median (54%)</div></div>
          <div class="card"><div class="c-lbl">Renewal <span class="ds-badge">Salesforce</span></div><div class="c-val" style="font-size:1.4rem">Sep '26</div><div class="c-delta muted">127 days away</div></div>
        </div>
        <div class="g2">
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Health Score Breakdown</div>
            <div class="ring-wrap" style="margin-top:.85rem">
              <div class="ring-box">
                <svg width="96" height="96" viewBox="0 0 96 96"><circle class="rbg" cx="48" cy="48" r="45"/><circle class="rfill" id="healthRing" cx="48" cy="48" r="45"/></svg>
                <div class="ring-ctr"><div class="ring-n">74</div><div class="ring-t">Score</div></div>
              </div>
              <div class="dim-list">
                <div class="dim-row"><div class="dim-n">Adoption</div><div class="dim-trk"><div class="dim-b" style="width:0%;background:var(--pink)" data-w="82%"></div></div><div class="dim-s">82</div></div>
                <div class="dim-row"><div class="dim-n">Revenue</div><div class="dim-trk"><div class="dim-b" style="width:0%;background:#60a5fa" data-w="78%"></div></div><div class="dim-s">78</div></div>
                <div class="dim-row"><div class="dim-n">Engagement</div><div class="dim-trk"><div class="dim-b" style="width:0%;background:#a78bfa" data-w="65%"></div></div><div class="dim-s">65</div></div>
                <div class="dim-row"><div class="dim-n">Actions</div><div class="dim-trk"><div class="dim-b" style="width:0%;background:var(--amber)" data-w="60%"></div></div><div class="dim-s">60</div></div>
                <div class="dim-row"><div class="dim-n">Support</div><div class="dim-trk"><div class="dim-b" style="width:0%;background:var(--green)" data-w="88%"></div></div><div class="dim-s">88</div></div>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Peer Position · Urban Upscale · Northeast US</div>
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-top:.85rem">
              <div><div style="font-size:.68rem;color:var(--g500);margin-bottom:.25rem">Online CI Rate <span class="ds-badge">Databricks</span></div><div style="font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.3rem">68%</div><div style="font-size:.65rem;color:var(--g400);margin-bottom:.25rem">Peer: 54%</div><span class="tier t-strong" style="font-size:.58rem">Strong</span></div>
              <div><div style="font-size:.68rem;color:var(--g500);margin-bottom:.25rem">Upsell Conv. <span class="ds-badge">Databricks</span></div><div style="font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.3rem">22%</div><div style="font-size:.65rem;color:var(--g400);margin-bottom:.25rem">Peer: 28%</div><span class="tier t-dev" style="font-size:.58rem">Developing</span></div>
              <div><div style="font-size:.68rem;color:var(--g500);margin-bottom:.25rem">Auto-Settlement <span class="ds-badge">Databricks</span></div><div style="font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.3rem">91%</div><div style="font-size:.65rem;color:var(--g400);margin-bottom:.25rem">Peer: 84%</div><span class="tier t-top" style="font-size:.58rem">Top</span></div>
              <div><div style="font-size:.68rem;color:var(--g500);margin-bottom:.25rem">OTA Share <span class="ds-badge">Databricks</span></div><div style="font-family:'Barlow Condensed',sans-serif;font-weight:900;font-size:1.3rem">62%</div><div style="font-size:.65rem;color:var(--g400);margin-bottom:.25rem">Peer: 54%</div><span class="tier t-dev" style="font-size:.58rem">Above Avg</span></div>
            </div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ REVENUE ═══════════════ -->
      <div class="sec" id="s-revenue">
        <div class="sec-hdr"><div><div class="sec-title">Revenue</div><div class="sec-sub">ARR trends, upsell performance, booking engine <span class="ds-badge">Salesforce + Databricks</span></div></div></div>
        <div class="g4">
          <div class="card"><div class="c-lbl">Total ARR</div><div class="c-val">$124k</div><div class="c-delta up">↑ +8.3% QoQ</div></div>
          <div class="card"><div class="c-lbl">Upsell Revenue</div><div class="c-val">$18.2k</div><div class="c-delta up">↑ +14% vs last Q</div></div>
          <div class="card"><div class="c-lbl">BE Conversion</div><div class="c-val">3.8%</div><div class="c-delta dn">↓ -0.4pts vs peer</div></div>
          <div class="card"><div class="c-lbl">Payments Volume</div><div class="c-val">$2.1M</div><div class="c-delta up">↑ +6% QoQ</div></div>
        </div>
        <div class="g2">
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">ARR by Product · <span class="ds-badge">Salesforce</span></div>
            <div style="margin-top:.5rem">
              <div class="roi-row"><div><div class="roi-n">PMS Core</div></div><div class="roi-v">$74,400</div></div>
              <div class="roi-row"><div><div class="roi-n">Mews Payments</div></div><div class="roi-v">$28,800</div></div>
              <div class="roi-row"><div><div class="roi-n">Flexkeeping</div></div><div class="roi-v">$12,600</div></div>
              <div class="roi-row"><div><div class="roi-n">Mews BI</div></div><div class="roi-v">$8,200</div></div>
            </div>
          </div>
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Upsell by Channel · <span class="ds-badge">product.marts.mrt_daily_upsells...</span></div>
            <div style="margin-top:.85rem">
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Online Check-In (Guest Portal)</span><span class="prog-val">$8,420 · 24%</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:var(--pink)" data-w="68%"></div></div></div>
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Kiosk</span><span class="prog-val">$6,180 · 18%</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:#60a5fa" data-w="50%"></div></div></div>
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Front Desk</span><span class="prog-val">$2,840 · 9%</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:#a78bfa" data-w="32%"></div></div></div>
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Booking Engine</span><span class="prog-val">$760 · 3%</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:var(--amber)" data-w="12%"></div></div></div>
            </div>
            <div class="insight"><div class="ins-lbl">💡 Insight</div><div class="ins-txt">OCI upsell at 24% beats peer median (19%). Kiosk is 5pts below — expanding the product catalog there is a quick win. Booking Engine upsell is near zero — configuration gap, not a product gap.</div></div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ ADOPTION ═══════════════ -->
      <div class="sec" id="s-adoption">
        <div class="sec-hdr"><div><div class="sec-title">Product Adoption</div><div class="sec-sub">Active modules, usage frequency, feature gaps <span class="ds-badge">Databricks</span></div></div></div>
        <div class="g3" style="margin-bottom:.85rem">
          <div class="adp-card"><div class="adp-hd"><div class="adp-prod">PMS Core</div><span class="tier t-top">Active</span></div><div class="adp-val">100%</div><div class="adp-det">Daily users: 14 · Last login: Today</div></div>
          <div class="adp-card"><div class="adp-hd"><div class="adp-prod">Mews Payments</div><span class="tier t-strong">Active</span></div><div class="adp-val">91% SoW</div><div class="adp-det">Auto-settlement: 91% · Card share: 87%</div></div>
          <div class="adp-card"><div class="adp-hd"><div class="adp-prod">Flexkeeping</div><span class="tier t-strong">Active</span></div><div class="adp-val">84%</div><div class="adp-det">Task automation: 66% · 3 properties</div></div>
          <div class="adp-card"><div class="adp-hd"><div class="adp-prod">Online Check-In</div><span class="tier t-strong">Active</span></div><div class="adp-val">68%</div><div class="adp-det">68% of guests · Above peer avg (54%)</div></div>
          <div class="adp-card"><div class="adp-hd"><div class="adp-prod">Mews BI</div><span class="tier t-dev">Low Usage</span></div><div class="adp-val">42%</div><div class="adp-det">2 of 14 users active · Needs attention</div></div>
          <div class="adp-card gap"><div class="adp-hd"><div class="adp-prod">Atomize RMS</div><span class="tier t-grow">Gap</span></div><div class="adp-val" style="color:var(--g400)">Not Active</div><div class="adp-det">78% of top-tier peers use RMS · +18% ADR avg</div></div>
        </div>
        <div class="card">
          <div class="c-lbl" style="margin-bottom:.85rem">Flexkeeping · Last 90 Days <span class="ds-badge">Databricks · product.marts</span></div>
          <div class="fk-grid">
            <div class="fk-card"><div class="fk-n">1,340</div><div class="fk-l">Hours Saved</div></div>
            <div class="fk-card"><div class="fk-n">93%</div><div class="fk-l">Productivity Boost</div></div>
            <div class="fk-card"><div class="fk-n">66%</div><div class="fk-l">Tasks Automated</div></div>
            <div class="fk-card"><div class="fk-n">450+</div><div class="fk-l">Maintenance Resolved</div></div>
            <div class="fk-card"><div class="fk-n">+0.4★</div><div class="fk-l">Review Score Lift</div></div>
            <div class="fk-card"><div class="fk-n">-3%</div><div class="fk-l">Staff Sick Leave</div></div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ ROI ═══════════════ -->
      <div class="sec" id="s-roi">
        <div class="sec-hdr"><div><div class="sec-title">ROI & Time Saved</div><div class="sec-sub">What Mews is delivering for your business <span class="ds-badge">Databricks · fintech.public + product.marts</span></div></div></div>
        <div class="g3">
          <div class="card"><div class="pbar"></div><div class="c-lbl">Time Saved</div><div class="c-val">1,680 hrs</div><div class="c-delta muted">This quarter · all products</div><div style="font-size:.68rem;color:var(--g400);margin-top:.4rem">≈ one full-time front desk employee</div></div>
          <div class="card"><div class="pbar"></div><div class="c-lbl">Cost Savings</div><div class="c-val">$28.4k</div><div class="c-delta up">vs manual workflows</div><div style="font-size:.68rem;color:var(--g400);margin-top:.4rem">Payments + AR reconciliation</div></div>
          <div class="card"><div class="pbar"></div><div class="c-lbl">Revenue Unlocked</div><div class="c-val">$18.2k</div><div class="c-delta up">Upsell + direct bookings</div><div style="font-size:.68rem;color:var(--g400);margin-top:.4rem">OCI + Kiosk channels</div></div>
        </div>
        <div class="g2">
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Time Saved Breakdown <span class="ds-badge">product.marts.mrt_daily_checkins... + fintech</span></div>
            <div style="margin-top:.5rem">
              <div class="roi-row"><div><div class="roi-n">Flexkeeping · Task Automation</div><div class="roi-s">count_total_checkins_r30d · 66% tasks automated</div></div><div class="roi-v">1,340 hrs</div></div>
              <div class="roi-row"><div><div class="roi-n">Online Check-In (Guest Portal)</div><div class="roi-s">count_guest_portal_checkins_r30d × 5min ÷ 60</div></div><div class="roi-v">214 hrs</div></div>
              <div class="roi-row"><div><div class="roi-n">Payments Auto-Settlement</div><div class="roi-s">gross_share_of_wallet_overall_volume = 91%</div></div><div class="roi-v">86 hrs</div></div>
              <div class="roi-row"><div><div class="roi-n">AR Reconciliation</div><div class="roi-s">Invoice volume × 22.5 min avg saved</div></div><div class="roi-v">40 hrs</div></div>
              <div style="padding:.65rem 0;display:flex;justify-content:space-between;font-weight:700;border-top:2px solid var(--black)"><span>Total</span><span style="color:var(--pink-d)">1,680 hrs</span></div>
            </div>
          </div>
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Payments Fee Breakdown <span class="ds-badge">fintech.public.fct_ic_plus_gross_fees...</span></div>
            <div style="margin-top:.5rem">
              <div class="pay-row"><div><div class="pay-n">Card Processing (IC+)</div><div class="pay-sub">net_mews_card_payment_charged_volume_eur</div></div><div class="pay-v">$4,820</div></div>
              <div class="pay-row"><div><div class="pay-n">Mews Commission</div><div class="pay-sub">avg_rate_pct × volume</div></div><div class="pay-v">$2,140</div></div>
              <div class="pay-row"><div><div class="pay-n">Chargebacks</div><div class="pay-sub">chargeback_charged_volume_eur</div></div><div class="pay-v">$320</div></div>
              <div class="pay-row"><div><div class="pay-n">FX Fees</div></div><div class="pay-v">$180</div></div>
              <div class="pay-row" style="border-top:2px solid var(--black);font-weight:700"><div class="pay-n" style="color:var(--black)">Total</div><div class="pay-v" style="color:var(--pink-d)">$7,460</div></div>
            </div>
            <div class="insight"><div class="ins-lbl">📊 Context</div><div class="ins-txt">Effective rate 0.36% vs 0.6% industry avg. Mews Payments saving ~$4.9k vs typical PSP at this volume.</div></div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ OTA ═══════════════ -->
      <div class="sec" id="s-ota">
        <div class="sec-hdr"><div><div class="sec-title">OTA & Distribution</div><div class="sec-sub">Booking channel mix, commission leakage, direct booking opportunity <span class="ds-badge">product.marts.mrt_reservations_and_guests</span></div></div></div>
        <div class="query-chip">🔍 SQL: reservation_origin GROUP BY · last 90 days · reservation_state != 'Canceled'</div>
        <div class="g2">
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Booking Channel Mix · reservation_origin field</div>
            <div class="ota-donut-wrap" style="margin-top:1rem">
              <div class="ota-donut">
                <svg width="120" height="120" viewBox="0 0 120 120" style="transform:rotate(-90deg)">
                  <circle fill="none" stroke="var(--g100)" stroke-width="18" cx="60" cy="60" r="45"/>
                  <!-- OTA: 62% -->
                  <circle fill="none" stroke="var(--red)" stroke-width="18" cx="60" cy="60" r="45" stroke-dasharray="175 283" stroke-dashoffset="0" stroke-linecap="butt"/>
                  <!-- Channel Mgr: 8% -->
                  <circle fill="none" stroke="var(--amber)" stroke-width="18" cx="60" cy="60" r="45" stroke-dasharray="23 283" stroke-dashoffset="-175" stroke-linecap="butt"/>
                  <!-- Direct/Navigator: 22% -->
                  <circle fill="none" stroke="var(--green)" stroke-width="18" cx="60" cy="60" r="45" stroke-dasharray="62 283" stroke-dashoffset="-198" stroke-linecap="butt"/>
                  <!-- Manual: 8% -->
                  <circle fill="none" stroke="var(--blue)" stroke-width="18" cx="60" cy="60" r="45" stroke-dasharray="23 283" stroke-dashoffset="-260" stroke-linecap="butt"/>
                </svg>
                <div class="ota-ctr"><div class="ota-pct">62%</div><div class="ota-tag">OTA</div></div>
              </div>
              <div class="ota-legend">
                <div class="ota-row"><div class="ota-dot" style="background:var(--red)"></div><div class="ota-lbl">Connector (OTA)</div><div class="ota-val">62%</div></div>
                <div class="ota-row"><div class="ota-dot" style="background:var(--green)"></div><div class="ota-lbl">Navigator (Direct BE)</div><div class="ota-val">22%</div></div>
                <div class="ota-row"><div class="ota-dot" style="background:var(--blue)"></div><div class="ota-lbl">Commander (Manual)</div><div class="ota-val">8%</div></div>
                <div class="ota-row"><div class="ota-dot" style="background:var(--amber)"></div><div class="ota-lbl">ChannelManager</div><div class="ota-val">5%</div></div>
                <div class="ota-row"><div class="ota-dot" style="background:var(--g300)"></div><div class="ota-lbl">Distributor (GDS)</div><div class="ota-val">3%</div></div>
              </div>
            </div>
            <div class="leakage-box">
              <div class="leak-lbl">💸 Commission Leakage Calculator</div>
              <div class="leak-txt">At 62% OTA share and ~17% avg commission rate:</div>
              <div class="leak-num" style="margin:.3rem 0">$340k/yr</div>
              <div class="leak-txt">estimated OTA commission cost. If you shifted just 10% of OTA bookings to direct, you'd save <strong>~$34k annually</strong> in commission fees.</div>
            </div>
          </div>
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">OTA Trend · Last 90 Days</div>
            <div class="bchart" id="otaChart" style="margin-top:1rem;height:80px"></div>
            <div style="display:flex;justify-content:space-between;margin-top:.4rem;margin-bottom:1rem">
              <span style="font-size:.62rem;color:var(--g400)">Mar</span>
              <span style="font-size:.62rem;color:var(--g400)">Apr</span>
              <span style="font-size:.62rem;color:var(--g400)">May</span>
            </div>
            <div style="display:flex;gap:.75rem;margin-bottom:1rem">
              <div style="display:flex;align-items:center;gap:.3rem"><div style="width:8px;height:8px;border-radius:2px;background:var(--red)"></div><span style="font-size:.65rem;color:var(--g500)">OTA</span></div>
              <div style="display:flex;align-items:center;gap:.3rem"><div style="width:8px;height:8px;border-radius:2px;background:var(--green)"></div><span style="font-size:.65rem;color:var(--g500)">Direct BE</span></div>
            </div>
            <div class="c-lbl" style="margin-bottom:.5rem">Peer Benchmark · OTA Share</div>
            <div class="bench-lines">
              <div class="bench-line"><div class="bench-tag">You</div><div class="bench-trk"><div class="bench-fill b-you" style="width:0%" data-w="62%"></div></div><div class="bench-num">62%</div></div>
              <div class="bench-line"><div class="bench-tag">Peer avg</div><div class="bench-trk"><div class="bench-fill b-peer" style="width:0%" data-w="54%"></div></div><div class="bench-num">54%</div></div>
              <div class="bench-line"><div class="bench-tag">Top tier</div><div class="bench-trk"><div class="bench-fill b-top" style="width:0%" data-w="38%"></div></div><div class="bench-num">38%</div></div>
            </div>
            <div class="insight" style="margin-top:.85rem"><div class="ins-lbl">🎯 Jorge's Take</div><div class="ins-txt">You're 8pts above peer median on OTA dependency. Top-performing properties in your group average 38% OTA share. Ask Jorge in Tech Expert mode for a tailored action plan.</div></div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ PAYMENTS ═══════════════ -->
      <div class="sec" id="s-payments">
        <div class="sec-hdr"><div><div class="sec-title">Mews Payments</div><div class="sec-sub">Volume, fees, chargeback health, share of wallet <span class="ds-badge">fintech.public.fct_transactions__key_reporting_metrics_by_enterprise_and_day</span></div></div></div>
        <div class="query-chip">🔍 SQL: enterprise_id filter · SUM(net_mews_payments_charged_volume_eur) · AVG(gross_share_of_wallet_overall_volume) · last 90 days</div>
        <div class="g4">
          <div class="card"><div class="c-lbl">Payments Volume</div><div class="c-val">$2.1M</div><div class="c-delta up">↑ +6% QoQ</div></div>
          <div class="card"><div class="c-lbl">Share of Wallet</div><div class="c-val">91%</div><div class="c-delta up">↑ Top tier · peer avg 84%</div></div>
          <div class="card"><div class="c-lbl">Chargeback Rate</div><div class="c-val">0.12%</div><div class="c-delta up">↓ Well below 0.5% threshold</div></div>
          <div class="card"><div class="c-lbl">Effective Rate</div><div class="c-val">0.36%</div><div class="c-delta up">↓ vs 0.6% industry avg</div></div>
        </div>
        <div class="g2">
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">Payment Method Mix <span class="ds-badge">fintech.public.fct_transactions__metrics_by_enterprise</span></div>
            <div style="margin-top:.85rem">
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Card (Mews Terminal)</span><span class="prog-val">68% · $1.43M</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:var(--pink)" data-w="68%"></div></div></div>
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Card (Online/OCI)</span><span class="prog-val">19% · $399k</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:#60a5fa" data-w="19%"></div></div></div>
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Payment Requests</span><span class="prog-val">9% · $189k</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:#a78bfa" data-w="9%"></div></div></div>
              <div class="prog"><div class="prog-hd"><span class="prog-lbl">Alternative Payments (APM)</span><span class="prog-val">4% · $84k</span></div><div class="prog-trk"><div class="prog-fill" style="width:0%;background:var(--amber)" data-w="4%"></div></div></div>
            </div>
            <div class="insight"><div class="ins-lbl">💡 Opportunity</div><div class="ins-txt">APM adoption at 4% is below the 11% peer average for properties with international guests. Enabling more APMs could reduce friction for non-card payers and improve conversion.</div></div>
          </div>
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl">If NOT on Mews Payments — Impact</div>
            <div style="margin-top:.5rem;display:flex;flex-direction:column;gap:.65rem">
              <div style="padding:.75rem;background:var(--red-l);border:1px solid #fecaca;border-radius:var(--rs)">
                <div style="font-size:.62rem;font-weight:700;color:var(--red);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.3rem">❌ Cost Impact</div>
                <div style="font-size:.74rem;color:var(--g700);line-height:1.5">Effective rate would be ~0.6% vs current 0.36%. At $2.1M volume that's <strong>+$5,040/quarter</strong> in additional fees.</div>
              </div>
              <div style="padding:.75rem;background:var(--red-l);border:1px solid #fecaca;border-radius:var(--rs)">
                <div style="font-size:.62rem;font-weight:700;color:var(--red);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.3rem">❌ Operational Impact</div>
                <div style="font-size:.74rem;color:var(--g700);line-height:1.5">No auto-settlement = staff manually handling payment exceptions. At 91% current automation, that's ~86 hrs/quarter recovered.</div>
              </div>
              <div style="padding:.75rem;background:var(--red-l);border:1px solid #fecaca;border-radius:var(--rs)">
                <div style="font-size:.62rem;font-weight:700;color:var(--red);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.3rem">❌ Risk Impact</div>
                <div style="font-size:.74rem;color:var(--g700);line-height:1.5">No tokenization = higher chargeback exposure. Current rate 0.12% — properties without Mews Payments average 0.31%.</div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ BENCHMARKS ═══════════════ -->
      <div class="sec" id="s-benchmark">
        <div class="sec-hdr">
          <div><div class="sec-title">Peer Benchmarks</div><div class="sec-sub">Anonymised · Urban Upscale · Northeast US · min. 100 properties <span class="ds-badge">playground.value_pillars + tech.value_pillars</span></div></div>
          <span class="tier t-strong">Strong Tier</span>
        </div>
        <div class="query-chip">🔍 SQL: dim_peer_groups_segments JOIN benchmark_revenue_per_m2_rolling_12m_v3 ON peer_group_id</div>
        <div class="g2">
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl" style="margin-bottom:1rem">Your Position vs Peer Group</div>
            <div class="bench-row"><div class="bench-m">Online CI Rate</div><div class="bench-lines"><div class="bench-line"><div class="bench-tag">You</div><div class="bench-trk"><div class="bench-fill b-you" style="width:0%" data-w="68%"></div></div><div class="bench-num">68%</div></div><div class="bench-line"><div class="bench-tag">Peer avg</div><div class="bench-trk"><div class="bench-fill b-peer" style="width:0%" data-w="54%"></div></div><div class="bench-num">54%</div></div><div class="bench-line"><div class="bench-tag">Top tier</div><div class="bench-trk"><div class="bench-fill b-top" style="width:0%" data-w="82%"></div></div><div class="bench-num">82%</div></div></div></div>
            <div class="bench-row"><div class="bench-m">Upsell Conversion</div><div class="bench-lines"><div class="bench-line"><div class="bench-tag">You</div><div class="bench-trk"><div class="bench-fill b-you" style="width:0%" data-w="22%"></div></div><div class="bench-num">22%</div></div><div class="bench-line"><div class="bench-tag">Peer avg</div><div class="bench-trk"><div class="bench-fill b-peer" style="width:0%" data-w="28%"></div></div><div class="bench-num">28%</div></div><div class="bench-line"><div class="bench-tag">Top tier</div><div class="bench-trk"><div class="bench-fill b-top" style="width:0%" data-w="41%"></div></div><div class="bench-num">41%</div></div></div></div>
            <div class="bench-row"><div class="bench-m">Auto-Settlement Rate</div><div class="bench-lines"><div class="bench-line"><div class="bench-tag">You</div><div class="bench-trk"><div class="bench-fill b-you" style="width:0%" data-w="91%"></div></div><div class="bench-num">91%</div></div><div class="bench-line"><div class="bench-tag">Peer avg</div><div class="bench-trk"><div class="bench-fill b-peer" style="width:0%" data-w="84%"></div></div><div class="bench-num">84%</div></div><div class="bench-line"><div class="bench-tag">Top tier</div><div class="bench-trk"><div class="bench-fill b-top" style="width:0%" data-w="96%"></div></div><div class="bench-num">96%</div></div></div></div>
            <div class="bench-row"><div class="bench-m">OTA Share (lower = better)</div><div class="bench-lines"><div class="bench-line"><div class="bench-tag">You</div><div class="bench-trk"><div class="bench-fill b-you" style="width:0%" data-w="62%"></div></div><div class="bench-num">62%</div></div><div class="bench-line"><div class="bench-tag">Peer avg</div><div class="bench-trk"><div class="bench-fill b-peer" style="width:0%" data-w="54%"></div></div><div class="bench-num">54%</div></div><div class="bench-line"><div class="bench-tag">Top tier</div><div class="bench-trk"><div class="bench-fill b-top" style="width:0%" data-w="38%"></div></div><div class="bench-num">38%</div></div></div></div>
            <div class="bench-row"><div class="bench-m">Rev per m²</div><div class="bench-lines"><div class="bench-line"><div class="bench-tag">You</div><div class="bench-trk"><div class="bench-fill b-you" style="width:0%" data-w="61%"></div></div><div class="bench-num">$61</div></div><div class="bench-line"><div class="bench-tag">Peer avg</div><div class="bench-trk"><div class="bench-fill b-peer" style="width:0%" data-w="58%"></div></div><div class="bench-num">$58</div></div><div class="bench-line"><div class="bench-tag">Top tier</div><div class="bench-trk"><div class="bench-fill b-top" style="width:0%" data-w="84%"></div></div><div class="bench-num">$84</div></div></div></div>
          </div>
          <div class="card">
            <div class="pbar"></div>
            <div class="c-lbl" style="margin-bottom:1rem">What Top Performers Have That You Don't</div>
            <div style="display:flex;flex-direction:column;gap:.65rem">
              <div style="padding:.85rem;background:var(--amber-l);border:1px solid #fde68a;border-radius:var(--rs)"><div style="font-size:.62rem;font-weight:700;color:var(--amber);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.35rem">🔶 Atomize RMS</div><div style="font-size:.75rem;font-weight:600;margin-bottom:.25rem">Revenue Management System</div><div style="font-size:.72rem;color:var(--g600);line-height:1.5">78% of top-tier peers use RMS · +18% ADR average · ~$378k additional room revenue at your volume</div></div>
              <div style="padding:.85rem;background:var(--amber-l);border:1px solid #fde68a;border-radius:var(--rs)"><div style="font-size:.62rem;font-weight:700;color:var(--amber);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.35rem">🔶 Direct Booking Share</div><div style="font-size:.75rem;font-weight:600;margin-bottom:.25rem">OTA Dependency Reduction</div><div style="font-size:.72rem;color:var(--g600);line-height:1.5">Top tier at 38% OTA share vs your 62% · $34k+ annual commission savings if 10% shifts to direct</div></div>
              <div style="padding:.85rem;background:var(--amber-l);border:1px solid #fde68a;border-radius:var(--rs)"><div style="font-size:.62rem;font-weight:700;color:var(--amber);text-transform:uppercase;letter-spacing:.5px;margin-bottom:.35rem">🔶 Mews BI Adoption</div><div style="font-size:.75rem;font-weight:600;margin-bottom:.25rem">Business Intelligence (Full Usage)</div><div style="font-size:.72rem;color:var(--g600);line-height:1.5">You have BI but only 2 of 14 users active · Top performers average 6+ active users tracking Value Pillar metrics monthly</div></div>
            </div>
          </div>
        </div>
      </div>

      <!-- ═══════════════ ACTIONS ═══════════════ -->
      <div class="sec" id="s-actions">
        <div class="sec-hdr">
          <div><div class="sec-title">Action Items</div><div class="sec-sub">From Jan 2026 QBR · via Gong <span class="ds-badge">Gong API</span></div></div>
          <div style="font-size:.76rem;color:var(--g400)">2 done · 1 in progress · 1 overdue</div>
        </div>
        <div class="card">
          <div class="act-row"><div class="act-chk done">✓</div><div class="act-body"><div class="act-title">Enable online check-in for all 3 properties</div><div class="act-meta"><span>Owner: Customer</span><span>Due: Mar 15</span><span class="tag tg-done">Done</span></div></div></div>
          <div class="act-row"><div class="act-chk done">✓</div><div class="act-body"><div class="act-title">Activate Flexkeeping automated cleaning schemas at Lakeview Downtown</div><div class="act-meta"><span>Owner: Alida</span><span>Due: Apr 1</span><span class="tag tg-done">Done</span></div></div></div>
          <div class="act-row"><div class="act-chk pending"></div><div class="act-body"><div class="act-title">Expand kiosk upsell catalog — add breakfast + late checkout packages</div><div class="act-meta"><span>Owner: Customer</span><span>Due: May 30</span><span class="tag tg-pend">In Progress</span></div></div></div>
          <div class="act-row"><div class="act-chk overdue">!</div><div class="act-body"><div class="act-title">Schedule Mews BI training for revenue manager team</div><div class="act-meta"><span>Owner: Alida</span><span>Due: Apr 20</span><span class="tag tg-over">Overdue</span></div></div></div>
        </div>
      </div>

      <!-- ═══════════════ XSELL ═══════════════ -->
      <div class="sec" id="s-xsell">
        <div class="sec-hdr"><div><div class="sec-title">Growth Opportunities</div><div class="sec-sub">Framed as customer value · Based on your data profile and MLOT stage</div></div></div>
        <div class="xs-grid" id="xsGrid"></div>
      </div>

    </div><!-- end content -->

    <!-- ═══════════════ JORGE CHAT ═══════════════ -->
    <div class="chat-panel">
      <div class="chat-hd">
        <div class="chat-tabs">
          <div class="chat-tab active" id="tab-data" onclick="switchTab('data')">📊 QBR Data</div>
          <div class="chat-tab" id="tab-jorge" onclick="switchTab('jorge')">🧠 Jorge</div>
        </div>
        <div class="chat-mode-label" id="modeLabel">Answering from your live account data</div>
        <div class="online">Live</div>
      </div>
      <div class="chat-msgs" id="chatMsgs"></div>
      <div class="chat-ft">
        <input class="chat-ipt" id="chatIpt" placeholder="Ask Jorge anything..." onkeydown="if(event.key==='Enter')sendMsg()">
        <button class="chat-btn" onclick="sendMsg()">↑</button>
      </div>
    </div>

  </div>
</div>

<!-- SLACK TOAST -->
<div class="toast" id="toast">
  <div class="toast-hd"><div class="toast-icon">💬</div><div><div class="toast-from">Slack · DM to Alida</div><div class="toast-ch">mews-qbr-bot</div></div></div>
  <div class="toast-body" id="toastBody"></div>
  <div class="toast-time" id="toastTime"></div>
</div>

<script>
// ═══════ XSELL DATA ═══════
const xsProducts = [
  {tag:'Atomize RMS',title:'Revenue Management',desc:'Properties like yours in the Strong tier average +18% ADR with RMS. Manual pricing misses demand signals every night — the gap compounds over time.',stat:'📈 +18% ADR in your peer group',impact:'Without it: ~$378k/yr in untapped room revenue at your volume.',mlot:'MLOT: Awareness'},
  {tag:'Mews Events (EMS)',title:'Event & Meeting Management',desc:'You have 3 meeting rooms with no EMS. Properties using EMS automate 75% of event documentation and respond to RFPs in under 2 minutes.',stat:'⏱ 75% reduction in event documentation',impact:'Without it: lost event revenue, no utilisation tracking, manual quoting.',mlot:'MLOT: Not Started'},
  {tag:'Mews POS',title:'Point of Sale',desc:'Your F&B Rev/m² is $22 vs a peer median of $31 for POS properties. Disconnected F&B = double-entry, slower service, no integrated revenue view.',stat:'🍽 +$9/m² F&B revenue gap vs POS peers',impact:'Without it: manual reconciliation, no F&B revenue insight, service delays.',mlot:'MLOT: Awareness'},
  {tag:'Accounts Receivable',title:'Automated AR & Invoicing',desc:'At 40+ B2B invoices/month, AR automation saves 20–25 min per invoice — that\'s ~16 hours/month your team gets back for guest-facing work.',stat:'⚡ ~16 hrs/month recovered at your invoice volume',impact:'Without it: manual reconciliation errors, delayed cash collection.',mlot:'MLOT: Not Started'},
  {tag:'Direct Booking Strategy',title:'Reduce OTA Dependency',desc:'You\'re at 62% OTA share — 8pts above peer median. Top-performing properties in your group average 38%. Each 1% shift to direct saves ~$3.4k/yr in commission.',stat:'💰 $34k/yr savings if 10% shifts to direct',impact:'Without it: $340k+/yr in OTA commissions, no guest data ownership.',mlot:'MLOT: Strategy Conversation'},
  {tag:'Mews BI',title:'Business Intelligence (Full Adoption)',desc:'You have BI but only 2 of 14 users are active. Top performers track Value Pillar metrics monthly — it drives faster revenue decisions and higher NPS.',stat:'📊 Top tier: avg 6+ active BI users',impact:'Without full adoption: data exists but isn\'t driving decisions.',mlot:'MLOT: Adoption Gap'},
];

// ═══════ AI RESPONSES ═══════
let currentMode = 'data';
const dataResponses = {
  'upsell':'Upsell conversion at 22% is 6pts below peer median (28%). The gap is almost entirely kiosk — 18% vs 23% peer average. Root cause: only 3 upsell products active on kiosk vs a peer average of 8. Booking Engine upsell is near zero — that\'s a configuration gap, not a product gap. Both are quick wins.',
  'ota':'OTA share is 62% vs a peer median of 54%. The main origin breakdown from product.marts.mrt_reservations_and_guests: Connector 62%, Navigator (direct BE) 22%, Commander 8%, ChannelManager 5%, Distributor 3%. At 17% avg OTA commission, that\'s ~$340k/yr in fees. Top performers in your peer group average 38% OTA share.',
  'payments':'Auto-settlement (gross_share_of_wallet_overall_volume) is at 91% — top tier, peer median is 84%. Chargeback rate at 0.12% is well below the 0.5% risk threshold. Effective rate 0.36% vs 0.6% industry average. The one gap: APM usage at 4% vs 11% peer average for properties with international guests.',
  'health':'Health score is 74/100. Strongest dimension: Support trend (88) and Product Adoption (82). Weakest: Actions (60) — you have 1 overdue item from Jan QBR. Revenue trend (78) is solid with ARR up 8.3% QoQ. Engagement (65) is the one to watch — Mews BI has only 2 active users.',
  'summary':'Two-line exec summary: "Lakeview is performing well — ARR up 8.3%, payments auto-settlement at 91% (top tier), and Flexkeeping saving 1,340 hours this quarter. The two clearest next steps are: (1) Atomize RMS — 78% of similar properties use it, averaging +18% ADR; (2) Direct booking strategy — 62% OTA dependency is costing ~$340k/yr in commission and leaving guest data on the table."'
};
const jorgeResponses = {
  'ota':() => `Great question. Here's your situation and what I'd do about it:\n\n**Your numbers:** 62% OTA, 22% direct — 8pts above peer median. Top properties in your group are at 38% OTA.\n\n**5 things I'd tackle in order:**\n\n1. **Rate parity audit** — OTAs often undercut your own booking engine without you knowing. Run a parity check and close any gaps. Guests book direct when the price is the same or slightly better.\n\n2. **Booking Engine placement** — Is your BE widget above the fold on your website? One click to book, not buried in a nav menu. This alone can move direct share 3-5pts.\n\n3. **Direct booking incentive** — Even small perks (free early check-in, welcome drink) shift behavior. Doesn't have to be a rate discount.\n\n4. **Loyalty rate setup in Mews** — Create a "Book Direct" rate with a small perk attached. Communicate it through OCI and your booking confirmation emails.\n\n5. **Google Hotel Ads (metasearch)** — If you're not running metasearch, you're invisible on price comparison. Mews integrates with Google Hotel Ads — this is often the fastest ROI lever.\n\nAt your OTA share, a realistic 90-day target is moving from 62% to 56-58%. That's $20-34k in annual commission savings.`,
  'rms':() => `RMS is the highest-ROI product for properties at your stage. Here's the honest case:\n\n**The math:** Properties in your peer group using Atomize average +18% ADR. At your current RevPAR and occupancy, that's roughly $378k in additional annual room revenue — or about 3x the cost of the software.\n\n**Why it works:** Manual pricing reacts to demand after it happens. RMS prices ahead of it — adjusting rates based on lead time, competitor pricing, local events, and historical patterns simultaneously. Your revenue manager can't track all of that manually.\n\n**When to bring it up with the customer:** When they're asking "why is our ADR below competitors?" — that's the moment. Frame it as: "Properties with similar profiles that added RMS in 2025 averaged 14-22% ADR uplift within 6 months."\n\n**One caveat:** RMS works best when occupancy data is reliable and rate strategy is already somewhat defined. If they have no rate strategy at all, start there first.`,
  'direct':() => `Direct booking strategy is really a combination of three things: distribution (where you're visible), conversion (getting people to book when they land), and retention (getting them back without OTAs).\n\n**Fastest wins for Mews properties:**\n\n**Distribution:** Google Hotel Ads integration — Mews supports this natively. You show up in price comparison searches, which are where most direct bookers start.\n\n**Conversion:** Booking Engine UX. Check: Is it mobile-optimized? Does it load in under 2 seconds? Are upsell products visible pre-booking? Each friction point costs 2-4% conversion.\n\n**Retention:** Post-stay email with a direct booking discount for next visit. Guests who've stayed once are 4x more likely to book direct the second time if asked directly.\n\n**The OTA relationship:** Don't try to eliminate OTAs — they're customer acquisition channels. The goal is to convert OTA guests into direct guests on their second stay. That's where the compound value is.`
};

// ═══════ TABS ═══════
function switchTab(mode) {
  currentMode = mode;
  document.getElementById('tab-data').classList.toggle('active', mode==='data');
  document.getElementById('tab-jorge').classList.toggle('active', mode==='jorge');
  document.getElementById('modeLabel').textContent = mode==='data' ? 'Answering from your live account data' : 'Jorge · Senior Hospitality Tech Consultant';
  const msgs = document.getElementById('chatMsgs');
  msgs.innerHTML = '';
  if (mode==='data') {
    addMsgFrom('ai','Hey Alida 👋 Lakeview data is loaded. Key signals:\n\n• ARR +8.3% — solid trajectory\n• OTA share at 62% — 8pts above peer median, $340k/yr in commission\n• Payments SoW 91% — top tier\n• Kiosk upsell below peer average — quick win available\n• 1 overdue action item\n\nWhat do you want to dig into?');
    const wrap = document.createElement('div');
    wrap.className='chips';
    [['Why is upsell low?','upsell'],['OTA breakdown','ota'],['Payments health','payments'],['Exec summary','summary']].forEach(([t,k])=>{
      const c=document.createElement('div');c.className='chip';c.textContent=t;c.onclick=()=>{c.parentElement.remove();addMsgFrom('user',t);setTimeout(()=>addMsgFrom('ai',dataResponses[k]),900)};
      wrap.appendChild(c);
    });
    msgs.appendChild(wrap);
  } else {
    addMsgFrom('jorge','Hola! I\'m **Jorge** — senior hospitality tech consultant. I know Mews inside out and I\'ve worked with 200+ properties on distribution, revenue management, and operations strategy.\n\nLooking at Lakeview\'s data, the thing I\'d focus on first is that 62% OTA share. That\'s a real problem — it\'s costing them $340k/yr in commission and they have zero guest data ownership from those bookings.\n\nWhat do you want to tackle?');
    const wrap = document.createElement('div');
    wrap.className='chips';
    [['How to reduce OTA dependency?','ota'],['RMS — make the case','rms'],['Direct booking strategy','direct']].forEach(([t,k])=>{
      const c=document.createElement('div');c.className='chip';c.textContent=t;c.onclick=()=>{c.parentElement.remove();addMsgFrom('user',t);setTimeout(()=>addMsgFrom('jorge',jorgeResponses[k]()),1100)};
      wrap.appendChild(c);
    });
    msgs.appendChild(wrap);
  }
}

// ═══════ CHAT ═══════
function addMsgFrom(role, txt) {
  const c = document.getElementById('chatMsgs');
  if (role !== 'user') {
    const dot = document.createElement('div');
    dot.className='typing-w';
    dot.innerHTML='<div class="td"></div><div class="td"></div><div class="td"></div>';
    c.appendChild(dot); c.scrollTop=c.scrollHeight;
    setTimeout(()=>{
      dot.remove();
      const m=document.createElement('div');
      m.className=`msg ${role}`;
      m.style.whiteSpace='pre-line';
      // Bold markdown
      m.innerHTML=txt.replace(/\*\*(.*?)\*\*/g,'<strong>$1</strong>');
      c.appendChild(m); c.scrollTop=c.scrollHeight;
    }, role==='jorge'?1100:850);
  } else {
    const m=document.createElement('div');m.className='msg user';m.textContent=txt;c.appendChild(m);c.scrollTop=c.scrollHeight;
  }
}

function sendMsg() {
  const ipt=document.getElementById('chatIpt');
  const t=ipt.value.trim(); if(!t) return; ipt.value='';
  addMsgFrom('user',t);
  const lower=t.toLowerCase();
  setTimeout(()=>{
    if(currentMode==='data') {
      let r='Based on Lakeview\'s live data: ARR is up 8.3%, OTA share is 62% (above peer median), and payments SoW is at 91% (top tier). The clearest gap is kiosk upsell conversion at 18% vs a 23% peer average — product catalog expansion is the quick win there.';
      if(lower.includes('ota')||lower.includes('booking')) r=dataResponses['ota'];
      else if(lower.includes('upsell')) r=dataResponses['upsell'];
      else if(lower.includes('pay')) r=dataResponses['payments'];
      else if(lower.includes('health')||lower.includes('score')) r=dataResponses['health'];
      else if(lower.includes('summar')||lower.includes('exec')) r=dataResponses['summary'];
      addMsgFrom('ai',r);
    } else {
      let r='Good question. Based on what I\'m seeing for Lakeview — the 62% OTA dependency is the highest-priority issue. Every OTA booking is $34-51 in commission AND you lose the guest relationship. I\'d start with the Google Hotel Ads integration in Mews — it\'s the fastest lever for direct visibility.';
      if(lower.includes('ota')||lower.includes('direct')||lower.includes('booking')) r=jorgeResponses['ota']();
      else if(lower.includes('rms')||lower.includes('revenue manag')||lower.includes('atomize')) r=jorgeResponses['rms']();
      addMsgFrom('jorge',r);
    }
  }, currentMode==='jorge'?1100:850);
}

// ═══════ XSELL ═══════
function buildXsell() {
  const g=document.getElementById('xsGrid'); if(!g) return;
  g.innerHTML=xsProducts.map((p,i)=>`
    <div class="xs-card">
      <div class="xs-tag">${p.tag}</div>
      <div class="xs-title">${p.title}</div>
      <div class="xs-desc">${p.desc}</div>
      <div class="xs-stat">${p.stat}</div>
      <div class="xs-impact">⚠ ${p.impact}</div>
      <div class="xs-mlot">${p.mlot}</div>
      <button class="btn-more" id="bm${i}" onclick="tellMore(${i})">Tell me more →</button>
    </div>`).join('');
}

function tellMore(idx) {
  const p=xsProducts[idx];
  document.getElementById('bm'+idx).textContent='✓ Opening Jorge...';
  document.getElementById('bm'+idx).classList.add('clicked');
  switchTab('jorge');
  go('overview');
  setTimeout(()=>{
    addMsgFrom('user',`Tell me more about ${p.tag} for Lakeview`);
    setTimeout(()=>addMsgFrom('jorge',`Here's the value case for **${p.tag}** specifically for Lakeview:\n\n${p.desc}\n\n${p.stat}\n\n**The cost of not acting:** ${p.impact}\n\nWant me to put together talking points for the customer conversation, or show how this benchmarks against their peer group?`),1200);
  },300);
  fireToast(p);
}

function fireToast(p) {
  const toast=document.getElementById('toast');
  const now=new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
  document.getElementById('toastBody').innerHTML=`🔔 <strong>The Lakeview Hotel Group</strong> clicked <strong>"Tell me more"</strong> on <strong>${p.tag}</strong>.<br><br>${p.mlot}`;
  document.getElementById('toastTime').textContent=`Today at ${now}`;
  toast.classList.add('show');
  setTimeout(()=>toast.classList.remove('show'),6000);
}

// ═══════ NAV ═══════
function go(id) {
  document.querySelectorAll('.sec').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.ni').forEach(n=>n.classList.remove('active'));
  document.getElementById('s-'+id).classList.add('active');
  const map={overview:0,revenue:1,adoption:2,roi:3,ota:4,payments:5,benchmark:6,actions:7,xsell:8};
  document.querySelectorAll('.ni')[map[id]]?.classList.add('active');
  setTimeout(animBars,80);
}

// ═══════ ANIMATIONS ═══════
function animBars() {
  document.querySelectorAll('[data-w]').forEach(el=>{ if(el.style.width==='0%'||el.style.width==='') el.style.width=el.dataset.w; });
}
function animRing() {
  const r=document.getElementById('healthRing'); if(!r) return;
  const c=2*Math.PI*45;
  r.style.strokeDasharray=c;
  r.style.strokeDashoffset=c-(74/100)*c;
}

// ═══════ OTA CHART ═══════
function buildOtaChart() {
  const el=document.getElementById('otaChart'); if(!el) return;
  const ota=[68,66,65,64,63,62,63,61,60,62,61,59];
  const dir=[18,20,21,22,23,22,23,24,25,24,25,27];
  const mx=Math.max(...ota,...dir);
  el.style.display='flex';el.style.alignItems='flex-end';el.style.gap='.35rem';el.style.height='80px';
  el.innerHTML=ota.map((v,i)=>`
    <div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:2px">
      <div style="width:100%;height:${Math.round(v/mx*70)}px;background:${i>=8?'var(--red)':'rgba(220,38,38,.35)'};border-radius:2px 2px 0 0"></div>
      <div style="width:100%;height:${Math.round(dir[i]/mx*70)}px;background:${i>=8?'var(--green)':'rgba(22,163,74,.35)'};border-radius:2px 2px 0 0;margin-top:2px"></div>
    </div>`).join('');
}

// ═══════ LOAD ACCOUNT ═══════
function loadAcct() {
  document.getElementById('acctName').textContent='Pulling data...';
  document.getElementById('dataStatus').textContent='● Connecting...';
  document.getElementById('dataStatus').className='data-status';
  setTimeout(()=>{
    document.getElementById('acctName').textContent='The Lakeview Hotel Group';
    document.getElementById('dataStatus').textContent='● Live · 5 sources';
    document.getElementById('dataStatus').className='data-status live';
    addMsgFrom('ai','Data refreshed. Lakeview — 3 properties, ARR $124k, last contact 4 days ago. OTA share 62%, health score 74. Anything to prep before the call?');
  },1800);
}

function exportPDF() {
  addMsgFrom('ai','Generating exec PDF... In the full build this produces a branded 2-page leave-behind: health score, top 5 metrics, peer position, top 3 recommended actions, and Jorge\'s summary.');
}

// ═══════ LOADER ═══════
window.addEventListener('load',()=>{
  const bar=document.getElementById('lBar');
  const lbl=document.getElementById('lLbl');
  const steps=[[15,'Connecting to Salesforce...'],[35,'Querying product.marts (reservations, checkins, upsells)...'],[55,'Querying fintech.public (transactions, fees)...'],[72,'Loading value_pillars benchmark data...'],[88,'Fetching Gong call summary...'],[100,'Jorge is ready']];
  let i=0;
  const tick=()=>{
    if(i>=steps.length){
      setTimeout(()=>{
        document.getElementById('loader').style.opacity='0';
        setTimeout(()=>{
          document.getElementById('loader').style.display='none';
          const app=document.getElementById('app');
          app.style.display='flex';
          buildXsell(); buildOtaChart();
          setTimeout(animBars,200); setTimeout(animRing,350);
          switchTab('data');
        },450);
      },400);return;
    }
    bar.style.width=steps[i][0]+'%';lbl.textContent=steps[i][1];i++;
    setTimeout(tick,500);
  };
  tick();
});
</script>
</body>
</html>
