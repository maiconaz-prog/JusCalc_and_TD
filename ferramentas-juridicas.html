<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ferramentas Jurídico-Financeiras — Maicon Zanette</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/PapaParse/5.4.1/papaparse.min.js"></script>
<style>
/* ═══════════════════════════════════════
   TOP NAV — menu global entre módulos
═══════════════════════════════════════ */
*{box-sizing:border-box;margin:0;padding:0}
html{height:100%}
body{font-family:'Segoe UI',system-ui,sans-serif;background:#f0f2f5;color:#1a1a2e;font-size:13px;min-height:100vh;display:flex;flex-direction:column}

.topnav{display:flex;align-items:center;gap:0;background:#0f2050;padding:0;height:48px;flex-shrink:0;position:sticky;top:0;z-index:200;box-shadow:0 2px 8px rgba(0,0,0,.25)}
.topnav-brand{display:flex;align-items:center;gap:10px;padding:0 20px;border-right:1px solid rgba(255,255,255,.12);height:100%;flex-shrink:0}
.topnav-brand .logo{width:28px;height:28px;background:rgba(255,255,255,.15);border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:15px}
.topnav-brand .brand-name{font-size:13px;font-weight:700;color:#fff;letter-spacing:.3px;line-height:1.2}
.topnav-brand .brand-sub{font-size:10px;color:rgba(255,255,255,.5);letter-spacing:.2px}
.topnav-tabs{display:flex;align-items:stretch;height:100%;flex:1}
.topnav-tab{display:flex;align-items:center;gap:8px;padding:0 22px;font-size:12px;font-weight:600;color:rgba(255,255,255,.6);cursor:pointer;border-bottom:3px solid transparent;transition:all .15s;letter-spacing:.2px;white-space:nowrap}
.topnav-tab:hover{background:rgba(255,255,255,.07);color:rgba(255,255,255,.9)}
.topnav-tab.active{color:#fff;border-bottom-color:#3b82f6;background:rgba(59,130,246,.1)}
.topnav-tab .tab-icon{font-size:14px;opacity:.8}
.topnav-badge{margin-left:auto;padding:0 20px;font-size:10px;color:rgba(255,255,255,.35);letter-spacing:.3px}

/* módulos */
.module{display:none;flex:1;overflow:hidden;min-height:0}
.module.active{display:flex;flex-direction:column;flex:1}

/* ═══════════════════════════════════════
   MÓDULO 1 — CALCULADORA JUDICIAL
═══════════════════════════════════════ */
.cj-app{display:flex;flex:1;overflow:hidden}
.cj-sidebar{width:280px;min-width:280px;background:#fff;border-right:1px solid #e0e4ee;overflow-y:auto;display:flex;flex-direction:column;flex-shrink:0}
.cj-main{flex:1;display:flex;flex-direction:column;overflow:hidden;background:#fff}

.cj-sidebar-header{padding:14px 16px 12px;border-bottom:1px solid #e0e4ee;background:linear-gradient(135deg,#1a3a7c 0%,#2563eb 100%)}
.cj-sidebar-header h2{font-size:14px;font-weight:700;color:#fff}
.cj-sidebar-header p{font-size:11px;color:rgba(255,255,255,.7);margin-top:2px}

.cj-ctabs{display:flex;border-bottom:1px solid #e0e4ee;background:#f8f9fc}
.cj-ctab{flex:1;padding:7px 0;border:none;background:none;cursor:pointer;font-size:11px;font-weight:600;color:#6b7280;border-bottom:2px solid transparent;transition:all .15s}
.cj-ctab:hover{color:#2563eb;background:#eff6ff}
.cj-ctab.active{color:#2563eb;border-bottom-color:#2563eb;background:#fff}

.cj-panel{border-bottom:1px solid #e8eaf0}
.cj-ptoggle{width:100%;display:flex;align-items:center;justify-content:space-between;padding:9px 14px;background:none;border:none;cursor:pointer;font-size:12px;font-weight:600;color:#374151;text-align:left;transition:background .15s}
.cj-ptoggle:hover{background:#f5f7ff}
.cj-ptoggle.active{color:#2563eb;background:#eff6ff}
.cj-ptoggle .arr{font-size:9px;transition:transform .2s;color:#9ca3af}
.cj-ptoggle.open .arr{transform:rotate(180deg)}
.cj-pbody{padding:12px 14px 14px;display:none;background:#fafbff;border-top:1px solid #e8eaf0}
.cj-pbody.open{display:block}

.cj-frow{margin-bottom:9px}
.cj-flabel{display:block;font-size:10px;color:#6b7280;margin-bottom:4px;font-weight:600;text-transform:uppercase;letter-spacing:.4px}
.cj-select,.cj-input{width:100%;padding:6px 8px;border:1px solid #d1d5db;border-radius:5px;background:#fff;color:#1f2937;font-size:12px;outline:none;transition:border-color .15s}
.cj-select:focus,.cj-input:focus{border-color:#2563eb;box-shadow:0 0 0 2px rgba(37,99,235,.12)}
.cj-radio-grp{display:flex;flex-direction:column;gap:5px;margin-bottom:8px}
.cj-radio-row{display:flex;align-items:center;gap:7px;font-size:12px;cursor:pointer;color:#374151}
.cj-radio-row input{accent-color:#2563eb;width:13px;height:13px}
.cj-check-row{display:flex;align-items:center;gap:7px;font-size:12px;cursor:pointer;color:#374151;margin-bottom:6px}
.cj-check-row input{accent-color:#2563eb;width:13px;height:13px}

.cj-btn-apply{width:100%;padding:7px;background:#2563eb;color:#fff;border:none;border-radius:5px;cursor:pointer;font-size:12px;font-weight:600;margin-top:10px;transition:background .15s}
.cj-btn-apply:hover{background:#1d4ed8}
.cj-btn-reset{width:100%;padding:7px;background:none;color:#6b7280;border:1px solid #d1d5db;border-radius:5px;cursor:pointer;font-size:12px;margin-top:5px}
.cj-btn-reset:hover{background:#f3f4f6}

.cj-topbar{padding:10px 16px;border-bottom:1px solid #e0e4ee;display:flex;align-items:center;gap:6px;flex-wrap:wrap;background:#fff;min-height:48px}
.cj-tab-btn{padding:5px 14px;border:1px solid #d1d5db;border-radius:5px;background:none;cursor:pointer;font-size:12px;font-weight:500;color:#6b7280;transition:all .15s}
.cj-tab-btn:hover{background:#f3f4f6}
.cj-tab-btn.active{background:#2563eb;color:#fff;border-color:#2563eb}
.cj-tab-item{display:flex;align-items:center;gap:2px}
.cj-close-tab{padding:3px 6px;background:none;border:none;cursor:pointer;font-size:12px;color:#9ca3af;border-radius:3px}
.cj-close-tab:hover{background:#fee2e2;color:#dc2626}
.cj-btn-nova{padding:5px 12px;background:none;border:1px dashed #9ca3af;border-radius:5px;cursor:pointer;font-size:12px;color:#6b7280;transition:all .15s}
.cj-btn-nova:hover{border-color:#2563eb;color:#2563eb;background:#eff6ff}
.cj-topbar-right{margin-left:auto;display:flex;gap:6px}
.cj-btn-calc{padding:6px 16px;background:#2563eb;color:#fff;border:none;border-radius:5px;cursor:pointer;font-size:12px;font-weight:600}
.cj-btn-calc:hover{background:#1d4ed8}
.cj-btn-mem{padding:6px 14px;background:none;color:#2563eb;border:1px solid #2563eb;border-radius:5px;cursor:pointer;font-size:12px;font-weight:500}
.cj-btn-mem:hover{background:#eff6ff}
.cj-btn-sec{padding:6px 14px;background:none;color:#6b7280;border:1px solid #d1d5db;border-radius:5px;cursor:pointer;font-size:12px}
.cj-btn-sec:hover{background:#f3f4f6}

.cj-content{flex:1;display:flex;flex-direction:column;overflow:hidden}
.cj-thead{display:grid;grid-template-columns:110px 1fr 90px 135px 120px;padding:8px 16px;background:#f8f9fc;border-bottom:1px solid #e0e4ee;font-size:11px;font-weight:600;color:#6b7280;text-transform:uppercase;letter-spacing:.4px}
.cj-tbody{flex:1;overflow-y:auto}
.cj-row{display:grid;grid-template-columns:110px 1fr 90px 135px 120px;padding:10px 16px;border-bottom:1px solid #f1f3f9;font-size:12px;align-items:center;cursor:pointer;transition:background .1s}
.cj-row:hover{background:#f5f7ff}
.cj-row.sel{background:#eff6ff;border-left:3px solid #2563eb}
.cj-row-desc{font-weight:500;color:#1f2937}
.cj-row-obs{font-size:11px;color:#9ca3af;margin-top:2px}
.cj-row-btns{display:flex;gap:5px}
.cj-rbtn{padding:4px 10px;border:1px solid #d1d5db;border-radius:4px;background:#fff;cursor:pointer;font-size:11px;font-weight:500;color:#374151;transition:all .15s}
.cj-rbtn:hover{background:#f3f4f6}
.cj-rbtn.del{color:#dc2626;border-color:#fca5a5}
.cj-rbtn.del:hover{background:#fff5f5}
.cj-badge{display:inline-block;padding:2px 8px;border-radius:12px;font-size:10px;font-weight:600}
.cj-badge-D{background:#dbeafe;color:#1d4ed8}
.cj-badge-C{background:#fef3c7;color:#92400e}
.cj-badge-H{background:#e0e7ff;color:#4338ca}
.cj-badge-C2{background:#d1fae5;color:#065f46}

.cj-action-bar{padding:10px 16px;border-top:1px solid #e0e4ee;display:flex;align-items:center;gap:8px;background:#fff}
.cj-btn-inc{padding:7px 18px;background:#2563eb;color:#fff;border:none;border-radius:5px;cursor:pointer;font-size:12px;font-weight:600}
.cj-btn-inc:hover{background:#1d4ed8}
.cj-btn-act{padding:6px 14px;background:#fff;color:#374151;border:1px solid #d1d5db;border-radius:5px;cursor:pointer;font-size:12px;font-weight:500;transition:all .15s}
.cj-btn-act:hover{background:#f3f4f6}
.cj-btn-act.danger{color:#dc2626;border-color:#fca5a5}
.cj-btn-act.danger:hover{background:#fff5f5}

.cj-totals{padding:12px 16px;background:#eff6ff;border-top:1px solid #bfdbfe;display:flex;align-items:center;gap:0;flex-wrap:wrap}
.cj-titem{flex:1;min-width:100px;padding:0 10px;border-right:1px solid #bfdbfe}
.cj-titem:first-child{padding-left:0}
.cj-titem:last-child{border-right:none}
.cj-tlabel{font-size:10px;color:#3b82f6;font-weight:600;text-transform:uppercase;letter-spacing:.5px;margin-bottom:3px}
.cj-tval{font-size:13px;font-weight:700;color:#1e3a8a}
.cj-resumo{padding:10px 16px;background:#1e3a8a;display:flex;align-items:center;justify-content:space-between}
.cj-rlabel{font-size:12px;color:rgba(255,255,255,.75)}
.cj-rval{font-size:16px;font-weight:700;color:#fff}

.cj-empty{text-align:center;padding:60px 20px;color:#9ca3af}
.cj-empty .ico{font-size:42px;margin-bottom:12px;opacity:.3}

.cj-highlight{background:#fffbe6;border:1px solid #fcd34d;border-radius:5px;padding:7px 10px;font-size:11px;color:#92400e;margin-top:8px;line-height:1.5}

/* modais CJ */
.cj-moverlay{position:fixed;inset:0;background:rgba(15,23,42,.5);display:none;align-items:center;justify-content:center;z-index:500;backdrop-filter:blur(2px)}
.cj-moverlay.open{display:flex}
.cj-modal{background:#fff;border-radius:10px;padding:22px;width:420px;max-width:95vw;box-shadow:0 20px 60px rgba(0,0,0,.2);border:1px solid #e0e4ee}
.cj-modal h3{font-size:15px;font-weight:600;margin-bottom:16px;color:#1e3a8a}
.cj-modal-btns{display:flex;gap:8px;margin-top:16px}
.cj-modal-btns button{flex:1;padding:9px;border-radius:6px;cursor:pointer;font-size:13px;font-weight:600}
.cj-btn-confirm{background:#2563eb;color:#fff;border:none}
.cj-btn-confirm:hover{background:#1d4ed8}
.cj-btn-cancel{background:#fff;color:#6b7280;border:1px solid #d1d5db}

.cj-memorial-modal{background:#fff;border-radius:10px;padding:22px;width:700px;max-width:96vw;max-height:88vh;display:flex;flex-direction:column;box-shadow:0 20px 60px rgba(0,0,0,.2)}
.cj-memorial-body{flex:1;overflow-y:auto;margin:12px 0;padding:16px;background:#fafbff;border:1px solid #e0e4ee;border-radius:6px;font-size:12px;line-height:1.7;color:#1f2937;white-space:pre-wrap;font-family:'Courier New',monospace}
.cj-memorial-btns{display:flex;gap:8px}

#cj-toast{position:fixed;bottom:24px;right:24px;background:#1e3a8a;color:#fff;padding:10px 18px;border-radius:8px;font-size:13px;font-weight:500;display:none;z-index:9999;box-shadow:0 8px 24px rgba(0,0,0,.25)}

/* ═══════════════════════════════════════
   MÓDULO 2 — TESOURO DIRETO
   (CSS original preservado, prefixado .td-)
═══════════════════════════════════════ */
.td-wrap{display:flex;flex:1;overflow:hidden}
.td-wrap .sb{width:200px;flex-shrink:0;background:#fff;border-right:1px solid #e0ddd8;padding:12px 0;overflow-y:auto}
.td-wrap .body{flex:1;padding:20px;overflow-y:auto;overflow-x:hidden}
.sb-logo{padding:0 14px 12px;border-bottom:1px solid #e0ddd8;margin-bottom:8px}
.sb-logo h2{font-size:14px;font-weight:600;color:#1a1a18}
.sb-logo p{font-size:11px;color:#aaa;margin-top:2px}
.badge{font-size:10px;background:#e1f5ee;color:#085041;padding:2px 10px;border-radius:99px;font-weight:600;margin:0 12px 8px;display:block;text-align:center}
.ns{font-size:10px;font-weight:600;color:#bbb;text-transform:uppercase;letter-spacing:.06em;padding:8px 14px 3px}
.ni{display:flex;align-items:center;gap:7px;padding:7px 14px;font-size:13px;color:#555;cursor:pointer;border-left:2px solid transparent}
.ni:hover{background:#f5f4f0}
.ni.on{color:#185FA5;border-left-color:#185FA5;background:#eef4fb;font-weight:600}
.page{display:none}.page.on{display:block}
h1{font-size:20px;font-weight:700;color:#1a1a18;margin-bottom:3px}
.sub{font-size:12px;color:#666;margin-bottom:14px}
.mg{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:8px;margin-bottom:14px}
.mc{background:#fff;border:1px solid #e8e5e0;border-radius:9px;padding:10px 12px}
.ml{font-size:10px;color:#aaa;text-transform:uppercase;font-weight:600;letter-spacing:.04em;margin-bottom:3px}
.mv{font-size:19px;font-weight:700;color:#1a1a18}
.ms{font-size:10px;color:#aaa;margin-top:2px}
.up{color:#1D9E75}.dn{color:#A32D2D}.wn{color:#BA7517}
.card{background:#fff;border:1px solid #e8e5e0;border-radius:10px;padding:14px;margin-bottom:10px}
.card h3{font-size:14px;font-weight:600;margin-bottom:4px;color:#1a1a18}
.card .desc{font-size:11px;color:#666;margin-bottom:10px}
.cw{position:relative;width:100%;height:220px}
.tg{display:grid;grid-template-columns:repeat(auto-fill,minmax(155px,1fr));gap:7px;margin-bottom:12px}
.tb{background:#fff;border:1px solid #e8e5e0;border-radius:9px;padding:10px 12px;cursor:pointer;text-align:left;width:100%;transition:border-color .15s}
.tb:hover{border-color:#aaa}
.tb.on{border:2px solid #185FA5;background:#eef4fb}
.tb .tn{font-size:11px;font-weight:600;color:#1a1a18}
.tb .tr{font-size:18px;font-weight:700;margin:3px 0}
.tb .tt{font-size:10px;color:#aaa}
.rng{display:flex;border:1px solid #ddd;border-radius:8px;overflow:hidden;width:fit-content;margin-bottom:10px}
.rng button{padding:5px 13px;font-size:11px;border:none;background:#fff;color:#555;cursor:pointer;font-family:inherit}
.rng button.on{background:#185FA5;color:#fff;font-weight:600}
.al{border-left:3px solid;border-radius:0 8px 8px 0;padding:8px 11px;margin-bottom:7px}
.al h4{font-size:12px;font-weight:600;margin-bottom:2px}
.al p{font-size:11px;line-height:1.55;color:#444}
.al-gn{border-color:#1D9E75;background:#e1f5ee}.al-gn h4{color:#085041}
.al-am{border-color:#BA7517;background:#faeeda}.al-am h4{color:#633806}
.al-bl{border-color:#185FA5;background:#eef4fb}.al-bl h4{color:#0C447C}
.ir{display:flex;align-items:center;gap:8px;padding:7px 0;border-bottom:1px solid #f0ede8}
.ir:last-child{border-bottom:none}
.in{font-size:12px;flex:1;color:#1a1a18}
.iv{font-size:12px;font-weight:700;min-width:62px;text-align:right;color:#1a1a18}
.bg{font-size:10px;font-weight:600;padding:1px 7px;border-radius:4px}
.bg-gn{background:#e1f5ee;color:#085041}.bg-rd{background:#fcebeb;color:#791F1F}.bg-am{background:#faeeda;color:#633806}.bg-bl{background:#eef4fb;color:#0C447C}
.pfb{display:flex;gap:6px;margin-bottom:12px;flex-wrap:wrap}
.pfb button{padding:6px 16px;font-size:12px;font-weight:600;border:1px solid #ddd;border-radius:8px;cursor:pointer;background:#fff;color:#555;font-family:inherit}
.pfb button.on{background:#eef4fb;color:#185FA5;border-color:#185FA5}
.rc{background:#fff;border:1px solid #e8e5e0;border-radius:10px;padding:12px 14px;margin-bottom:8px}
.rc.ft{border:2px solid #185FA5}
.rh2{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:5px}
.rn{font-size:13px;font-weight:700;color:#1a1a18}
.rr{font-size:18px;font-weight:700}
.rd{font-size:11px;color:#555;line-height:1.55;margin-bottom:4px}
.tags{display:flex;gap:4px;flex-wrap:wrap}
.tag{font-size:10px;font-weight:600;padding:2px 7px;border-radius:4px}
.rat{display:flex;gap:2px;margin:4px 0}
.rt{width:9px;height:9px;border-radius:2px}.rt.on{background:#185FA5}.rt.off{background:#ddd}
.sg{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:12px}
.sf label{display:block;font-size:10px;font-weight:600;color:#aaa;text-transform:uppercase;letter-spacing:.04em;margin-bottom:5px}
.sf input[type=number]{width:100%;padding:7px 10px;font-size:13px;border:1px solid #ddd;border-radius:8px;background:#fff;color:#1a1a18}
.sf input[type=range]{width:100%;margin-top:5px;accent-color:#185FA5}
.sv2{font-size:12px;font-weight:600;margin-top:3px;color:#1a1a18}
.lg{display:flex;flex-wrap:wrap;gap:12px;margin-top:8px;font-size:11px;color:#555}
.lg span{display:flex;align-items:center;gap:4px}
.ls{width:9px;height:9px;border-radius:2px;flex-shrink:0}
.sl{font-size:10px;font-weight:600;color:#aaa;text-transform:uppercase;letter-spacing:.06em;margin:.9rem 0 .4rem}
.mbg{display:none;position:fixed;inset:0;background:rgba(0,0,0,.45);z-index:300;align-items:center;justify-content:center}
.mbg.open{display:flex}
.modal{background:#fff;border-radius:12px;padding:24px;max-width:480px;width:90%}
.modal h2{font-size:16px;font-weight:700;margin-bottom:6px;color:#1a1a18}
.modal p{font-size:12px;color:#555;line-height:1.6;margin-bottom:12px}
.dz{border:2px dashed #ccc;border-radius:9px;padding:20px;text-align:center;cursor:pointer;margin-bottom:10px;transition:border-color .2s}
.dz:hover,.dz.drag{border-color:#185FA5;background:#eef4fb}
.dz p{font-size:12px;color:#666;margin-bottom:8px}
.btn{display:inline-flex;align-items:center;gap:5px;padding:8px 16px;font-size:12px;font-weight:600;border-radius:8px;cursor:pointer;border:1px solid #ddd;background:#fff;color:#1a1a18;font-family:inherit}
.btn-p{background:#185FA5;color:#fff;border-color:#185FA5}
.btn-gn{background:#1D9E75;color:#fff;border-color:#1D9E75}
.pbar{height:5px;background:#eee;border-radius:99px;overflow:hidden;margin:10px 0 4px}
.pfill{height:100%;background:#185FA5;border-radius:99px;width:0%;transition:width .3s}
.res-box{background:#e1f5ee;border:1px solid #9fe1cb;border-radius:8px;padding:12px;margin-top:10px;display:none}
.err-box{background:#fcebeb;border:1px solid #f7c1c1;border-radius:8px;padding:10px;margin-top:10px;display:none;font-size:12px;color:#791F1F}
td-footer{padding:16px;font-size:11px;color:#bbb;text-align:center;display:block}
td-footer a{color:#bbb;text-decoration:none}
@media(max-width:640px){.td-wrap .sb{display:none}.td-wrap .body{padding:12px}.sg{grid-template-columns:1fr}.cj-sidebar{display:none}}

/* scrollbar global */
::-webkit-scrollbar{width:5px;height:5px}
::-webkit-scrollbar-track{background:#f1f3f9}
::-webkit-scrollbar-thumb{background:#c7d2fe;border-radius:3px}
::-webkit-scrollbar-thumb:hover{background:#818cf8}

@media print{
  .topnav,.cj-sidebar,.cj-topbar,.cj-action-bar,.cj-row-btns,.cj-btn-calc,.cj-btn-mem,.cj-btn-sec,.cj-btn-nova{display:none!important}
  #mod-calculadora{display:flex!important;flex-direction:column}
  .cj-app{display:block}
  .cj-content{overflow:visible}
  .cj-totals,.cj-resumo{display:flex!important}
}
</style>
</head>
<body>

<!-- ═══════════ TOP NAV GLOBAL ═══════════ -->
<nav class="topnav">
  <div class="topnav-brand">
    <div class="logo">⚖</div>
    <div>
      <div class="brand-name">Ferramentas Jurídico-Financeiras</div>
      <div class="brand-sub">Maicon Zanette · Advogado</div>
    </div>
  </div>
  <div class="topnav-tabs">
    <div class="topnav-tab active" onclick="switchModule('calculadora')" id="navtab-calculadora">
      <span class="tab-icon">⚖</span> Calculadora Judicial
    </div>
    <div class="topnav-tab" onclick="switchModule('tesouro')" id="navtab-tesouro">
      <span class="tab-icon">📈</span> Tesouro Direto
    </div>
  </div>
  <div class="topnav-badge">v2.0 · Florianópolis/SC</div>
</nav>

<!-- ═══════════════════════════════════════════════════════
     MÓDULO 1 — CALCULADORA JUDICIAL
═══════════════════════════════════════════════════════ -->
<div class="module active" id="mod-calculadora">
<div class="cj-app">

<!-- SIDEBAR -->
<div class="cj-sidebar">
  <div class="cj-sidebar-header">
    <h2>⚖ Calculadora Judicial</h2>
    <p>Liquidação de Sentença</p>
  </div>
  <div class="cj-ctabs">
    <button class="cj-ctab active" onclick="cjSwitchCrit(this)">Critérios</button>
    <button class="cj-ctab" onclick="cjSwitchCrit(this)">Avançado</button>
  </div>

  <!-- CORREÇÃO MONETÁRIA -->
  <div class="cj-panel">
    <button class="cj-ptoggle open active" onclick="cjTogglePanel(this)"><span>Correção Monetária</span><span class="arr">▼</span></button>
    <div class="cj-pbody open">
      <div class="cj-radio-grp">
        <label class="cj-radio-row"><input type="radio" name="corr" value="nao" onchange="cjSetCorrMode(this)"> Não aplicar</label>
        <label class="cj-radio-row"><input type="radio" name="corr" value="tabela" checked onchange="cjSetCorrMode(this)"> Usar tabela</label>
        <label class="cj-radio-row"><input type="radio" name="corr" value="taxa" onchange="cjSetCorrMode(this)"> Usar outra taxa</label>
      </div>
      <div id="cj-corr-tabela">
        <div class="cj-frow">
          <label class="cj-flabel">Índice</label>
          <select class="cj-select" id="cj-sel-corr">
            <option value="IPCA-E">IPCA-E IBGE</option>
            <option value="INPC">INPC IBGE</option>
            <option value="IPCA">IPCA IBGE</option>
            <option value="POUPANCA">Poupança Sem Capitalização</option>
          </select>
        </div>
        <label class="cj-check-row"><input type="checkbox" id="cj-chk-expurgos"> Com expurgos</label>
      </div>
      <div id="cj-corr-taxa" style="display:none">
        <div class="cj-frow"><label class="cj-flabel">Taxa ao mês (%)</label><input type="number" class="cj-input" placeholder="0,0000" step="0.0001"></div>
      </div>
      <div class="cj-frow">
        <label class="cj-check-row"><input type="checkbox" id="cj-chk-corr-desde" checked> Aplicar desde</label>
        <input type="date" class="cj-input" id="cj-corr-desde" style="margin-top:5px">
      </div>
      <div class="cj-frow"><label class="cj-flabel">Até</label><input type="date" class="cj-input" id="cj-corr-ate"></div>
      <div class="cj-frow">
        <label class="cj-flabel">Pró-Rata</label>
        <select class="cj-select"><option>Conforme tabela</option><option>Proporcional por dias</option></select>
      </div>
      <button class="cj-btn-apply" onclick="cjToast('Critérios de correção aplicados.')">Aplicar</button>
      <button class="cj-btn-reset" onclick="cjResetCorr()">Desfazer</button>
    </div>
  </div>

  <!-- JUROS MORATÓRIOS -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Juros Moratórios</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-radio-grp">
        <label class="cj-radio-row"><input type="radio" name="juros" value="nao" onchange="cjSetJurosMode(this)"> Não aplicar</label>
        <label class="cj-radio-row"><input type="radio" name="juros" value="tabela" checked onchange="cjSetJurosMode(this)"> Usar tabela</label>
        <label class="cj-radio-row"><input type="radio" name="juros" value="taxa" onchange="cjSetJurosMode(this)"> Usar outra taxa</label>
      </div>
      <div id="cj-juros-tabela">
        <div class="cj-frow"><label class="cj-flabel">Tabela</label>
          <select class="cj-select" id="cj-sel-juros">
            <option value="POUPANCA_SEM">Poupança Sem Capitalização</option>
            <option value="SELIC">SELIC — Lei 11.960/09</option>
            <option value="CC_1PCT">1% ao mês — CC art. 406</option>
          </select>
        </div>
      </div>
      <div id="cj-juros-taxa" style="display:none">
        <div class="cj-frow"><label class="cj-flabel">Taxa ao mês (%)</label><input type="number" class="cj-input" placeholder="1,0000" step="0.0001"></div>
      </div>
      <div class="cj-frow">
        <label class="cj-check-row"><input type="checkbox" checked> Aplicar desde</label>
        <input type="date" class="cj-input" id="cj-juros-desde" style="margin-top:5px">
      </div>
      <div class="cj-frow"><label class="cj-flabel">Até</label><input type="date" class="cj-input" id="cj-juros-ate"></div>
      <button class="cj-btn-apply" onclick="cjToast('Critérios de juros aplicados.')">Aplicar</button>
      <button class="cj-btn-reset">Desfazer</button>
    </div>
  </div>

  <!-- JUROS COMPENSATÓRIOS -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Juros Compensatórios</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-radio-grp">
        <label class="cj-radio-row"><input type="radio" name="jcomp" value="nao" checked> Não aplicar</label>
        <label class="cj-radio-row"><input type="radio" name="jcomp" value="tabela"> Usar tabela</label>
      </div>
      <div class="cj-frow"><label class="cj-flabel">Base legal</label>
        <select class="cj-select"><option>Lei 11.960/09 — Art. 5º</option><option>6% ao ano — Súm. 618 STF</option></select>
      </div>
      <div class="cj-frow"><label class="cj-check-row"><input type="checkbox"> Aplicar desde</label><input type="date" class="cj-input" style="margin-top:5px"></div>
      <button class="cj-btn-apply" onclick="cjToast('Juros compensatórios configurados.')">Aplicar</button>
    </div>
  </div>

  <!-- CORREÇÃO E JUROS (pós) -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Correção e Juros (pós)</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-radio-grp">
        <label class="cj-radio-row"><input type="radio" name="corrjuros" value="nao"> Não aplicar</label>
        <label class="cj-radio-row"><input type="radio" name="corrjuros" value="selic" checked> SELIC (a partir 09/12/2021)</label>
        <label class="cj-radio-row"><input type="radio" name="corrjuros" value="ipcae"> IPCA-E + 6% aa (Tema 905 STF)</label>
      </div>
      <div class="cj-frow"><label class="cj-check-row"><input type="checkbox" checked> Aplicar desde</label><input type="date" class="cj-input" value="2021-12-09" style="margin-top:5px"></div>
      <div class="cj-highlight">📊 SELIC acumulada desde 09/12/2021 ≈ <strong id="cj-selic-acum">calculando...</strong></div>
      <button class="cj-btn-apply" onclick="cjCalcSelicAcum()">Calcular acumulado</button>
    </div>
  </div>

  <!-- MULTA PERIÓDICA -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Multa Periódica (Astreintes)</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-radio-grp">
        <label class="cj-radio-row"><input type="radio" name="multa_p" value="nao" checked> Não aplicar</label>
        <label class="cj-radio-row"><input type="radio" name="multa_p" value="sim"> Aplicar astreintes</label>
      </div>
      <div class="cj-frow"><label class="cj-flabel">Valor diário (R$)</label><input type="number" class="cj-input" placeholder="0,00" step="0.01"></div>
      <div class="cj-frow"><label class="cj-flabel">De — até</label><div style="display:flex;gap:6px"><input type="date" class="cj-input"><input type="date" class="cj-input"></div></div>
      <button class="cj-btn-apply" onclick="cjToast('Multa periódica configurada.')">Aplicar</button>
    </div>
  </div>

  <!-- HONORÁRIOS -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Honorários e Multa</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-frow"><label class="cj-flabel">Honorários Advocatícios (%)</label><input type="number" class="cj-input" id="cj-hon-pct" placeholder="10" step="0.5" min="0" max="30"></div>
      <div class="cj-frow"><label class="cj-flabel">Base de cálculo</label><select class="cj-select" id="cj-hon-base"><option value="total">Sobre o total atualizado</option><option value="principal">Sobre o principal</option></select></div>
      <div class="cj-frow"><label class="cj-flabel">Multa art. 523 CPC (%)</label><input type="number" class="cj-input" id="cj-multa-pct" placeholder="10" step="0.5" min="0"></div>
      <div class="cj-frow"><label class="cj-flabel">Honorários Sucumbência (%)</label><input type="number" class="cj-input" id="cj-hon-suc-pct" placeholder="0" step="0.5" min="0"></div>
      <button class="cj-btn-apply" onclick="cjToast('Honorários configurados.')">Aplicar</button>
    </div>
  </div>

  <!-- IDENTIFICAÇÃO -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Identificação</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-frow"><label class="cj-flabel">Processo nº</label><input type="text" class="cj-input" id="cj-proc-num" placeholder="0000000-00.0000.0.00.0000"></div>
      <div class="cj-frow"><label class="cj-flabel">Credor / Exequente</label><input type="text" class="cj-input" id="cj-credor" placeholder="Nome completo"></div>
      <div class="cj-frow"><label class="cj-flabel">Devedor / Executado</label><input type="text" class="cj-input" id="cj-devedor" placeholder="Nome completo"></div>
      <div class="cj-frow"><label class="cj-flabel">Vara / Juízo</label><input type="text" class="cj-input" id="cj-vara" placeholder="Ex: 3ª Vara Cível de Florianópolis"></div>
      <div class="cj-frow"><label class="cj-flabel">Data-base do cálculo</label><input type="date" class="cj-input" id="cj-data-base"></div>
      <div class="cj-frow"><label class="cj-flabel">Elaborado por</label><input type="text" class="cj-input" id="cj-elaborado-por" placeholder="Advogado / Contador"></div>
    </div>
  </div>

  <!-- CUMPRIMENTO DE SENTENÇA -->
  <div class="cj-panel">
    <button class="cj-ptoggle" onclick="cjTogglePanel(this)"><span>Cumprimento de Sentença</span><span class="arr">▼</span></button>
    <div class="cj-pbody">
      <div class="cj-frow"><label class="cj-flabel">Trânsito em julgado</label><input type="date" class="cj-input" id="cj-transito"></div>
      <div class="cj-frow"><label class="cj-flabel">Data da intimação (art. 513)</label><input type="date" class="cj-input" id="cj-intimacao"></div>
      <div class="cj-frow"><label class="cj-flabel">Prazo para pagamento (dias)</label><input type="number" class="cj-input" value="15" id="cj-prazo"></div>
      <div class="cj-highlight" id="cj-prazo-info" style="display:none"></div>
      <button class="cj-btn-apply" onclick="cjCalcPrazo()">Calcular prazo</button>
    </div>
  </div>
</div><!-- /sidebar -->

<!-- MAIN -->
<div class="cj-main">
  <div class="cj-topbar" id="cj-tabs-bar">
    <div class="cj-tab-item"><button class="cj-tab-btn active" onclick="cjSwitchTab(this)" id="cj-tabBtn-0">Principal</button></div>
    <button class="cj-btn-nova" onclick="cjNovaAba()">+ Nova Aba</button>
    <div class="cj-topbar-right">
      <button class="cj-btn-calc" onclick="cjCalcular()">▶ Calcular</button>
      <button class="cj-btn-mem" onclick="cjGerarMemorial()">📄 Memorial</button>
      <button class="cj-btn-sec" onclick="window.print()">🖨 Imprimir</button>
      <button class="cj-btn-sec" onclick="cjExportarCSV()">⬇ CSV</button>
    </div>
  </div>
  <div class="cj-content">
    <div class="cj-thead"><span>Data</span><span>Descrição</span><span>Tipo</span><span>Valor Original</span><span>Ações</span></div>
    <div class="cj-tbody" id="cj-tbody">
      <div class="cj-empty" id="cj-empty">
        <div class="ico">📋</div>
        <p style="font-weight:500;color:#6b7280;margin-bottom:6px">Nenhum valor incluído</p>
        <p>Clique em <strong>"Incluir"</strong> abaixo para adicionar rubricas ao cálculo.</p>
      </div>
    </div>
  </div>
  <div class="cj-action-bar">
    <button class="cj-btn-inc" onclick="cjOpenModal()">+ Incluir</button>
    <button class="cj-btn-act" onclick="cjAlterar()">Alterar</button>
    <button class="cj-btn-act danger" onclick="cjExcluir()">Excluir</button>
    <button class="cj-btn-act" onclick="cjLimpar()" style="margin-left:auto">Limpar tudo</button>
  </div>
  <div class="cj-totals" id="cj-totals" style="display:none">
    <div class="cj-titem"><div class="cj-tlabel">Principal</div><div class="cj-tval" id="cj-tot-principal">R$ 0,00</div></div>
    <div class="cj-titem"><div class="cj-tlabel">Correção</div><div class="cj-tval" id="cj-tot-corr">R$ 0,00</div></div>
    <div class="cj-titem"><div class="cj-tlabel">Juros</div><div class="cj-tval" id="cj-tot-juros">R$ 0,00</div></div>
    <div class="cj-titem"><div class="cj-tlabel">Honorários</div><div class="cj-tval" id="cj-tot-hon">R$ 0,00</div></div>
    <div class="cj-titem"><div class="cj-tlabel">Multa (art.523)</div><div class="cj-tval" id="cj-tot-multa">R$ 0,00</div></div>
  </div>
  <div class="cj-resumo" id="cj-resumo" style="display:none">
    <span class="cj-rlabel">TOTAL GERAL — atualizado em <span id="cj-data-calc"></span></span>
    <span class="cj-rval" id="cj-tot-geral">R$ 0,00</span>
  </div>
</div>
</div><!-- /cj-app -->
</div><!-- /mod-calculadora -->

<!-- ═══════════════════════════════════════════════════════
     MÓDULO 2 — TESOURO DIRETO
═══════════════════════════════════════════════════════ -->
<div class="module" id="mod-tesouro">
<div class="mbg" id="td-modal">
 <div class="modal">
  <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px">
   <h2>Atualizar dados</h2><button class="btn" onclick="tdCloseM()">Fechar</button>
  </div>
  <p>Baixe o CSV em <a href="https://www.tesourotransparente.gov.br/ckan/dataset/taxas-dos-titulos-ofertados-pelo-tesouro-direto" target="_blank" style="color:#185FA5">Tesouro Transparente</a> e carregue aqui. Um novo <b>index.html</b> com os dados atualizados será baixado automaticamente.</p>
  <div class="dz" id="td-dz" onclick="document.getElementById('td-fi').click()">
   <p>Arraste o CSV ou clique para selecionar</p>
   <button class="btn btn-p" onclick="event.stopPropagation();document.getElementById('td-fi').click()">Selecionar arquivo</button>
   <input type="file" id="td-fi" accept=".csv" style="display:none" onchange="tdHandleCSV(event)">
  </div>
  <div id="td-prog" style="display:none"><div class="pbar"><div class="pfill" id="td-pfill"></div></div><div id="td-pmsg" style="font-size:11px;color:#555"></div></div>
  <div class="err-box" id="td-errbox"></div>
  <div class="res-box" id="td-resbox">
   <p style="font-size:13px;font-weight:700;color:#085041;margin-bottom:4px">index.html gerado com sucesso!</p>
   <p id="td-resstats" style="font-size:12px;color:#085041;margin-bottom:10px"></p>
   <button class="btn btn-gn" onclick="tdRedown()">Baixar novamente</button>
  </div>
 </div>
</div>
<div class="td-wrap">
 <nav class="sb">
  <div class="sb-logo"><h2>Tesouro Direto</h2><p>Análise histórica + macro</p></div>
  <span class="badge" id="td-sbd">carregando...</span>
  <div class="ns">Histórico</div>
  <div class="ni on" onclick="tdGo('ov')">◉ Visão geral</div>
  <div class="ni" onclick="tdGo('hi')">↑ Histórico</div>
  <div class="ni" onclick="tdGo('re')">! Quando resgatar</div>
  <div class="ns">Análise</div>
  <div class="ni" onclick="tdGo('ma')">★ Painel macro</div>
  <div class="ni" onclick="tdGo('ti')">✓ Qual título</div>
  <div class="ni" onclick="tdGo('si')">≈ Simulador</div>
  <div style="padding:14px 14px 0;margin-top:auto">
    <button class="btn btn-p" style="width:100%;justify-content:center;font-size:11px" onclick="tdOpenM()">⬆ Atualizar dados CSV</button>
  </div>
 </nav>
 <main class="body">
  <div id="td-pov" class="page on">
   <h1>Visão geral</h1><p class="sub">Taxas e preços atuais de todos os títulos</p>
   <div class="mg" id="td-ovm"></div>
   <div class="card"><h3>Taxas de compra atuais por título</h3><p class="desc">Comparativo da última data disponível</p><div class="cw"><canvas id="td-cc"></canvas></div><div class="lg" id="td-lgc"></div></div>
   <div class="sl">Clique em um título para ver o histórico</div>
   <div class="tg" id="td-tco"></div>
  </div>
  <div id="td-phi" class="page">
   <h1>Histórico por título</h1><p class="sub">Selecione um título abaixo</p>
   <div class="tg" id="td-tch"></div>
   <div id="td-hdd" style="display:none">
    <div class="mg" id="td-hm"></div>
    <div class="rng"><button onclick="tdSetR('6m')">6 meses</button><button onclick="tdSetR('1a')">1 ano</button><button class="on" onclick="tdSetR('2a')">2 anos</button><button onclick="tdSetR('max')">Máximo</button></div>
    <div class="card"><h3 id="td-htt">Taxa histórica</h3><p class="desc">% ao ano — taxa alta = preço baixo</p><div class="cw"><canvas id="td-ct"></canvas></div></div>
    <div class="card"><h3 id="td-hpt">PU de compra</h3><p class="desc">R$ — inversamente proporcional à taxa</p><div class="cw"><canvas id="td-cpu"></canvas></div></div>
   </div>
  </div>
  <div id="td-pre" class="page">
   <h1>Quando resgatar</h1><p class="sub">Guia prático + análise automática</p>
   <div id="td-rec"></div>
  </div>
  <div id="td-pma" class="page">
   <h1>Painel macro</h1><p class="sub">Indicadores · mai/2026 · Focus / BCB / IBGE / FMI</p>
   <div class="mg" style="grid-template-columns:repeat(auto-fit,minmax(125px,1fr))">
    <div class="mc"><div class="ml">Selic atual</div><div class="mv wn">14,75%</div><div class="ms">1.º corte pós-ciclo</div></div>
    <div class="mc"><div class="ml">Selic fim 2026</div><div class="mv">13,00%</div><div class="ms">projeção Focus</div></div>
    <div class="mc"><div class="ml">IPCA 12 meses</div><div class="mv wn">4,14%</div><div class="ms">abr/26 · meta 3%±1,5</div></div>
    <div class="mc"><div class="ml">IPCA proj. 2026</div><div class="mv dn">4,80%</div><div class="ms">acima do teto 4,5%</div></div>
    <div class="mc"><div class="ml">Dívida bruta/PIB</div><div class="mv dn">~79%</div><div class="ms">trajetória ascendente</div></div>
    <div class="mc"><div class="ml">Juro real</div><div class="mv up">~10,6%</div><div class="ms">2.º maior do mundo</div></div>
   </div>
   <div class="card"><h3>Sinais para o investidor</h3>
    <div class="sl">Política monetária</div>
    <div class="ir"><span class="in">Selic — ciclo de cortes iniciado</span><span class="iv">14,75%</span><span class="bg bg-am">Atenção</span></div>
    <div class="ir"><span class="in">Selic projetada dez/2026</span><span class="iv">13,00%</span><span class="bg bg-am">Corte gradual</span></div>
    <div class="ir"><span class="in">Selic projetada 2027</span><span class="iv">11,00%</span><span class="bg bg-gn">Queda contínua</span></div>
    <div class="sl">Inflação</div>
    <div class="ir"><span class="in">IPCA 12 meses (abr/26)</span><span class="iv">4,14%</span><span class="bg bg-am">Pressionado</span></div>
    <div class="ir"><span class="in">IPCA projetado 2026</span><span class="iv">4,80%</span><span class="bg bg-rd">Acima do teto</span></div>
    <div class="ir"><span class="in">Meta do Banco Central</span><span class="iv">3%±1,5</span><span class="bg bg-bl">Teto 4,5%</span></div>
    <div class="sl">Fiscal</div>
    <div class="ir"><span class="in">Dívida bruta / PIB (jan/26)</span><span class="iv">~79%</span><span class="bg bg-rd">Trajetória alta</span></div>
    <div class="ir"><span class="in">FMI: dívida projetada 2027</span><span class="iv">~100%</span><span class="bg bg-rd">Risco alto</span></div>
    <div class="ir"><span class="in">Juro real (Selic − IPCA)</span><span class="iv">~10,6%</span><span class="bg bg-gn">2.º maior mundo</span></div>
   </div>
   <div class="card"><h3>Leitura atual</h3><p class="desc">Selic a 14,75% com cortes graduais projetados, inflação acima do teto e juro real de ~10,6% — o 2.º maior do mundo. Ambiente muito favorável à renda fixa. Tesouro Selic garante retorno elevado com risco mínimo. IPCA+ oferece oportunidade histórica de travar taxa real alta. Prefixado tem apelo se acreditar que a Selic cairá mais do que o mercado projeta.</p></div>
  </div>
  <div id="td-pti" class="page">
   <h1>Qual título escolher</h1><p class="sub">Recomendações por perfil · mai/2026</p>
   <div class="pfb"><button class="on" onclick="tdSetP('c')">Conservador</button><button onclick="tdSetP('m')">Moderado</button><button onclick="tdSetP('a')">Arrojado</button></div>
   <div id="td-pfc"></div>
  </div>
  <div id="td-psi" class="page">
   <h1>Simulador</h1><p class="sub">Rentabilidade estimada líquida de IR</p>
   <div class="card">
    <div class="sg">
     <div class="sf"><label>Valor investido (R$)</label><input type="number" id="td-sv" value="10000" min="30" step="1000" oninput="tdSim()"></div>
     <div class="sf"><label>Prazo</label><input type="range" id="td-sp" min="1" max="20" value="5" step="1" oninput="tdSim()"><div class="sv2"><span id="td-spv">5</span> anos</div></div>
     <div class="sf"><label>IPCA médio projetado</label><input type="range" id="td-sipc" min="2" max="9" value="4.5" step="0.5" oninput="tdSim()"><div class="sv2"><span id="td-siv">4,5</span>% a.a.</div></div>
     <div class="sf"><label>Selic média projetada</label><input type="range" id="td-ssel" min="8" max="16" value="12" step="0.5" oninput="tdSim()"><div class="sv2"><span id="td-ssv">12,0</span>% a.a.</div></div>
    </div>
    <div class="mg" id="td-smm"></div>
    <div class="cw" style="height:240px;margin-top:10px"><canvas id="td-cs"></canvas></div>
    <div class="lg" id="td-slg"></div>
    <p style="font-size:10px;color:#aaa;margin-top:8px">IR regressivo (22,5% até 6m → 15% após 2 anos). Não inclui taxa de custódia B3 (0,2% a.a.). Simulação aproximada.</p>
   </div>
  </div>
 </main>
</div>
<td-footer>Tesouro Direto · Dados: <a href="https://www.tesourotransparente.gov.br" target="_blank">Tesouro Transparente</a></td-footer>
</div><!-- /mod-tesouro -->

<!-- ═══════════════════════════════════════
     MODAIS CJ
═══════════════════════════════════════ -->
<div class="cj-moverlay" id="cj-modal-overlay">
  <div class="cj-modal">
    <h3>📌 Incluir Valor / Rubrica</h3>
    <div class="cj-frow"><label class="cj-flabel">Data do fato gerador</label><input type="date" class="cj-input" id="cj-m-data"></div>
    <div class="cj-frow"><label class="cj-flabel">Descrição da rubrica</label><input type="text" class="cj-input" id="cj-m-desc" placeholder="Ex: Salários de jan/2020, Multa FGTS..."></div>
    <div class="cj-frow"><label class="cj-flabel">Tipo</label>
      <select class="cj-select" id="cj-m-tipo">
        <option value="D">Débito principal</option>
        <option value="C">Crédito / Dedução</option>
        <option value="H">Honorários periciais</option>
        <option value="C2">Custas processuais</option>
      </select>
    </div>
    <div class="cj-frow"><label class="cj-flabel">Valor original (R$)</label><input type="number" class="cj-input" id="cj-m-valor" placeholder="0,00" step="0.01" min="0"></div>
    <div class="cj-frow"><label class="cj-flabel">Observação (opcional)</label><input type="text" class="cj-input" id="cj-m-obs" placeholder="Referência, nota..."></div>
    <div class="cj-modal-btns">
      <button class="cj-btn-confirm" onclick="cjConfirmar()">Incluir</button>
      <button class="cj-btn-cancel" onclick="cjCloseModal()">Cancelar</button>
    </div>
  </div>
</div>

<div class="cj-moverlay" id="cj-memorial-overlay">
  <div class="cj-memorial-modal">
    <h3 style="font-size:15px;font-weight:600;color:#1e3a8a;margin-bottom:4px">📄 Memorial de Cálculo</h3>
    <p style="font-size:11px;color:#6b7280;margin-bottom:8px">Documento gerado automaticamente para juntada aos autos</p>
    <div class="cj-memorial-body" id="cj-memorial-body"></div>
    <div class="cj-memorial-btns">
      <button class="cj-btn-confirm" style="flex:1;padding:9px;border:none;border-radius:6px;cursor:pointer;font-size:12px;font-weight:600;background:#2563eb;color:#fff" onclick="cjCopiarMemorial()">📋 Copiar texto</button>
      <button class="cj-btn-cancel" style="flex:1;padding:9px;border:1px solid #d1d5db;border-radius:6px;cursor:pointer;font-size:12px;background:#fff;color:#6b7280" onclick="document.getElementById('cj-memorial-overlay').classList.remove('open')">Fechar</button>
    </div>
  </div>
</div>

<div id="cj-toast"></div>

<script>
// ══════════════════════════════════════════════════
// NAVEGAÇÃO GLOBAL
// ══════════════════════════════════════════════════
function switchModule(mod) {
  document.querySelectorAll('.module').forEach(m => m.classList.remove('active'));
  document.querySelectorAll('.topnav-tab').forEach(t => t.classList.remove('active'));
  document.getElementById('mod-' + mod).classList.add('active');
  document.getElementById('navtab-' + mod).classList.add('active');
}

// ══════════════════════════════════════════════════
// ÍNDICES HISTÓRICOS COMPLETOS 2000–2025
// ══════════════════════════════════════════════════
const CJ_IDX = {
"IPCA-E":{"2000-01":1.14,"2000-02":0.25,"2000-03":0.33,"2000-04":0.38,"2000-05":0.38,"2000-06":0.51,"2000-07":2.27,"2000-08":1.56,"2000-09":0.57,"2000-10":0.28,"2000-11":0.43,"2000-12":0.58,"2001-01":0.62,"2001-02":0.66,"2001-03":0.52,"2001-04":0.71,"2001-05":0.69,"2001-06":0.72,"2001-07":0.88,"2001-08":0.93,"2001-09":0.78,"2001-10":0.96,"2001-11":0.75,"2001-12":0.80,"2002-01":0.52,"2002-02":0.30,"2002-03":0.70,"2002-04":0.58,"2002-05":0.37,"2002-06":0.33,"2002-07":1.17,"2002-08":0.85,"2002-09":0.62,"2002-10":0.68,"2002-11":3.22,"2002-12":3.00,"2003-01":2.25,"2003-02":1.52,"2003-03":1.23,"2003-04":0.97,"2003-05":0.83,"2003-06":0.31,"2003-07":-0.04,"2003-08":0.34,"2003-09":0.53,"2003-10":0.43,"2003-11":0.51,"2003-12":0.52,"2004-01":0.68,"2004-02":0.72,"2004-03":0.44,"2004-04":0.37,"2004-05":0.51,"2004-06":0.75,"2004-07":0.91,"2004-08":0.69,"2004-09":0.49,"2004-10":0.44,"2004-11":0.69,"2004-12":0.86,"2005-01":0.62,"2005-02":0.59,"2005-03":0.61,"2005-04":0.87,"2005-05":0.49,"2005-06":0.27,"2005-07":0.25,"2005-08":0.18,"2005-09":0.35,"2005-10":0.75,"2005-11":0.55,"2005-12":0.36,"2006-01":0.57,"2006-02":0.40,"2006-03":0.43,"2006-04":-0.05,"2006-05":0.09,"2006-06":-0.16,"2006-07":0.15,"2006-08":0.07,"2006-09":0.13,"2006-10":0.33,"2006-11":0.44,"2006-12":0.48,"2007-01":0.58,"2007-02":0.44,"2007-03":0.36,"2007-04":0.25,"2007-05":0.29,"2007-06":0.31,"2007-07":0.35,"2007-08":0.36,"2007-09":0.30,"2007-10":0.44,"2007-11":0.62,"2007-12":0.74,"2008-01":0.76,"2008-02":0.80,"2008-03":0.49,"2008-04":0.55,"2008-05":0.88,"2008-06":1.07,"2008-07":0.83,"2008-08":0.43,"2008-09":0.26,"2008-10":0.45,"2008-11":0.36,"2008-12":0.28,"2009-01":0.72,"2009-02":0.91,"2009-03":0.33,"2009-04":0.48,"2009-05":0.36,"2009-06":-0.29,"2009-07":0.24,"2009-08":0.15,"2009-09":0.24,"2009-10":0.28,"2009-11":0.41,"2009-12":0.37,"2010-01":0.75,"2010-02":0.78,"2010-03":0.52,"2010-04":0.57,"2010-05":0.43,"2010-06":0.08,"2010-07":0.01,"2010-08":0.11,"2010-09":0.45,"2010-10":0.75,"2010-11":0.83,"2010-12":0.83,"2011-01":0.83,"2011-02":0.80,"2011-03":0.62,"2011-04":0.77,"2011-05":0.55,"2011-06":0.15,"2011-07":0.16,"2011-08":0.37,"2011-09":0.53,"2011-10":0.43,"2011-11":0.52,"2011-12":0.62,"2012-01":0.97,"2012-02":0.49,"2012-03":0.43,"2012-04":0.64,"2012-05":0.36,"2012-06":0.08,"2012-07":0.35,"2012-08":0.41,"2012-09":0.54,"2012-10":0.59,"2012-11":0.57,"2012-12":0.68,"2013-01":0.86,"2013-02":0.60,"2013-03":0.47,"2013-04":0.51,"2013-05":0.37,"2013-06":0.33,"2013-07":0.03,"2013-08":0.09,"2013-09":0.35,"2013-10":0.54,"2013-11":0.54,"2013-12":0.72,"2014-01":0.78,"2014-02":0.69,"2014-03":0.73,"2014-04":0.67,"2014-05":0.46,"2014-06":0.40,"2014-07":0.20,"2014-08":0.25,"2014-09":0.44,"2014-10":0.42,"2014-11":0.39,"2014-12":0.79,"2015-01":1.22,"2015-02":1.22,"2015-03":1.32,"2015-04":0.99,"2015-05":0.60,"2015-06":0.70,"2015-07":0.62,"2015-08":0.45,"2015-09":0.54,"2015-10":0.82,"2015-11":1.01,"2015-12":0.96,"2016-01":1.27,"2016-02":0.90,"2016-03":0.43,"2016-04":0.61,"2016-05":0.78,"2016-06":0.35,"2016-07":0.52,"2016-08":0.44,"2016-09":0.08,"2016-10":0.26,"2016-11":0.18,"2016-12":0.34,"2017-01":0.54,"2017-02":0.27,"2017-03":0.25,"2017-04":0.14,"2017-05":-0.01,"2017-06":-0.23,"2017-07":0.24,"2017-08":0.19,"2017-09":0.16,"2017-10":0.42,"2017-11":0.28,"2017-12":0.44,"2018-01":0.30,"2018-02":0.32,"2018-03":0.09,"2018-04":0.22,"2018-05":0.40,"2018-06":1.11,"2018-07":0.20,"2018-08":0.09,"2018-09":0.48,"2018-10":0.45,"2018-11":-0.21,"2018-12":0.14,"2019-01":0.98,"2019-02":0.53,"2019-03":0.93,"2019-04":0.57,"2019-05":0.13,"2019-06":0.01,"2019-07":0.19,"2019-08":0.11,"2019-09":0.43,"2019-10":0.28,"2019-11":0.51,"2019-12":1.22,"2020-01":0.56,"2020-02":0.28,"2020-03":-0.07,"2020-04":-0.31,"2020-05":-0.38,"2020-06":0.26,"2020-07":0.58,"2020-08":0.67,"2020-09":0.94,"2020-10":0.83,"2020-11":0.78,"2020-12":1.35,"2021-01":0.78,"2021-02":0.97,"2021-03":0.93,"2021-04":0.31,"2021-05":0.44,"2021-06":0.72,"2021-07":0.96,"2021-08":0.89,"2021-09":1.17,"2021-10":1.20,"2021-11":0.95,"2021-12":0.78,"2022-01":0.54,"2022-02":1.25,"2022-03":1.62,"2022-04":1.06,"2022-05":0.59,"2022-06":1.19,"2022-07":0.13,"2022-08":-0.02,"2022-09":0.59,"2022-10":0.59,"2022-11":0.53,"2022-12":0.54,"2023-01":0.38,"2023-02":0.84,"2023-03":0.71,"2023-04":0.60,"2023-05":0.23,"2023-06":0.00,"2023-07":0.07,"2023-08":0.28,"2023-09":0.26,"2023-10":0.24,"2023-11":0.33,"2023-12":0.71,"2024-01":0.42,"2024-02":0.78,"2024-03":0.36,"2024-04":0.69,"2024-05":0.44,"2024-06":0.39,"2024-07":0.30,"2024-08":0.44,"2024-09":0.44,"2024-10":0.56,"2024-11":0.39,"2024-12":0.43,"2025-01":0.53,"2025-02":1.23,"2025-03":0.64,"2025-04":0.43},
"INPC":{"2000-01":0.69,"2000-02":0.24,"2000-03":0.25,"2000-04":0.46,"2000-05":0.40,"2000-06":0.34,"2000-07":1.61,"2000-08":1.62,"2000-09":0.72,"2000-10":0.34,"2000-11":0.43,"2000-12":0.56,"2001-01":0.52,"2001-02":0.57,"2001-03":0.52,"2001-04":0.80,"2001-05":0.77,"2001-06":0.97,"2001-07":1.24,"2001-08":0.98,"2001-09":0.88,"2001-10":1.38,"2001-11":0.95,"2001-12":0.80,"2002-01":0.53,"2002-02":0.25,"2002-03":0.77,"2002-04":0.74,"2002-05":0.52,"2002-06":0.44,"2002-07":1.36,"2002-08":0.81,"2002-09":0.82,"2002-10":1.32,"2002-11":3.68,"2002-12":3.63,"2003-01":2.69,"2003-02":1.83,"2003-03":1.23,"2003-04":0.65,"2003-05":0.63,"2003-06":0.25,"2003-07":-0.22,"2003-08":0.19,"2003-09":0.50,"2003-10":0.30,"2003-11":0.41,"2003-12":0.55,"2004-01":0.77,"2004-02":0.89,"2004-03":0.62,"2004-04":0.46,"2004-05":0.60,"2004-06":0.83,"2004-07":0.91,"2004-08":0.75,"2004-09":0.41,"2004-10":0.38,"2004-11":0.70,"2004-12":0.86,"2005-01":0.64,"2005-02":0.65,"2005-03":0.58,"2005-04":0.95,"2005-05":0.57,"2005-06":0.31,"2005-07":0.27,"2005-08":0.27,"2005-09":0.34,"2005-10":0.77,"2005-11":0.59,"2005-12":0.36,"2006-01":0.48,"2006-02":0.42,"2006-03":0.46,"2006-04":-0.01,"2006-05":0.02,"2006-06":-0.16,"2006-07":0.06,"2006-08":0.12,"2006-09":0.25,"2006-10":0.40,"2006-11":0.51,"2006-12":0.44,"2007-01":0.44,"2007-02":0.33,"2007-03":0.37,"2007-04":0.20,"2007-05":0.24,"2007-06":0.31,"2007-07":0.30,"2007-08":0.39,"2007-09":0.32,"2007-10":0.52,"2007-11":0.65,"2007-12":0.79,"2008-01":0.86,"2008-02":0.72,"2008-03":0.52,"2008-04":0.51,"2008-05":0.87,"2008-06":1.07,"2008-07":0.89,"2008-08":0.42,"2008-09":0.40,"2008-10":0.50,"2008-11":0.44,"2008-12":0.38,"2009-01":0.66,"2009-02":0.75,"2009-03":0.34,"2009-04":0.47,"2009-05":0.41,"2009-06":-0.18,"2009-07":0.22,"2009-08":0.15,"2009-09":0.21,"2009-10":0.28,"2009-11":0.41,"2009-12":0.30,"2010-01":0.63,"2010-02":0.66,"2010-03":0.62,"2010-04":0.58,"2010-05":0.49,"2010-06":0.08,"2010-07":-0.13,"2010-08":0.08,"2010-09":0.49,"2010-10":0.74,"2010-11":0.81,"2010-12":0.81,"2011-01":0.83,"2011-02":0.82,"2011-03":0.65,"2011-04":0.75,"2011-05":0.60,"2011-06":0.17,"2011-07":0.18,"2011-08":0.38,"2011-09":0.54,"2011-10":0.43,"2011-11":0.52,"2011-12":0.60,"2012-01":0.90,"2012-02":0.44,"2012-03":0.43,"2012-04":0.64,"2012-05":0.50,"2012-06":0.10,"2012-07":0.37,"2012-08":0.41,"2012-09":0.63,"2012-10":0.75,"2012-11":0.57,"2012-12":0.78,"2013-01":0.81,"2013-02":0.58,"2013-03":0.57,"2013-04":0.57,"2013-05":0.33,"2013-06":0.35,"2013-07":0.03,"2013-08":0.10,"2013-09":0.28,"2013-10":0.62,"2013-11":0.57,"2013-12":0.63,"2014-01":0.74,"2014-02":0.71,"2014-03":0.92,"2014-04":0.67,"2014-05":0.46,"2014-06":0.40,"2014-07":0.17,"2014-08":0.24,"2014-09":0.44,"2014-10":0.42,"2014-11":0.41,"2014-12":0.77,"2015-01":1.07,"2015-02":1.22,"2015-03":1.30,"2015-04":1.01,"2015-05":0.71,"2015-06":0.73,"2015-07":0.61,"2015-08":0.59,"2015-09":0.77,"2015-10":0.88,"2015-11":1.05,"2015-12":0.96,"2016-01":1.36,"2016-02":1.00,"2016-03":0.50,"2016-04":0.74,"2016-05":0.75,"2016-06":0.50,"2016-07":0.52,"2016-08":0.44,"2016-09":0.06,"2016-10":0.24,"2016-11":0.17,"2016-12":0.29,"2017-01":0.42,"2017-02":0.24,"2017-03":0.18,"2017-04":0.18,"2017-05":-0.02,"2017-06":-0.24,"2017-07":0.10,"2017-08":0.20,"2017-09":0.12,"2017-10":0.42,"2017-11":0.30,"2017-12":0.45,"2018-01":0.25,"2018-02":0.27,"2018-03":0.06,"2018-04":0.19,"2018-05":0.30,"2018-06":1.23,"2018-07":0.25,"2018-08":0.09,"2018-09":0.47,"2018-10":0.50,"2018-11":-0.41,"2018-12":0.13,"2019-01":0.32,"2019-02":0.55,"2019-03":0.93,"2019-04":0.70,"2019-05":0.35,"2019-06":0.09,"2019-07":0.18,"2019-08":0.11,"2019-09":0.40,"2019-10":0.22,"2019-11":0.49,"2019-12":1.39,"2020-01":0.48,"2020-02":0.22,"2020-03":-0.14,"2020-04":-0.50,"2020-05":-0.26,"2020-06":0.19,"2020-07":1.20,"2020-08":0.78,"2020-09":0.86,"2020-10":0.78,"2020-11":0.75,"2020-12":1.38,"2021-01":0.64,"2021-02":0.72,"2021-03":0.93,"2021-04":0.31,"2021-05":0.44,"2021-06":0.60,"2021-07":0.96,"2021-08":0.89,"2021-09":1.17,"2021-10":1.25,"2021-11":0.95,"2021-12":0.73,"2022-01":0.59,"2022-02":1.16,"2022-03":1.74,"2022-04":1.24,"2022-05":0.59,"2022-06":0.47,"2022-07":0.07,"2022-08":-0.09,"2022-09":0.62,"2022-10":0.57,"2022-11":0.52,"2022-12":0.53,"2023-01":0.37,"2023-02":0.84,"2023-03":0.75,"2023-04":0.64,"2023-05":0.21,"2023-06":-0.01,"2023-07":0.05,"2023-08":0.31,"2023-09":0.26,"2023-10":0.26,"2023-11":0.34,"2023-12":0.73,"2024-01":0.42,"2024-02":0.83,"2024-03":0.39,"2024-04":0.72,"2024-05":0.47,"2024-06":0.41,"2024-07":0.32,"2024-08":0.47,"2024-09":0.45,"2024-10":0.56,"2024-11":0.39,"2024-12":0.45,"2025-01":0.54,"2025-02":1.31,"2025-03":0.65,"2025-04":0.45},
"IPCA":{"2000-01":0.62,"2000-02":0.13,"2000-03":0.22,"2000-04":0.42,"2000-05":0.01,"2000-06":0.23,"2000-07":1.61,"2000-08":1.31,"2000-09":0.75,"2000-10":0.14,"2000-11":0.32,"2000-12":0.59,"2001-01":0.67,"2001-02":0.46,"2001-03":0.38,"2001-04":0.64,"2001-05":0.55,"2001-06":0.52,"2001-07":1.33,"2001-08":0.70,"2001-09":0.72,"2001-10":1.03,"2001-11":0.71,"2001-12":0.67,"2002-01":0.52,"2002-02":0.36,"2002-03":0.60,"2002-04":0.61,"2002-05":0.21,"2002-06":0.42,"2002-07":1.19,"2002-08":0.65,"2002-09":0.72,"2002-10":1.31,"2002-11":3.02,"2002-12":2.10,"2003-01":2.25,"2003-02":1.57,"2003-03":1.23,"2003-04":0.97,"2003-05":0.61,"2003-06":-0.15,"2003-07":-0.10,"2003-08":0.34,"2003-09":0.78,"2003-10":0.29,"2003-11":0.54,"2003-12":0.52,"2004-01":0.76,"2004-02":0.69,"2004-03":0.47,"2004-04":0.37,"2004-05":0.51,"2004-06":0.71,"2004-07":0.91,"2004-08":0.69,"2004-09":0.44,"2004-10":0.44,"2004-11":0.69,"2004-12":0.86,"2005-01":0.58,"2005-02":0.59,"2005-03":0.61,"2005-04":0.87,"2005-05":0.49,"2005-06":0.04,"2005-07":0.25,"2005-08":0.17,"2005-09":0.35,"2005-10":0.75,"2005-11":0.55,"2005-12":0.36,"2006-01":0.59,"2006-02":0.41,"2006-03":0.43,"2006-04":-0.21,"2006-05":0.10,"2006-06":-0.21,"2006-07":0.19,"2006-08":0.05,"2006-09":0.21,"2006-10":0.33,"2006-11":0.31,"2006-12":0.48,"2007-01":0.44,"2007-02":0.44,"2007-03":0.37,"2007-04":0.25,"2007-05":0.28,"2007-06":0.28,"2007-07":0.24,"2007-08":0.47,"2007-09":0.18,"2007-10":0.30,"2007-11":0.38,"2007-12":0.74,"2008-01":0.74,"2008-02":0.49,"2008-03":0.48,"2008-04":0.55,"2008-05":0.79,"2008-06":0.74,"2008-07":0.53,"2008-08":0.28,"2008-09":0.26,"2008-10":0.45,"2008-11":0.36,"2008-12":0.28,"2009-01":0.48,"2009-02":0.55,"2009-03":0.20,"2009-04":0.48,"2009-05":0.47,"2009-06":-0.39,"2009-07":0.24,"2009-08":0.15,"2009-09":0.24,"2009-10":0.28,"2009-11":0.41,"2009-12":0.37,"2010-01":0.75,"2010-02":0.78,"2010-03":0.52,"2010-04":0.57,"2010-05":0.43,"2010-06":0.00,"2010-07":0.01,"2010-08":0.04,"2010-09":0.45,"2010-10":0.75,"2010-11":0.83,"2010-12":0.63,"2011-01":0.83,"2011-02":0.80,"2011-03":0.79,"2011-04":0.77,"2011-05":0.47,"2011-06":0.15,"2011-07":0.16,"2011-08":0.37,"2011-09":0.53,"2011-10":0.43,"2011-11":0.52,"2011-12":0.50,"2012-01":0.97,"2012-02":0.45,"2012-03":0.21,"2012-04":0.64,"2012-05":0.36,"2012-06":0.08,"2012-07":0.43,"2012-08":0.41,"2012-09":0.57,"2012-10":0.59,"2012-11":0.60,"2012-12":0.79,"2013-01":0.86,"2013-02":0.60,"2013-03":0.47,"2013-04":0.55,"2013-05":0.37,"2013-06":0.26,"2013-07":0.03,"2013-08":0.24,"2013-09":0.35,"2013-10":0.54,"2013-11":0.54,"2013-12":0.92,"2014-01":0.55,"2014-02":0.69,"2014-03":0.92,"2014-04":0.67,"2014-05":0.46,"2014-06":0.40,"2014-07":0.01,"2014-08":0.25,"2014-09":0.44,"2014-10":0.42,"2014-11":0.51,"2014-12":0.78,"2015-01":1.24,"2015-02":1.22,"2015-03":1.32,"2015-04":0.99,"2015-05":0.60,"2015-06":0.79,"2015-07":0.62,"2015-08":0.22,"2015-09":0.54,"2015-10":0.82,"2015-11":1.01,"2015-12":0.96,"2016-01":1.27,"2016-02":0.90,"2016-03":0.43,"2016-04":0.61,"2016-05":0.78,"2016-06":0.35,"2016-07":0.52,"2016-08":0.44,"2016-09":0.08,"2016-10":0.26,"2016-11":0.18,"2016-12":0.30,"2017-01":0.38,"2017-02":0.33,"2017-03":0.25,"2017-04":0.14,"2017-05":-0.93,"2017-06":-0.23,"2017-07":0.24,"2017-08":0.19,"2017-09":0.16,"2017-10":0.42,"2017-11":0.28,"2017-12":0.44,"2018-01":0.29,"2018-02":0.32,"2018-03":0.09,"2018-04":0.22,"2018-05":0.40,"2018-06":1.26,"2018-07":0.33,"2018-08":-0.09,"2018-09":0.48,"2018-10":0.45,"2018-11":-0.21,"2018-12":0.15,"2019-01":0.32,"2019-02":0.43,"2019-03":0.75,"2019-04":0.57,"2019-05":0.13,"2019-06":0.01,"2019-07":0.19,"2019-08":0.11,"2019-09":0.43,"2019-10":0.28,"2019-11":0.51,"2019-12":1.15,"2020-01":0.21,"2020-02":0.25,"2020-03":-0.07,"2020-04":-0.31,"2020-05":-0.38,"2020-06":0.26,"2020-07":0.36,"2020-08":0.24,"2020-09":0.64,"2020-10":0.86,"2020-11":0.89,"2020-12":1.35,"2021-01":0.25,"2021-02":0.86,"2021-03":0.93,"2021-04":0.31,"2021-05":0.83,"2021-06":0.53,"2021-07":0.96,"2021-08":0.87,"2021-09":1.16,"2021-10":1.25,"2021-11":0.95,"2021-12":0.73,"2022-01":0.54,"2022-02":1.01,"2022-03":1.62,"2022-04":1.06,"2022-05":0.47,"2022-06":0.67,"2022-07":-0.68,"2022-08":-0.02,"2022-09":0.59,"2022-10":0.59,"2022-11":0.41,"2022-12":0.54,"2023-01":0.53,"2023-02":0.84,"2023-03":0.71,"2023-04":0.61,"2023-05":0.23,"2023-06":-0.08,"2023-07":0.12,"2023-08":0.23,"2023-09":0.26,"2023-10":0.24,"2023-11":0.28,"2023-12":0.62,"2024-01":0.42,"2024-02":0.83,"2024-03":0.16,"2024-04":0.38,"2024-05":0.46,"2024-06":0.20,"2024-07":0.38,"2024-08":0.44,"2024-09":0.44,"2024-10":0.56,"2024-11":0.39,"2024-12":0.52,"2025-01":0.16,"2025-02":1.31,"2025-03":0.56,"2025-04":0.43},
"SELIC":{"2000-01":1.46,"2000-02":1.38,"2000-03":1.45,"2000-04":1.35,"2000-05":1.47,"2000-06":1.34,"2000-07":1.31,"2000-08":1.36,"2000-09":1.21,"2000-10":1.26,"2000-11":1.19,"2000-12":1.20,"2001-01":1.27,"2001-02":1.02,"2001-03":1.26,"2001-04":1.19,"2001-05":1.34,"2001-06":1.27,"2001-07":1.50,"2001-08":1.56,"2001-09":1.32,"2001-10":1.53,"2001-11":1.38,"2001-12":1.39,"2002-01":1.53,"2002-02":1.14,"2002-03":1.37,"2002-04":1.48,"2002-05":1.40,"2002-06":1.27,"2002-07":1.54,"2002-08":1.41,"2002-09":1.36,"2002-10":1.67,"2002-11":1.62,"2002-12":2.25,"2003-01":1.97,"2003-02":1.84,"2003-03":1.78,"2003-04":1.87,"2003-05":1.97,"2003-06":1.86,"2003-07":2.09,"2003-08":1.77,"2003-09":1.68,"2003-10":1.64,"2003-11":1.34,"2003-12":1.37,"2004-01":1.27,"2004-02":1.07,"2004-03":1.38,"2004-04":1.18,"2004-05":1.23,"2004-06":1.23,"2004-07":1.30,"2004-08":1.30,"2004-09":1.36,"2004-10":1.37,"2004-11":1.21,"2004-12":1.49,"2005-01":1.38,"2005-02":1.22,"2005-03":1.53,"2005-04":1.41,"2005-05":1.50,"2005-06":1.61,"2005-07":1.52,"2005-08":1.66,"2005-09":1.50,"2005-10":1.41,"2005-11":1.38,"2005-12":1.47,"2006-01":1.43,"2006-02":1.15,"2006-03":1.42,"2006-04":1.08,"2006-05":1.28,"2006-06":1.18,"2006-07":1.17,"2006-08":1.26,"2006-09":1.06,"2006-10":1.09,"2006-11":1.02,"2006-12":0.99,"2007-01":1.08,"2007-02":0.87,"2007-03":1.05,"2007-04":0.94,"2007-05":1.03,"2007-06":0.91,"2007-07":0.97,"2007-08":0.99,"2007-09":0.89,"2007-10":0.93,"2007-11":0.84,"2007-12":0.84,"2008-01":0.93,"2008-02":0.80,"2008-03":0.84,"2008-04":0.90,"2008-05":0.88,"2008-06":0.96,"2008-07":1.07,"2008-08":1.02,"2008-09":1.10,"2008-10":1.18,"2008-11":1.02,"2008-12":1.12,"2009-01":1.05,"2009-02":0.86,"2009-03":0.97,"2009-04":0.84,"2009-05":0.77,"2009-06":0.76,"2009-07":0.79,"2009-08":0.69,"2009-09":0.69,"2009-10":0.69,"2009-11":0.66,"2009-12":0.73,"2010-01":0.66,"2010-02":0.59,"2010-03":0.76,"2010-04":0.67,"2010-05":0.75,"2010-06":0.79,"2010-07":0.86,"2010-08":0.89,"2010-09":0.85,"2010-10":0.81,"2010-11":0.81,"2010-12":0.93,"2011-01":0.86,"2011-02":0.84,"2011-03":0.92,"2011-04":0.84,"2011-05":0.99,"2011-06":0.96,"2011-07":0.97,"2011-08":1.07,"2011-09":0.94,"2011-10":0.88,"2011-11":0.86,"2011-12":0.91,"2012-01":0.89,"2012-02":0.75,"2012-03":0.82,"2012-04":0.71,"2012-05":0.74,"2012-06":0.64,"2012-07":0.68,"2012-08":0.69,"2012-09":0.54,"2012-10":0.61,"2012-11":0.55,"2012-12":0.55,"2013-01":0.60,"2013-02":0.49,"2013-03":0.55,"2013-04":0.61,"2013-05":0.60,"2013-06":0.61,"2013-07":0.72,"2013-08":0.71,"2013-09":0.71,"2013-10":0.81,"2013-11":0.72,"2013-12":0.79,"2014-01":0.85,"2014-02":0.78,"2014-03":0.77,"2014-04":0.82,"2014-05":0.87,"2014-06":0.82,"2014-07":0.95,"2014-08":0.87,"2014-09":0.91,"2014-10":0.95,"2014-11":0.84,"2014-12":0.96,"2015-01":0.93,"2015-02":0.82,"2015-03":1.04,"2015-04":0.95,"2015-05":0.99,"2015-06":1.07,"2015-07":1.18,"2015-08":1.11,"2015-09":1.11,"2015-10":1.11,"2015-11":1.06,"2015-12":1.16,"2016-01":1.06,"2016-02":1.00,"2016-03":1.16,"2016-04":0.97,"2016-05":1.11,"2016-06":1.16,"2016-07":1.11,"2016-08":1.22,"2016-09":1.11,"2016-10":1.05,"2016-11":1.04,"2016-12":1.12,"2017-01":1.09,"2017-02":0.87,"2017-03":1.05,"2017-04":0.79,"2017-05":0.93,"2017-06":0.81,"2017-07":0.80,"2017-08":0.80,"2017-09":0.64,"2017-10":0.64,"2017-11":0.57,"2017-12":0.54,"2018-01":0.58,"2018-02":0.47,"2018-03":0.53,"2018-04":0.52,"2018-05":0.52,"2018-06":0.52,"2018-07":0.53,"2018-08":0.57,"2018-09":0.47,"2018-10":0.54,"2018-11":0.49,"2018-12":0.49,"2019-01":0.49,"2019-02":0.49,"2019-03":0.47,"2019-04":0.52,"2019-05":0.54,"2019-06":0.47,"2019-07":0.57,"2019-08":0.50,"2019-09":0.46,"2019-10":0.48,"2019-11":0.38,"2019-12":0.37,"2020-01":0.38,"2020-02":0.29,"2020-03":0.34,"2020-04":0.28,"2020-05":0.24,"2020-06":0.21,"2020-07":0.19,"2020-08":0.16,"2020-09":0.16,"2020-10":0.16,"2020-11":0.15,"2020-12":0.16,"2021-01":0.15,"2021-02":0.15,"2021-03":0.20,"2021-04":0.25,"2021-05":0.27,"2021-06":0.29,"2021-07":0.34,"2021-08":0.43,"2021-09":0.44,"2021-10":0.49,"2021-11":0.59,"2021-12":0.77,"2022-01":0.73,"2022-02":0.76,"2022-03":0.83,"2022-04":0.83,"2022-05":1.03,"2022-06":1.07,"2022-07":1.07,"2022-08":1.07,"2022-09":1.07,"2022-10":1.07,"2022-11":1.07,"2022-12":1.12,"2023-01":1.12,"2023-02":0.95,"2023-03":0.83,"2023-04":0.83,"2023-05":0.81,"2023-06":0.81,"2023-07":0.79,"2023-08":0.91,"2023-09":0.83,"2023-10":0.82,"2023-11":0.92,"2023-12":0.97,"2024-01":0.97,"2024-02":0.80,"2024-03":0.83,"2024-04":0.83,"2024-05":0.83,"2024-06":0.80,"2024-07":0.89,"2024-08":0.89,"2024-09":0.90,"2024-10":0.93,"2024-11":1.00,"2024-12":1.07,"2025-01":1.07,"2025-02":1.04,"2025-03":1.07,"2025-04":1.00},
"POUPANCA":{"2000-01":0.60,"2000-02":0.60,"2000-03":0.60,"2000-04":0.60,"2000-05":0.60,"2000-06":0.60,"2000-07":0.60,"2000-08":0.60,"2000-09":0.60,"2000-10":0.60,"2000-11":0.60,"2000-12":0.60,"2001-01":0.60,"2001-02":0.60,"2001-03":0.60,"2001-04":0.60,"2001-05":0.60,"2001-06":0.60,"2001-07":0.60,"2001-08":0.60,"2001-09":0.60,"2001-10":0.60,"2001-11":0.60,"2001-12":0.60,"2002-01":0.60,"2002-02":0.60,"2002-03":0.60,"2002-04":0.60,"2002-05":0.60,"2002-06":0.60,"2002-07":0.60,"2002-08":0.60,"2002-09":0.60,"2002-10":0.60,"2002-11":0.60,"2002-12":0.60,"2003-01":0.60,"2003-02":0.60,"2003-03":0.60,"2003-04":0.60,"2003-05":0.60,"2003-06":0.60,"2003-07":0.60,"2003-08":0.60,"2003-09":0.60,"2003-10":0.60,"2003-11":0.60,"2003-12":0.60,"2004-01":0.60,"2004-02":0.60,"2004-03":0.60,"2004-04":0.60,"2004-05":0.60,"2004-06":0.60,"2004-07":0.60,"2004-08":0.60,"2004-09":0.60,"2004-10":0.60,"2004-11":0.60,"2004-12":0.60,"2005-01":0.60,"2005-02":0.60,"2005-03":0.60,"2005-04":0.60,"2005-05":0.60,"2005-06":0.60,"2005-07":0.60,"2005-08":0.60,"2005-09":0.60,"2005-10":0.60,"2005-11":0.60,"2005-12":0.60,"2006-01":0.60,"2006-02":0.60,"2006-03":0.60,"2006-04":0.60,"2006-05":0.60,"2006-06":0.60,"2006-07":0.60,"2006-08":0.60,"2006-09":0.60,"2006-10":0.60,"2006-11":0.60,"2006-12":0.60,"2007-01":0.60,"2007-02":0.60,"2007-03":0.60,"2007-04":0.60,"2007-05":0.60,"2007-06":0.60,"2007-07":0.60,"2007-08":0.60,"2007-09":0.60,"2007-10":0.60,"2007-11":0.60,"2007-12":0.60,"2008-01":0.60,"2008-02":0.60,"2008-03":0.60,"2008-04":0.60,"2008-05":0.60,"2008-06":0.60,"2008-07":0.60,"2008-08":0.60,"2008-09":0.60,"2008-10":0.60,"2008-11":0.60,"2008-12":0.60,"2009-01":0.60,"2009-02":0.60,"2009-03":0.60,"2009-04":0.60,"2009-05":0.60,"2009-06":0.60,"2009-07":0.60,"2009-08":0.60,"2009-09":0.60,"2009-10":0.60,"2009-11":0.60,"2009-12":0.60,"2010-01":0.60,"2010-02":0.60,"2010-03":0.60,"2010-04":0.60,"2010-05":0.60,"2010-06":0.60,"2010-07":0.60,"2010-08":0.60,"2010-09":0.60,"2010-10":0.60,"2010-11":0.60,"2010-12":0.60,"2011-01":0.60,"2011-02":0.60,"2011-03":0.60,"2011-04":0.60,"2011-05":0.60,"2011-06":0.60,"2011-07":0.60,"2011-08":0.60,"2011-09":0.60,"2011-10":0.60,"2011-11":0.60,"2011-12":0.60,"2012-01":0.60,"2012-02":0.60,"2012-03":0.60,"2012-04":0.60,"2012-05":0.60,"2012-06":0.50,"2012-07":0.47,"2012-08":0.47,"2012-09":0.47,"2012-10":0.47,"2012-11":0.47,"2012-12":0.47,"2013-01":0.47,"2013-02":0.47,"2013-03":0.47,"2013-04":0.47,"2013-05":0.47,"2013-06":0.47,"2013-07":0.47,"2013-08":0.47,"2013-09":0.47,"2013-10":0.47,"2013-11":0.47,"2013-12":0.47,"2014-01":0.47,"2014-02":0.47,"2014-03":0.47,"2014-04":0.47,"2014-05":0.47,"2014-06":0.47,"2014-07":0.47,"2014-08":0.47,"2014-09":0.47,"2014-10":0.47,"2014-11":0.47,"2014-12":0.47,"2015-01":0.47,"2015-02":0.47,"2015-03":0.47,"2015-04":0.47,"2015-05":0.47,"2015-06":0.47,"2015-07":0.47,"2015-08":0.47,"2015-09":0.47,"2015-10":0.47,"2015-11":0.47,"2015-12":0.47,"2016-01":0.47,"2016-02":0.47,"2016-03":0.47,"2016-04":0.47,"2016-05":0.47,"2016-06":0.47,"2016-07":0.47,"2016-08":0.47,"2016-09":0.47,"2016-10":0.47,"2016-11":0.47,"2016-12":0.47,"2017-01":0.47,"2017-02":0.47,"2017-03":0.47,"2017-04":0.47,"2017-05":0.47,"2017-06":0.47,"2017-07":0.47,"2017-08":0.47,"2017-09":0.47,"2017-10":0.47,"2017-11":0.47,"2017-12":0.47,"2018-01":0.47,"2018-02":0.47,"2018-03":0.47,"2018-04":0.47,"2018-05":0.47,"2018-06":0.47,"2018-07":0.47,"2018-08":0.47,"2018-09":0.47,"2018-10":0.47,"2018-11":0.47,"2018-12":0.47,"2019-01":0.37,"2019-02":0.37,"2019-03":0.37,"2019-04":0.37,"2019-05":0.37,"2019-06":0.37,"2019-07":0.37,"2019-08":0.37,"2019-09":0.37,"2019-10":0.37,"2019-11":0.37,"2019-12":0.37,"2020-01":0.37,"2020-02":0.29,"2020-03":0.26,"2020-04":0.21,"2020-05":0.18,"2020-06":0.16,"2020-07":0.16,"2020-08":0.16,"2020-09":0.16,"2020-10":0.16,"2020-11":0.16,"2020-12":0.16,"2021-01":0.16,"2021-02":0.16,"2021-03":0.16,"2021-04":0.16,"2021-05":0.16,"2021-06":0.16,"2021-07":0.16,"2021-08":0.16,"2021-09":0.16,"2021-10":0.16,"2021-11":0.16,"2021-12":0.41,"2022-01":0.56,"2022-02":0.56,"2022-03":0.71,"2022-04":0.74,"2022-05":0.74,"2022-06":0.74,"2022-07":0.74,"2022-08":0.74,"2022-09":0.74,"2022-10":0.74,"2022-11":0.74,"2022-12":0.74,"2023-01":0.74,"2023-02":0.74,"2023-03":0.74,"2023-04":0.74,"2023-05":0.74,"2023-06":0.74,"2023-07":0.61,"2023-08":0.61,"2023-09":0.61,"2023-10":0.61,"2023-11":0.61,"2023-12":0.61,"2024-01":0.61,"2024-02":0.61,"2024-03":0.61,"2024-04":0.61,"2024-05":0.61,"2024-06":0.61,"2024-07":0.61,"2024-08":0.61,"2024-09":0.61,"2024-10":0.61,"2024-11":0.61,"2024-12":0.61,"2025-01":0.74,"2025-02":0.74,"2025-03":0.74,"2025-04":0.74}
};

// ══════════════════════════════════════════════════
// CALCULADORA JUDICIAL — LÓGICA
// ══════════════════════════════════════════════════
let cjRubricas=[],cjSelIdx=-1,cjTabCount=1,cjUltimoCalc=null;
const cjFmt=v=>new Intl.NumberFormat('pt-BR',{style:'currency',currency:'BRL'}).format(v);
const cjHoje=()=>new Date().toISOString().slice(0,10);
const cjPtDate=s=>s?new Date(s+'T12:00').toLocaleDateString('pt-BR'):'—';
const cjYm=s=>s?s.slice(0,7):'';

function cjAcumulado(idx,de,ate){
  const t=CJ_IDX[idx]||CJ_IDX["IPCA-E"];
  let d=new Date(de+'-01'),f=new Date(ate+'-01'),r=1;
  while(d<=f){const k=d.toISOString().slice(0,7);r*=(1+(t[k]||0)/100);d.setMonth(d.getMonth()+1);}
  return r-1;
}

function cjTogglePanel(btn){btn.classList.toggle('open');btn.nextElementSibling.classList.toggle('open');btn.classList.toggle('active',btn.classList.contains('open'));}
function cjSwitchCrit(btn){document.querySelectorAll('.cj-ctab').forEach(b=>b.classList.remove('active'));btn.classList.add('active');}
function cjSetCorrMode(r){document.getElementById('cj-corr-tabela').style.display=r.value==='tabela'?'':'none';document.getElementById('cj-corr-taxa').style.display=r.value==='taxa'?'':'none';}
function cjSetJurosMode(r){document.getElementById('cj-juros-tabela').style.display=r.value==='tabela'?'':'none';document.getElementById('cj-juros-taxa').style.display=r.value==='taxa'?'':'none';}

function cjOpenModal(){
  document.getElementById('cj-m-data').value=cjHoje();
  document.getElementById('cj-m-desc').value='';
  document.getElementById('cj-m-valor').value='';
  document.getElementById('cj-m-obs').value='';
  document.getElementById('cj-m-tipo').value='D';
  document.getElementById('cj-modal-overlay').classList.add('open');
  setTimeout(()=>document.getElementById('cj-m-desc').focus(),100);
}
function cjCloseModal(){document.getElementById('cj-modal-overlay').classList.remove('open');}
function cjConfirmar(){
  const data=document.getElementById('cj-m-data').value,desc=document.getElementById('cj-m-desc').value.trim()||'Rubrica '+(cjRubricas.length+1),tipo=document.getElementById('cj-m-tipo').value,valor=parseFloat(document.getElementById('cj-m-valor').value)||0,obs=document.getElementById('cj-m-obs').value.trim();
  if(valor<=0&&tipo!=='C'){alert('Informe um valor maior que zero.');return;}
  cjRubricas.push({data,desc,tipo,valor,obs,id:Date.now()});
  cjCloseModal();cjRenderTabela();cjToast('Rubrica incluída com sucesso.');
}

const cjTipoLabel={D:'Débito',C:'Crédito',H:'Honorários',C2:'Custas'};
function cjRenderTabela(){
  const tb=document.getElementById('cj-tbody'),em=document.getElementById('cj-empty');
  if(!cjRubricas.length){em.style.display='block';tb.innerHTML='';tb.appendChild(em);return;}
  em.style.display='none';
  tb.innerHTML=cjRubricas.map((r,i)=>{
    const m=r.tipo==='C'?-1:1;
    return `<div class="cj-row${i===cjSelIdx?' sel':''}" onclick="cjSel(${i})">
      <span>${cjPtDate(r.data)}</span>
      <span><span class="cj-row-desc">${r.desc}</span>${r.obs?`<div class="cj-row-obs">${r.obs}</div>`:''}</span>
      <span><span class="cj-badge cj-badge-${r.tipo}">${cjTipoLabel[r.tipo]||r.tipo}</span></span>
      <span style="font-weight:500;color:${m<0?'#dc2626':'#1f2937'}">${cjFmt(r.valor*m)}</span>
      <span class="cj-row-btns">
        <button class="cj-rbtn" onclick="event.stopPropagation();cjEditRow(${i})">Alt.</button>
        <button class="cj-rbtn del" onclick="event.stopPropagation();cjDelRow(${i})">Excluir</button>
      </span></div>`;
  }).join('');
}
function cjSel(i){cjSelIdx=i;cjRenderTabela();}
function cjDelRow(i){cjRubricas.splice(i,1);if(cjSelIdx>=cjRubricas.length)cjSelIdx=-1;cjRenderTabela();cjToast('Rubrica removida.');}
function cjEditRow(i){
  const r=cjRubricas[i];
  ['cj-m-data','cj-m-desc','cj-m-tipo','cj-m-valor','cj-m-obs'].forEach((id,j)=>{document.getElementById(id).value=[r.data,r.desc,r.tipo,r.valor,r.obs][j];});
  cjRubricas.splice(i,1);cjRenderTabela();document.getElementById('cj-modal-overlay').classList.add('open');
}
function cjAlterar(){if(cjSelIdx>=0)cjEditRow(cjSelIdx);}
function cjExcluir(){if(cjSelIdx>=0)cjDelRow(cjSelIdx);}
function cjLimpar(){if(confirm('Limpar todas as rubricas?')){cjRubricas=[];cjSelIdx=-1;cjRenderTabela();document.getElementById('cj-totals').style.display='none';document.getElementById('cj-resumo').style.display='none';}}

function cjCalcular(){
  if(!cjRubricas.length){alert('Adicione ao menos uma rubrica antes de calcular.');return;}
  const iCorr=document.getElementById('cj-sel-corr').value,cAte=document.getElementById('cj-corr-ate').value||cjHoje(),jTab=document.getElementById('cj-sel-juros').value,jAte=document.getElementById('cj-juros-ate').value||cjHoje(),honPct=parseFloat(document.getElementById('cj-hon-pct').value)||0,multaPct=parseFloat(document.getElementById('cj-multa-pct').value)||0,honSucPct=parseFloat(document.getElementById('cj-hon-suc-pct').value)||0;
  let tP=0,tC=0,tJ=0;
  cjRubricas.forEach(r=>{
    const s=r.tipo==='C'?-1:1,v=r.valor*s,de=r.data||cjHoje();
    tP+=v;
    const yDe=cjYm(de),yCAte=cjYm(cAte),yJAte=cjYm(jAte);
    if(yDe<yCAte)tC+=v*cjAcumulado(iCorr,yDe,yCAte);
    if(jTab==='SELIC'&&yDe<yJAte)tJ+=v*cjAcumulado('SELIC',yDe,yJAte);
    else if(jTab==='POUPANCA_SEM'&&yDe<yJAte)tJ+=v*cjAcumulado('POUPANCA',yDe,yJAte);
    else if(jTab==='CC_1PCT'){const m=(new Date(jAte).getFullYear()-new Date(de).getFullYear())*12+(new Date(jAte).getMonth()-new Date(de).getMonth());tJ+=v*m*0.01;}
  });
  const base=tP+tC+tJ,tH=base*honPct/100,tM=base*multaPct/100,tHS=base*honSucPct/100,geral=base+tH+tM+tHS;
  ['tot-principal','tot-corr','tot-juros','tot-hon','tot-multa','tot-geral'].forEach((id,i)=>{document.getElementById('cj-'+id).textContent=cjFmt([tP,tC,tJ,tH+tHS,tM,geral][i]);});
  document.getElementById('cj-data-calc').textContent=new Date().toLocaleDateString('pt-BR');
  document.getElementById('cj-totals').style.display='flex';
  document.getElementById('cj-resumo').style.display='flex';
  cjUltimoCalc={tP,tC,tJ,tH,tM,tHS,geral,iCorr,jTab,cAte,jAte};
  cjToast('Cálculo concluído com sucesso!');
}

function cjGerarMemorial(){
  if(!cjUltimoCalc){alert('Execute o cálculo antes de gerar o memorial.');return;}
  const c=cjUltimoCalc,proc=document.getElementById('cj-proc-num').value||'_______________',cred=document.getElementById('cj-credor').value||'_______________',dev=document.getElementById('cj-devedor').value||'_______________',vara=document.getElementById('cj-vara').value||'_______________',elab=document.getElementById('cj-elaborado-por').value||'_______________';
  const linhas=cjRubricas.map((r,i)=>`  ${i+1}. ${r.desc} (${cjPtDate(r.data)}): ${cjFmt(r.valor)} — Tipo: ${cjTipoLabel[r.tipo]||r.tipo}${r.obs?' | Obs: '+r.obs:''}`).join('\n');
  const txt=`MEMORIAL DE CÁLCULO — LIQUIDAÇÃO DE SENTENÇA\n${'='.repeat(56)}\n\nPROCESSO Nº: ${proc}\nVARA/JUÍZO:  ${vara}\nCREDOR:      ${cred}\nDEVEDOR:     ${dev}\nDATA-BASE:   ${new Date().toLocaleDateString('pt-BR')}\nELABORADO:   ${elab}\n\n${'─'.repeat(56)}\nI — CRITÉRIOS ADOTADOS\n${'─'.repeat(56)}\n\nCorreção Monetária: ${c.iCorr} — período até ${cjPtDate(c.cAte)}\nJuros Moratórios: ${c.jTab==='SELIC'?'SELIC — Lei 11.960/2009':c.jTab==='CC_1PCT'?'1% ao mês (CC art. 406)':'Poupança sem capitalização'} — período até ${cjPtDate(c.jAte)}\n\n${'─'.repeat(56)}\nII — VALORES INCLUÍDOS\n${'─'.repeat(56)}\n\n${linhas}\n\n${'─'.repeat(56)}\nIII — MEMÓRIA DE CÁLCULO\n${'─'.repeat(56)}\n\n  Principal:                        ${cjFmt(c.tP)}\n  Correção monetária (${c.iCorr}):    + ${cjFmt(c.tC)}\n  Juros moratórios:                 + ${cjFmt(c.tJ)}\n                                    ${'─'.repeat(14)}\n  Subtotal:                         = ${cjFmt(c.tP+c.tC+c.tJ)}\n  Honorários advocatícios:          + ${cjFmt(c.tH)}\n  Honorários sucumbenciais:         + ${cjFmt(c.tHS)}\n  Multa (art. 523, CPC):            + ${cjFmt(c.tM)}\n                                    ${'─'.repeat(14)}\n  TOTAL GERAL:                      = ${cjFmt(c.geral)}\n\n${'─'.repeat(56)}\n\nFlorianópolis/SC, ${new Date().toLocaleDateString('pt-BR',{day:'2-digit',month:'long',year:'numeric'})}.\n\n_____________________________________\n${elab}`;
  document.getElementById('cj-memorial-body').textContent=txt;
  document.getElementById('cj-memorial-overlay').classList.add('open');
}
function cjCopiarMemorial(){navigator.clipboard.writeText(document.getElementById('cj-memorial-body').textContent).then(()=>cjToast('Memorial copiado!'));}
function cjExportarCSV(){
  if(!cjRubricas.length){alert('Nenhuma rubrica para exportar.');return;}
  let csv='Data,Descrição,Tipo,Valor,Obs\n';
  cjRubricas.forEach(r=>{csv+=`"${r.data}","${r.desc}","${cjTipoLabel[r.tipo]||r.tipo}","${r.valor}","${r.obs}"\n`;});
  const a=document.createElement('a');a.href='data:text/csv;charset=utf-8,\uFEFF'+encodeURIComponent(csv);a.download='rubricas.csv';a.click();
  cjToast('CSV exportado!');
}

function cjNovaAba(){
  cjTabCount++;
  const bar=document.getElementById('cj-tabs-bar'),item=document.createElement('div');
  item.className='cj-tab-item';
  item.innerHTML=`<button class="cj-tab-btn" onclick="cjSwitchTab(this)">Rubrica ${cjTabCount}</button><button class="cj-close-tab" onclick="this.parentElement.remove()">✕</button>`;
  bar.insertBefore(item,bar.children[cjTabCount-1]);
  cjSwitchTab(item.querySelector('.cj-tab-btn'));
}
function cjSwitchTab(btn){document.querySelectorAll('.cj-tab-btn').forEach(b=>b.classList.remove('active'));btn.classList.add('active');}

function cjCalcSelicAcum(){
  const a=(cjAcumulado('SELIC','2021-12',cjYm(cjHoje()))*100).toFixed(2);
  document.getElementById('cj-selic-acum').textContent=a+'%';
  cjToast('SELIC acumulada calculada.');
}
function cjCalcPrazo(){
  const d=document.getElementById('cj-intimacao').value,p=parseInt(document.getElementById('cj-prazo').value)||15;
  if(!d){alert('Informe a data da intimação.');return;}
  const v=new Date(d+'T12:00');v.setDate(v.getDate()+p);
  const el=document.getElementById('cj-prazo-info');
  el.style.display='block';
  el.innerHTML=`⚖ Prazo de ${p} dias vence em: <strong>${v.toLocaleDateString('pt-BR')}</strong>${new Date()>v?`<br>⚠ Prazo expirado há ${Math.floor((new Date()-v)/86400000)} dias.`:''}`;
}
function cjResetCorr(){document.getElementById('cj-corr-desde').value='';document.getElementById('cj-corr-ate').value=cjHoje();document.getElementById('cj-sel-corr').value='IPCA-E';cjToast('Correção restaurada.');}

function cjToast(msg){const t=document.getElementById('cj-toast');t.textContent=msg;t.style.cssText='position:fixed;bottom:24px;right:24px;background:#1e3a8a;color:#fff;padding:10px 18px;border-radius:8px;font-size:13px;font-weight:500;z-index:9999;box-shadow:0 8px 24px rgba(0,0,0,.25);display:block';setTimeout(()=>t.style.display='none',2800);}

// Init CJ
document.getElementById('cj-corr-ate').value=cjHoje();
document.getElementById('cj-juros-ate').value=cjHoje();
document.getElementById('cj-data-base').value=cjHoje();
document.getElementById('cj-modal-overlay').addEventListener('click',e=>{if(e.target===document.getElementById('cj-modal-overlay'))cjCloseModal();});
document.getElementById('cj-memorial-overlay').addEventListener('click',e=>{if(e.target===document.getElementById('cj-memorial-overlay'))document.getElementById('cj-memorial-overlay').classList.remove('open');});
cjCalcSelicAcum();

// ══════════════════════════════════════════════════
// TESOURO DIRETO — LÓGICA (prefixada td*)
// ══════════════════════════════════════════════════
var COLORS={'Tesouro Selic':'#185FA5','Tesouro IPCA+':'#1D9E75','Tesouro Prefixado':'#BA7517','Tesouro IPCA+ com Juros Semestrais':'#0F6E56','Tesouro Prefixado com Juros Semestrais':'#854F0B'};
function gc(n){for(var k in COLORS)if(n&&n.indexOf(k)>-1)return COLORS[k];return '#888';}
function fr(v){return v!=null?(v*100).toFixed(2)+'%':'—';}
function fp(v){return v!=null?'R$ '+v.toLocaleString('pt-BR',{minimumFractionDigits:2,maximumFractionDigits:2}):'—';}
function fd(d){return d instanceof Date&&!isNaN(d)?d.toLocaleDateString('pt-BR'):'—';}
function latest(rows){return rows.reduce(function(a,b){return a.d>b.d?a:b;});}
function prevYear(rows){var t=new Date(Date.now()-365*864e5),best=null,bd=1e15;rows.forEach(function(r){var df=Math.abs(r.d-t);if(df<bd){bd=df;best=r;}});return best;}
function filt(rows,range){var days={max:9999,'2a':730,'1a':365,'6m':180}[range]||730,cut=new Date(Date.now()-days*864e5);return rows.filter(function(r){return r.d>=cut;}).sort(function(a,b){return a.d-b.d;});}
function thin(rows,mx){if(rows.length<=mx)return rows;var s=Math.ceil(rows.length/mx);return rows.filter(function(_,i){return i%s===0||i===rows.length-1;});}
var charts={};
function dc(id){if(charts[id]){charts[id].destroy();delete charts[id];}}

function genDemo(){
  var tipos=[['Tesouro Selic',0.1375],['Tesouro IPCA+',0.068],['Tesouro Prefixado',0.132]];
  var rows=[];var seed=7;
  function rnd(){seed=(seed*1664525+1013904223)&0xffffffff;return((seed>>>0)/4294967296);}
  var start=new Date(2023,0,2),end=new Date(2026,4,2);
  tipos.forEach(function(tp){var rate=tp[1],d=new Date(start);while(d<=end){if(d.getDay()>0&&d.getDay()<6){rate=Math.max(0.05,Math.min(0.19,rate+(rnd()-0.5)*0.002));rows.push({t:tp[0],d:new Date(d),r:parseFloat(rate.toFixed(5)),p:parseFloat((1000*Math.pow(1+rate,5)).toFixed(2))});}d.setDate(d.getDate()+1);}});
  return rows;
}
var D=genDemo(),G={};
D.forEach(function(x){if(!G[x.t])G[x.t]=[];G[x.t].push(x);});
var tdTitles=Object.keys(G),lat=D.reduce(function(a,b){return a.d>b.d?a:b;}),old=D.reduce(function(a,b){return a.d<b.d?a:b;});
document.getElementById('td-sbd').textContent='Demo · '+fd(lat.d);

function buildAll(){
  var avg=0,cnt=0;
  tdTitles.forEach(function(t){var l=latest(G[t]);if(l.r){avg+=l.r;cnt++;}});
  avg=cnt?avg/cnt:0;
  var anos=Math.round((lat.d-old.d)/864e5/365);
  document.getElementById('td-ovm').innerHTML=
    tdMc('Títulos',tdTitles.length,'tipos')+tdMc('Registros',D.length.toLocaleString('pt-BR'),'dias úteis')+tdMc('Taxa média',fr(avg),'atual')+tdMc('Histórico',anos+' anos',fd(old.d)+' → '+fd(lat.d),'up');
  var ns=[],rs=[],cs=[];
  tdTitles.forEach(function(t){var l=latest(G[t]);if(!l.r)return;ns.push(t.replace('Tesouro ',''));rs.push(parseFloat((l.r*100).toFixed(2)));cs.push(gc(t));});
  dc('td-cc');
  charts['td-cc']=new Chart(document.getElementById('td-cc'),{type:'bar',data:{labels:ns,datasets:[{data:rs,backgroundColor:cs.map(function(c){return c+'cc';}),borderColor:cs,borderWidth:1}]},options:{responsive:true,maintainAspectRatio:false,indexAxis:'y',plugins:{legend:{display:false}},scales:{x:{ticks:{callback:function(v){return v+'%';}},grid:{color:'rgba(0,0,0,0.06)'}},y:{grid:{display:false}}}}});
  document.getElementById('td-lgc').innerHTML=ns.map(function(n,i){return '<span><span class="ls" style="background:'+cs[i]+'"></span>'+n+': '+rs[i]+'%</span>';}).join('');
  var h1='',h2='';
  tdTitles.forEach(function(t){var l=latest(G[t]),c=gc(t);var inner='<div class="tn">'+t+'</div><div class="tr" style="color:'+c+'">'+fr(l.r)+'</div><div class="tt">'+G[t].length.toLocaleString('pt-BR')+' registros</div>';h1+='<button class="tb" onclick="tdGoHi(\''+t+'\')">'+inner+'</button>';h2+='<button class="tb" data-t="'+t+'" onclick="tdSelHi(\''+t+'\')">'+inner+'</button>';});
  document.getElementById('td-tco').innerHTML=h1;document.getElementById('td-tch').innerHTML=h2;
  var rh='';
  [{c:'al-gn',t:'Tesouro Selic — resgate a qualquer momento',b:'Liquidez diária real.'},{c:'al-am',t:'Tesouro IPCA+ — atenção ao momento',b:'Taxa atual maior que sua taxa de compra → aguarde. Taxa atual menor → PU subiu.'},{c:'al-gn',t:'Regra de ouro: taxa alta = preço baixo · taxa baixa = preço alto',b:'Quando taxa atual está abaixo da taxa de compra, o resgate antecipado é favorável para IPCA+ e Prefixado.'}].forEach(function(g){rh+='<div class="al '+g.c+'"><h4>'+g.t+'</h4><p>'+g.b+'</p></div>';});
  rh+='<div class="sl">Análise automática</div>';
  var now=new Date();
  tdTitles.forEach(function(t){var rows=G[t],l=latest(rows),l2y=rows.filter(function(r){return(now-r.d)<730*864e5;});if(!l2y.length||!l.r)return;var avg2=l2y.reduce(function(s,r){return s+r.r;},0)/l2y.length,above=l.r>avg2*1.02;rh+='<div class="al '+(above?'al-gn':'al-bl')+'"><h4>'+t+' — '+(above?'taxa acima da média':'taxa abaixo da média')+'</h4><p>Atual: <b>'+fr(l.r)+'</b> · Média 2 anos: <b>'+fr(avg2)+'</b> · '+(above?'Momento de compra favorável.':'Favorável para resgate antecipado.')+'</p></div>';});
  document.getElementById('td-rec').innerHTML=rh;
  tdBuildP();tdSim();
}
function tdMc(l,v,s,cls){return '<div class="mc"><div class="ml">'+l+'</div><div class="mv'+(cls?' '+cls:'')+'" >'+v+'</div><div class="ms">'+s+'</div></div>';}
buildAll();

var tdSelT=null,tdSelR='2a';
function tdGoHi(t){tdSelT=t;tdGo('hi');tdSelHi(t);}
function tdSelHi(t){
  tdSelT=t;
  document.querySelectorAll('#td-tch .tb').forEach(function(b){b.classList.toggle('on',b.dataset.t===t);});
  document.getElementById('td-hdd').style.display='block';
  tdDrawHist();
}
function tdSetR(r){
  tdSelR=r;
  var m={max:'Máximo','2a':'2 anos','1a':'1 ano','6m':'6 meses'};
  document.querySelectorAll('#td-phi .rng button').forEach(function(b){b.classList.toggle('on',b.textContent===m[r]);});
  if(tdSelT)tdDrawHist();
}
function tdDrawHist(){
  var rows=G[tdSelT],f=thin(filt(rows,tdSelR),200);
  var lbs=f.map(function(r){return r.d.toLocaleDateString('pt-BR',{month:'2-digit',year:'2-digit'});});
  var col=gc(tdSelT),l=latest(rows),py=prevYear(rows),diff=(l&&py)?(l.r-py.r):null;
  document.getElementById('td-htt').textContent=tdSelT+' — Taxa histórica';
  document.getElementById('td-hpt').textContent=tdSelT+' — PU histórico';
  document.getElementById('td-hm').innerHTML=
    '<div class="mc"><div class="ml">Taxa atual</div><div class="mv">'+fr(l.r)+'</div><div class="ms">em '+fd(l.d)+'</div></div>'+
    '<div class="mc"><div class="ml">PU compra</div><div class="mv" style="font-size:14px">'+fp(l.p)+'</div><div class="ms">preço unitário</div></div>'+
    '<div class="mc"><div class="ml">Taxa há 1 ano</div><div class="mv" style="font-size:15px">'+(py?fr(py.r):'—')+'</div><div class="ms">em '+fd(py&&py.d)+'</div></div>'+
    '<div class="mc"><div class="ml">Var. 12 meses</div><div class="mv '+(diff==null?'':diff>0?'up':'dn')+'" style="font-size:15px">'+(diff!=null?(diff>0?'+':'')+((diff*100).toFixed(2))+'pp':'—')+'</div><div class="ms">na taxa a.a.</div></div>';
  dc('td-ct');charts['td-ct']=new Chart(document.getElementById('td-ct'),{type:'line',data:{labels:lbs,datasets:[{data:f.map(function(r){return parseFloat((r.r*100).toFixed(4));}),borderColor:col,backgroundColor:col+'22',fill:true,tension:.3,pointRadius:0,borderWidth:1.5,spanGaps:true}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false}},scales:{x:{ticks:{maxTicksLimit:7,autoSkip:true},grid:{display:false}},y:{ticks:{callback:function(v){return v+'%';}},grid:{color:'rgba(0,0,0,0.06)'}}}}});
  dc('td-cpu');charts['td-cpu']=new Chart(document.getElementById('td-cpu'),{type:'line',data:{labels:lbs,datasets:[{data:f.map(function(r){return parseFloat(r.p.toFixed(2));}),borderColor:'#1D9E75',backgroundColor:'#1D9E7522',fill:true,tension:.3,pointRadius:0,borderWidth:1.5,spanGaps:true}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false}},scales:{x:{ticks:{maxTicksLimit:7,autoSkip:true},grid:{display:false}},y:{ticks:{callback:function(v){return 'R$'+v.toLocaleString('pt-BR');}},grid:{color:'rgba(0,0,0,0.06)'}}}}});
}

var tdAp='c';
function tdSetP(p){tdAp=p;document.querySelectorAll('.pfb button').forEach(function(b,i){b.classList.toggle('on',['c','m','a'][i]===p);});tdBuildP();}
var PD={c:[{n:'Tesouro Selic',t:'14,75%',col:'#185FA5',rec:1,r:9,d:'Acompanha a Selic. Liquidez imediata. Ideal para reserva de emergência.',m:'Excelente — Selic a 14,75%.',tg:[{t:'Risco mínimo',c:'bg-gn'},{t:'Liquidez diária',c:'bg-gn'}]},{n:'Tesouro IPCA+ (≤2030)',t:'IPCA + ~7%',col:'#1D9E75',rec:0,r:7,d:'Protege contra inflação + taxa real ~7% a.a.',m:'Bom — taxa real histórica.',tg:[{t:'Proteção inflação',c:'bg-gn'},{t:'Taxa real alta',c:'bg-gn'}]}],m:[{n:'Tesouro IPCA+ 2035',t:'IPCA + ~7%',col:'#1D9E75',rec:1,r:9,d:'Melhor equilíbrio risco-retorno. Trava taxa real elevada.',m:'Excelente momento — taxas reais próximas de máximas históricas.',tg:[{t:'Oportunidade histórica',c:'bg-gn'},{t:'Proteção inflação',c:'bg-gn'}]},{n:'Tesouro Selic',t:'14,75%',col:'#185FA5',rec:0,r:8,d:'Manter parte para liquidez.',m:'Muito bom.',tg:[{t:'Liquidez',c:'bg-gn'}]}],a:[{n:'Tesouro IPCA+ 2045/2055',t:'IPCA + ~7%',col:'#1D9E75',rec:1,r:10,d:'Máxima convexidade — queda de taxa gera valorização exponencial.',m:'Taxa real de 7% em título soberano é excepcional.',tg:[{t:'Alta convexidade',c:'bg-gn'},{t:'Máx. retorno',c:'bg-gn'},{t:'Alta volatilidade PU',c:'bg-rd'}]},{n:'Tesouro Prefixado 2031',t:'~13,5–14%',col:'#BA7517',rec:0,r:7,d:'Aposta em queda mais intensa da Selic.',m:'Para quem acredita em cenário fiscal melhor.',tg:[{t:'Alavancagem taxa',c:'bg-am'},{t:'Risco elevado',c:'bg-rd'}]}]};
function tdBuildP(){
  var list=PD[tdAp],rec=list.find(function(x){return x.rec;}),h='';
  if(rec)h+='<div class="al al-bl" style="margin-bottom:8px"><h4>Recomendação principal: '+rec.n+'</h4><p>'+rec.m+'</p></div>';
  list.forEach(function(x){h+='<div class="rc'+(x.rec?' ft':'')+'"><div class="rh2"><div><div class="rn">'+(x.rec?'★ ':'')+x.n+'</div></div><div class="rr" style="color:'+x.col+'">'+x.t+'</div></div><div class="rd">'+x.d+'</div><div class="rd"><b>Momento:</b> '+x.m+'</div><div class="rat">'+Array.from({length:10},function(_,i){return '<div class="rt '+(i<x.r?'on':'off')+'"></div>';}).join('')+'</div><div style="font-size:10px;color:#aaa;margin-bottom:4px">'+x.r+'/10</div><div class="tags">'+x.tg.map(function(g){return '<span class="tag '+g.c+'">'+g.t+'</span>';}).join('')+'</div></div>';});
  document.getElementById('td-pfc').innerHTML=h;
}
function tdSim(){
  var v=parseFloat(document.getElementById('td-sv').value)||10000,a=parseInt(document.getElementById('td-sp').value)||5,ip=parseFloat(document.getElementById('td-sipc').value)/100,se=parseFloat(document.getElementById('td-ssel').value)/100;
  document.getElementById('td-spv').textContent=a;document.getElementById('td-siv').textContent=(ip*100).toFixed(1).replace('.',',');document.getElementById('td-ssv').textContent=(se*100).toFixed(1).replace('.',',');
  var ir=a<=0.5?.225:a<=1?.20:a<=2?.175:.15;
  function calc(r){return Math.round(v+(v*Math.pow(1+r,a)-v)*(1-ir));}
  function fb(n){return 'R$ '+n.toLocaleString('pt-BR');}
  document.getElementById('td-smm').innerHTML='<div class="mc"><div class="ml">Tesouro Selic</div><div class="mv up" style="font-size:15px">'+fb(calc(se))+'</div><div class="ms">líquido de IR</div></div>'+'<div class="mc"><div class="ml">Tesouro IPCA+</div><div class="mv up" style="font-size:15px">'+fb(calc(ip+.07))+'</div><div class="ms">líquido de IR</div></div>'+'<div class="mc"><div class="ml">Prefixado</div><div class="mv up" style="font-size:15px">'+fb(calc(.135))+'</div><div class="ms">líquido de IR</div></div>'+'<div class="mc"><div class="ml">Poupança</div><div class="mv dn" style="font-size:15px">'+fb(calc(.065))+'</div><div class="ms">referência</div></div>';
  var ls=['Hoje'],dS=[v],dI=[v],dP=[v],dPoup=[v];
  for(var i=1;i<=a;i++){ls.push('Ano '+i);dS.push(Math.round(v*Math.pow(1+se,i)));dI.push(Math.round(v*Math.pow(1+ip+.07,i)));dP.push(Math.round(v*Math.pow(1+.135,i)));dPoup.push(Math.round(v*Math.pow(1+.065,i)));}
  dc('td-cs');charts['td-cs']=new Chart(document.getElementById('td-cs'),{type:'line',data:{labels:ls,datasets:[{label:'Selic',data:dS,borderColor:'#185FA5',fill:false,tension:.3,pointRadius:2,borderWidth:2},{label:'IPCA+',data:dI,borderColor:'#1D9E75',fill:false,tension:.3,pointRadius:2,borderWidth:2,borderDash:[5,3]},{label:'Prefixado',data:dP,borderColor:'#BA7517',fill:false,tension:.3,pointRadius:2,borderWidth:2,borderDash:[2,4]},{label:'Poupança',data:dPoup,borderColor:'#888',fill:false,tension:.3,pointRadius:1,borderWidth:1.5,borderDash:[1,3]}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false}},scales:{x:{grid:{display:false}},y:{ticks:{callback:function(v){return 'R$'+Math.round(v/1000)+'k';}},grid:{color:'rgba(0,0,0,0.06)'}}}}});
  document.getElementById('td-slg').innerHTML=[['#185FA5','Selic'],['#1D9E75','IPCA+'],['#BA7517','Prefixado'],['#888','Poupança']].map(function(x){return '<span><span class="ls" style="background:'+x[0]+'"></span>'+x[1]+'</span>';}).join('');
}

var tdPages=['ov','hi','re','ma','ti','si'];
function tdGo(p){
  tdPages.forEach(function(x){var el=document.getElementById('td-p'+x);if(el)el.style.display=x===p?'block':'none';});
  document.querySelectorAll('#mod-tesouro .ni').forEach(function(b,i){b.classList.toggle('on',tdPages[i]===p);});
  if(p==='ti')tdBuildP();if(p==='si')tdSim();
}
function tdOpenM(){document.getElementById('td-modal').classList.add('open');}
function tdCloseM(){document.getElementById('td-modal').classList.remove('open');}
var tdDzel=document.getElementById('td-dz');
tdDzel.addEventListener('dragover',function(e){e.preventDefault();tdDzel.classList.add('drag');});
tdDzel.addEventListener('dragleave',function(){tdDzel.classList.remove('drag');});
tdDzel.addEventListener('drop',function(e){e.preventDefault();tdDzel.classList.remove('drag');var f=e.dataTransfer.files[0];if(f)tdProcCSV(f);});
function tdHandleCSV(e){var f=e.target.files[0];if(f)tdProcCSV(f);}
var tdBlob=null;
function tdRedown(){if(tdBlob){var u=URL.createObjectURL(tdBlob),a=document.createElement('a');a.href=u;a.download='ferramentas-juridicas.html';a.click();setTimeout(function(){URL.revokeObjectURL(u);},1000);}}
function tdSetp(pct,msg){document.getElementById('td-pfill').style.width=pct+'%';document.getElementById('td-pmsg').textContent=msg;}
function tdShowerr(msg){document.getElementById('td-errbox').style.display='block';document.getElementById('td-errbox').textContent='Erro: '+msg;document.getElementById('td-prog').style.display='none';}
function tdProcCSV(file){
  document.getElementById('td-prog').style.display='block';
  document.getElementById('td-resbox').style.display='none';
  document.getElementById('td-errbox').style.display='none';
  tdSetp(10,'Lendo arquivo...');
  var r=new FileReader();
  r.onerror=function(){tdShowerr('Erro ao ler o arquivo.');};
  r.onload=function(e){
    try{
      tdSetp(40,'Processando CSV...');
      var parsed=Papa.parse(e.target.result,{header:true,skipEmptyLines:true,delimiter:';'});
      if(!parsed.data.length)throw new Error('Arquivo vazio ou delimitador inválido.');
      var keys=Object.keys(parsed.data[0]);
      function get(row,pats){for(var i=0;i<pats.length;i++)for(var j=0;j<keys.length;j++)if(keys[j].toLowerCase().replace(/\s+/g,'').indexOf(pats[i].toLowerCase().replace(/\s+/g,''))>-1)return row[keys[j]];return null;}
      function pd(s){if(!s)return null;var p=s.trim().split('/');return p.length===3?new Date(+p[2],+p[1]-1,+p[0]).toISOString().slice(0,10):null;}
      function pu(s){if(!s)return null;var v=parseFloat(s.trim().replace(/\./g,'').replace(',','.'));return isNaN(v)?null:v;}
      function pr(s){if(!s)return null;var v=parseFloat(s.trim().replace(',','.'));return isNaN(v)?null:v/100;}
      var nd=parsed.data.map(function(row){return{t:(get(row,['TipoTitulo','Tipo Titulo'])||'').trim(),d:pd(get(row,['DataBase','Data Base'])),r:pr(get(row,['TaxaCompraM','Taxa Compra Manha'])),p:pu(get(row,['PUCompraM','PU Compra Manha'])),};}).filter(function(x){return x.d&&x.t;});
      if(!nd.length)throw new Error('Nenhum registro válido.');
      tdSetp(80,'Gerando arquivo...');
      var tits=[...new Set(nd.map(function(x){return x.t;}))];
      var ds=nd.map(function(x){return x.d;}).filter(Boolean).sort();
      var anos=Math.round((new Date(ds[ds.length-1])-new Date(ds[0]))/864e5/365);
      var newData=JSON.stringify(nd);
      var newFn='function genDemo(){return '+newData+'.map(function(x){return{t:x.t,d:new Date(x.d),r:x.r,p:x.p};});}';
      var html=document.documentElement.outerHTML;
      var final=html.replace(/function genDemo\(\)\{[\s\S]*?^\}/m,newFn);
      tdBlob=new Blob([final],{type:'text/html;charset=utf-8'});
      tdRedown();
      document.getElementById('td-resstats').textContent=nd.length.toLocaleString('pt-BR')+' registros · '+tits.length+' títulos · '+anos+' anos de histórico';
      document.getElementById('td-resbox').style.display='block';
      document.getElementById('td-prog').style.display='none';
    }catch(err){tdShowerr(err.message);}
  };
  r.readAsText(file,'latin1');
}
</script>
</body>
</html>
