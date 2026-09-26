# Torres.mobiles.reparacion
Especialista de reparaciones de celulares avanzadas laptop TV reloj
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#101827">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="mobile-web-app-capable" content="yes">
<title>Torres Mobil Reparación | Sistema Profesional</title>

<style>
:root{
 --ink:#172033;--muted:#68758a;--navy:#101827;--navy2:#172338;
 --blue:#3478f6;--blue2:#5a8df8;--cyan:#26b8c7;--green:#22a06b;
 --amber:#e8a331;--red:#d9535f;--bg:#f3f6fa;--card:#ffffff;--line:#e7ebf1;
 --shadow:0 12px 35px rgba(20,31,53,.08);--shadow2:0 4px 16px rgba(20,31,53,.06);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 margin:0;background:var(--bg);color:var(--ink);
 font-family:Inter,ui-sans-serif,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Arial,sans-serif;
 font-size:14px;
}
body:before{
 content:"";position:fixed;inset:0;z-index:-2;
 background:linear-gradient(90deg,rgba(243,246,250,.98),rgba(243,246,250,.96)),
 url("https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?q=85&w=2200&auto=format&fit=crop") center/cover fixed;
}
button,input,select,textarea{font:inherit}
button{cursor:pointer}
.shell{min-height:100vh;display:flex}
.sidebar{
 position:fixed;left:0;top:0;bottom:0;width:248px;background:linear-gradient(180deg,#111b2d 0%,#0d1626 100%);
 color:white;padding:22px 15px;z-index:20;box-shadow:8px 0 30px rgba(10,18,31,.10);
}
.logo{display:flex;align-items:center;gap:11px;padding:7px 9px 23px;border-bottom:1px solid rgba(255,255,255,.09)}
.logo-mark{
 width:42px;height:42px;border-radius:12px;background:linear-gradient(135deg,#3478f6,#26b8c7);
 display:grid;place-items:center;font-size:22px;box-shadow:0 7px 18px rgba(52,120,246,.25)
}
.logo strong{display:block;font-size:14px;letter-spacing:.3px}.logo small{color:#91a0b6;font-size:10px}
.side-label{color:#6f8099;text-transform:uppercase;font-size:9px;font-weight:800;letter-spacing:1px;margin:23px 11px 8px}
.side-nav{display:grid;gap:4px}
.side-nav button{
 width:100%;border:0;background:transparent;color:#aebbd0;text-align:left;
 padding:11px 12px;border-radius:10px;font-weight:650;display:flex;align-items:center;gap:11px
}
.side-nav button:hover,.side-nav button.active{background:rgba(255,255,255,.08);color:#fff}
.side-nav .ico{width:20px;text-align:center}
.side-bottom{position:absolute;left:15px;right:15px;bottom:18px;padding:12px;border-radius:12px;background:rgba(255,255,255,.055);color:#9eacc0;font-size:10px;line-height:1.5}
.main{margin-left:248px;width:calc(100% - 248px);min-width:0}
.topbar{
 height:76px;background:rgba(255,255,255,.92);border-bottom:1px solid var(--line);
 display:flex;align-items:center;justify-content:space-between;padding:0 34px;position:sticky;top:0;z-index:15;
 backdrop-filter:blur(15px)
}
.crumb{color:var(--muted);font-size:12px}.crumb b{color:var(--ink);font-size:13px}
.top-actions{display:flex;align-items:center;gap:10px}
.user-chip{display:flex;align-items:center;gap:9px;padding:7px 10px;border:1px solid var(--line);border-radius:10px;background:#fff}
.avatar{width:30px;height:30px;border-radius:9px;background:#eaf1ff;color:#3478f6;display:grid;place-items:center;font-weight:800}
.content{padding:30px 34px 40px;max-width:1700px;margin:auto}
.hero{
 border-radius:20px;min-height:190px;padding:30px 34px;color:#fff;position:relative;overflow:hidden;
 background:
 linear-gradient(100deg,rgba(14,27,49,.97) 0%,rgba(20,53,88,.92) 54%,rgba(40,91,130,.72) 100%),
 url("https://images.unsplash.com/photo-1598327105666-5b89351aff97?q=85&w=1800&auto=format&fit=crop") right center/cover;
 box-shadow:0 16px 40px rgba(16,32,54,.14)
}
.hero:after{content:"";position:absolute;right:-70px;top:-90px;width:320px;height:320px;border:1px solid rgba(255,255,255,.08);border-radius:50%;box-shadow:0 0 0 55px rgba(255,255,255,.025),0 0 0 110px rgba(255,255,255,.02)}
.hero h1{font-size:28px;letter-spacing:-.5px;margin:0 0 8px;position:relative;z-index:2}.hero p{margin:0;color:#c7d5e8;max-width:610px;line-height:1.55;position:relative;z-index:2}
.hero-actions{margin-top:20px;display:flex;gap:9px;position:relative;z-index:2}
.btn{border:1px solid transparent;border-radius:9px;padding:10px 14px;font-weight:750;font-size:12px;transition:.15s}
.btn:hover{transform:translateY(-1px)}.btn-primary{background:var(--blue);color:white}.btn-white{background:#fff;color:#172033}.btn-soft{background:#edf3ff;color:#2b66cf;border-color:#dbe7ff}.btn-green{background:var(--green);color:#fff}.btn-amber{background:var(--amber);color:#fff}.btn-red{background:var(--red);color:#fff}.btn-dark{background:#172033;color:#fff}.btn-plain{background:#f3f6fa;color:#344154;border-color:#e1e6ed}
.stats{display:grid;grid-template-columns:repeat(5,minmax(0,1fr));gap:14px;margin:18px 0}
.stat{
 background:#fff;border:1px solid var(--line);border-radius:14px;padding:16px 17px;box-shadow:var(--shadow2);position:relative;overflow:hidden
}
.stat .sicon{position:absolute;right:14px;top:14px;width:35px;height:35px;border-radius:10px;background:#f1f5fb;display:grid;place-items:center}
.stat small{display:block;color:var(--muted);font-size:10px;font-weight:800;text-transform:uppercase;letter-spacing:.55px;margin-bottom:8px}
.stat b{font-size:23px;letter-spacing:-.5px}.stat .trend{display:block;color:#7b8798;font-size:10px;margin-top:5px}
.grid2{display:grid;grid-template-columns:minmax(0,1.35fr) minmax(330px,.65fr);gap:18px}
.card{background:var(--card);border:1px solid var(--line);border-radius:15px;box-shadow:var(--shadow2);padding:21px}
.card-head{display:flex;justify-content:space-between;align-items:flex-start;gap:15px;margin-bottom:17px}.card-head h2{font-size:16px;margin:0}.card-head p{font-size:11px;color:var(--muted);margin:4px 0 0}
.form-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.span2{grid-column:span 2}.span3{grid-column:1/-1}
label{display:block;font-size:10px;font-weight:850;text-transform:uppercase;letter-spacing:.55px;color:#526075;margin-bottom:6px}
input,select,textarea{width:100%;padding:10px 11px;border:1px solid #d9e0e9;border-radius:8px;background:#fff;color:#172033;outline:none;font-size:12px;transition:.16s}
input:focus,select:focus,textarea:focus{border-color:#72a0f9;box-shadow:0 0 0 3px rgba(52,120,246,.09)}
textarea{min-height:84px;resize:vertical}
.form-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:17px;padding-top:15px;border-top:1px solid var(--line)}
.photo-card{background:#f8fafc;border:1px dashed #ccd6e3;border-radius:12px;padding:15px;text-align:center}
.photo-card img{max-width:100%;max-height:210px;display:none;border-radius:10px;margin:10px auto 0;object-fit:cover}
.photo-card .photo-icon{font-size:30px;color:#8b9bb0;margin:5px}
.quick{display:grid;grid-template-columns:1fr 1fr;gap:9px}.quick button{min-height:64px;text-align:left}
.quick strong{display:block;font-size:11px}.quick small{display:block;color:#7c8798;font-size:9px;margin-top:3px}
.appointment{border:1px solid var(--line);border-left:3px solid var(--blue);padding:11px 12px;border-radius:9px;margin-bottom:8px;background:#fbfcfe}
.appointment b{font-size:12px}.appointment span,.appointment small{display:block;color:var(--muted);font-size:10px;margin-top:3px}
.filters{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:13px}.filters input{flex:1;min-width:280px}.filters select{width:auto;min-width:145px}
.table-wrap{overflow:auto;border:1px solid var(--line);border-radius:11px}
table{width:100%;border-collapse:collapse;min-width:1150px}th,td{padding:11px 12px;border-bottom:1px solid #edf0f4;text-align:left;font-size:11px;vertical-align:middle}th{background:#f8fafc;color:#667387;text-transform:uppercase;font-size:9px;letter-spacing:.55px}tr:hover td{background:#fbfdff}
.thumb{width:45px;height:45px;border-radius:8px;object-fit:cover;border:1px solid #dbe2eb}
.badge{display:inline-flex;border-radius:99px;padding:5px 8px;font-size:9px;font-weight:850}.b-pendiente{background:#fff5dc;color:#996500}.b-reparacion{background:#eaf2ff;color:#2c61c1}.b-reparado{background:#e5f8ef;color:#17764d}.b-entregado{background:#eef1f5;color:#596577}
.invoice-paper{border:1px solid #e2e7ef;border-radius:12px;overflow:hidden;max-width:900px;margin:auto;background:#fff}.invoice-head{background:linear-gradient(120deg,#111b2d,#1f3c69);color:#fff;padding:22px 24px;display:flex;justify-content:space-between}.invoice-head h3{margin:0;font-size:19px}.invoice-head small{color:#b9c9df;font-size:9px}.invoice-body{padding:22px}.invoice-info{display:grid;grid-template-columns:1fr 1fr;gap:10px}.ibox{padding:12px;background:#f7f9fc;border-radius:8px;font-size:11px}.ibox b{display:block;font-size:9px;text-transform:uppercase;color:#738096;margin-bottom:5px}.invoice-line{display:flex;justify-content:space-between;border-bottom:1px solid #e7ebf1;padding:18px 0;font-size:12px}.invoice-total{display:flex;justify-content:space-between;margin-top:14px;background:#edf4ff;color:#1f4e9b;border-radius:9px;padding:14px;font-size:17px;font-weight:900}
.modal{position:fixed;inset:0;background:rgba(12,19,33,.68);backdrop-filter:blur(7px);display:none;align-items:center;justify-content:center;padding:20px;z-index:100}.modal.open{display:flex}.modal-card{width:100%;max-width:540px;background:#fff;border-radius:16px;padding:20px;box-shadow:0 25px 80px rgba(0,0,0,.25)}
.toast{position:fixed;right:25px;bottom:25px;background:#172033;color:white;padding:11px 15px;border-radius:9px;font-size:11px;display:none;z-index:200;box-shadow:0 12px 30px rgba(0,0,0,.2)}
.footer{padding:25px 0;color:#8a96a8;text-align:center;font-size:10px}
@media(max-width:1100px){.stats{grid-template-columns:repeat(3,1fr)}.grid2{grid-template-columns:1fr}.form-grid{grid-template-columns:repeat(2,1fr)}.span2{grid-column:auto}.span3{grid-column:1/-1}}
@media(max-width:760px){.sidebar{position:static;width:100%;height:auto}.shell{display:block}.main{margin-left:0;width:100%}.side-nav{grid-template-columns:repeat(2,1fr)}.side-bottom{display:none}.topbar{padding:0 15px}.content{padding:16px}.stats{grid-template-columns:repeat(2,1fr)}.form-grid{grid-template-columns:1fr}.span3{grid-column:auto}.hero{padding:23px}.hero h1{font-size:23px}.invoice-info{grid-template-columns:1fr}}
</style>


<style id="simple-clean-style">
/* Diseño simplificado: menos elementos, más espacio y lectura más clara */
.sidebar{width:210px;padding:18px 12px}
.main{margin-left:210px;width:calc(100% - 210px)}
.topbar{height:64px;padding:0 24px}
.content{padding:22px 24px 32px;max-width:1500px}
.hero{min-height:145px;padding:24px 28px;border-radius:16px}
.hero h1{font-size:25px;margin-bottom:6px}
.hero p{font-size:12px;margin:0 0 16px}
.hero-actions{margin-top:12px}
.stats{grid-template-columns:repeat(5,minmax(0,1fr));gap:10px;margin:14px 0}
.stat{padding:13px 14px;border-radius:11px}
.stat b{font-size:20px}
.stat .trend{font-size:9px}
.grid2{gap:14px}
.card{border-radius:12px}
.card-head{padding:15px 17px}
.card-head h2{font-size:15px}
.card-head p{font-size:10px}
.form-grid{gap:10px}
label{font-size:10px}
input,select,textarea{padding:10px 11px;border-radius:8px}
.photo-card{padding:14px!important}
.quick{display:none}
.grid2 > aside > section.card:not(#agenda){display:none}
#historial,#facturacion{margin-top:14px!important}
.table-wrap{border-radius:9px}
.btn{border-radius:8px}
@media(max-width:1000px){.stats{grid-template-columns:repeat(3,1fr)}}
@media(max-width:760px){.sidebar{position:static;width:100%;height:auto}.main{margin-left:0;width:100%}.side-nav{display:grid;grid-template-columns:repeat(2,1fr);gap:6px}.sidebar .side-label,.sidebar .side-footer{display:none}.topbar{padding:0 14px}.content{padding:14px}.stats{grid-template-columns:repeat(2,1fr)}.hero{min-height:125px;padding:20px}.hero-actions .btn{font-size:11px}}
</style>
<script async onload="nativelyOnLoad()" src="https://cdn.jsdelivr.net/npm/natively@2.26.0/natively-frontend.min.js"></script>
<script>
function nativelyOnLoad(){
  try{ if(window.natively && window.natively.setDebug) window.natively.setDebug(false); }catch(e){}
}
</script>
<style>
/* Ajustes para Natively / teléfonos */
html,body{overscroll-behavior-y:none;-webkit-tap-highlight-color:transparent}
button,a,input,select,textarea{touch-action:manipulation}
@media(max-width:760px){
  body{font-size:15px;padding-bottom:70px}
  .shell{display:block}
  .sidebar{display:none!important}
  .main{width:100%!important;margin:0!important;padding:12px!important}
  .topbar{position:sticky;top:0;z-index:20;margin:-12px -12px 12px;padding:12px 14px!important}
  .hero{min-height:150px!important;border-radius:18px!important}
  .stats{grid-template-columns:repeat(2,1fr)!important;gap:10px!important}
  .grid,.form-grid,.cards,.columns{grid-template-columns:1fr!important}
  .card{border-radius:16px!important}
  .modal-card{width:calc(100% - 24px)!important;max-height:90vh!important}
  input,select,textarea{font-size:16px!important;min-height:44px}
  .btn{min-height:44px}
  .mobile-nav{display:flex!important}
}
.mobile-nav{display:none;position:fixed;left:10px;right:10px;bottom:10px;z-index:1000;background:rgba(16,24,39,.96);border:1px solid rgba(255,255,255,.12);border-radius:18px;padding:7px;box-shadow:0 12px 30px rgba(0,0,0,.25);backdrop-filter:blur(12px)}
.mobile-nav button{flex:1;border:0;background:transparent;color:#cbd5e1;padding:9px 4px;border-radius:12px;font-size:11px}
.mobile-nav button:first-child{background:#3478f6;color:#fff}
.native-badge{display:none}
</style>
</head>

<body>
<div class="shell">
<aside class="sidebar">
  <div class="logo"><div class="logo-mark">📱</div><div><strong>TORRES MOBIL</strong><small>REPARACIÓN • PRO</small></div></div>
  <div class="side-label">Principal</div>
  <nav class="side-nav">
    <button class="active" onclick="irA('dashboard')"><span class="ico">⌂</span>Dashboard</button>
    <button onclick="irA('registro')"><span class="ico">＋</span>Nuevo equipo</button>
    <button onclick="irA('agenda')"><span class="ico">◷</span>Agenda</button>
    <button onclick="irA('facturacion')"><span class="ico">▣</span>Facturación</button>
    <button onclick="irA('historial')"><span class="ico">☷</span>Historial</button>
  </nav>
  <div class="side-label">Herramientas</div>
  <nav class="side-nav">
    <button onclick="exportarDatos()"><span class="ico">↓</span>Exportar respaldo</button>
    <button onclick="document.getElementById('importFile').click()"><span class="ico">↑</span>Importar respaldo</button>
  </nav>
  <div class="side-bottom">Sistema local de gestión<br><b>Torres Mobil Reparación</b><br>Diseñado para escritorio y móvil.</div>
</aside>

<main class="main">
<header class="topbar">
  <div class="crumb">Torres Mobil / <b>Panel de control</b></div>
  <div class="top-actions"><button class="btn btn-soft" onclick="irA('registro')">＋ Registrar equipo</button><div class="user-chip"><div class="avatar">TM</div><span>Administrador</span></div></div>
</header>

<div class="content">
<section class="hero" id="dashboard">
  <h1>Torres Mobil Reparación</h1>
  <p>Registro, reparaciones, agenda y facturación en un solo lugar.</p>
  <div class="hero-actions"><button class="btn btn-white" onclick="irA('registro')">📱 Recibir equipo</button><button class="btn" style="background:rgba(255,255,255,.12);color:#fff;border-color:rgba(255,255,255,.18)" onclick="irA('agenda')">📅 Ver agenda</button></div>
</section>

<section class="stats">
 <div class="stat"><small>Equipos registrados</small><b id="sTotal">0</b><span class="sicon">📱</span><span class="trend">Historial total</span></div>
 <div class="stat"><small>Pendientes</small><b id="sPend">0</b><span class="sicon">⏳</span><span class="trend">Esperando atención</span></div>
 <div class="stat"><small>En reparación</small><b id="sRep">0</b><span class="sicon">🔧</span><span class="trend">Trabajo activo</span></div>
 <div class="stat"><small>Reparados</small><b id="sReady">0</b><span class="sicon">✓</span><span class="trend">Listos para entregar</span></div>
 <div class="stat"><small>Valor registrado</small><b id="sValue">RD$ 0</b><span class="sicon">$</span><span class="trend">Total de servicios</span></div>
</section>

<div class="grid2">
<section class="card" id="registro">
 <div class="card-head"><div><h2>Registrar nuevo equipo</h2><p>Ficha técnica y recepción del dispositivo</p></div><span>● <small style="color:#22a06b">Nuevo registro</small></span></div>
 <form id="phoneForm">
  <div class="form-grid">
   <div><label>Cliente</label><input id="cliente" required placeholder="Nombre completo"></div>
   <div><label>Teléfono</label><input id="telefono" type="tel" placeholder="809 000 0000"></div>
   <div><label>Celular / modelo</label><input id="modelo" required placeholder="iPhone 13 Pro Max"></div>
   <div><label>IMEI / serial</label><input id="imei" placeholder="Opcional"></div>
   <div><label>Precio (RD$)</label><input id="precio" type="number" min="0" step=".01" required placeholder="0.00"></div>
   <div><label>Categoría</label><select id="categoria"><option>Pantalla</option><option>Batería</option><option>Puerto de carga</option><option>Cámara</option><option>Software</option><option>Placa / electrónica</option><option>Audio / micrófono</option><option>Otro</option></select></div>
   <div><label>Servicio / reparación</label><input id="reparacion" required placeholder="Cambio de pantalla"></div>
   <div><label>Estado</label><select id="estado"><option>Pendiente</option><option>En reparación</option><option>Reparado</option><option>Entregado</option></select></div>
   <div><label>Fecha recepción</label><input id="fecha" type="date" required></div>
   <div><label>Entrega programada</label><input id="entrega" type="datetime-local"></div>
   <div class="span2"><label>Diagnóstico / observaciones</label><textarea id="descripcion" placeholder="Daños visibles, diagnóstico, accesorios, garantía..."></textarea></div>
   <div class="span3 photo-card">
    <div class="photo-icon">📷</div><label>Fotografía del equipo</label>
    <div style="color:#7b8798;font-size:10px;margin-bottom:10px">Toma una foto del estado del celular al recibirlo.</div>
    <div style="display:flex;gap:7px;justify-content:center;flex-wrap:wrap">
      <button class="btn btn-primary" type="button" onclick="abrirCamara()">📷 Abrir cámara</button>
      <button class="btn btn-plain" type="button" onclick="document.getElementById('fotoArchivo').click()">🖼️ Galería</button>
      <button class="btn btn-plain" type="button" onclick="quitarFoto()">Eliminar</button>
    </div>
    <input id="fotoArchivo" type="file" accept="image/*" capture="environment" hidden><img id="fotoPreview" alt="Foto del equipo"><canvas id="canvasFoto" hidden></canvas>
   </div>
  </div>
  <div class="form-actions"><button class="btn btn-primary" type="submit">✓ Guardar equipo</button><button class="btn btn-plain" type="button" onclick="limpiarRegistro()">Limpiar formulario</button></div>
 </form>
</section>

<aside>
 <section class="card" id="agenda">
  <div class="card-head"><div><h2>Agenda</h2><p>Próximas citas y entregas</p></div><button class="btn btn-soft" onclick="abrirCita()">＋</button></div>
  <div id="agendaLista"></div>
  <button class="btn btn-primary" style="width:100%;margin-top:6px" onclick="abrirCita()">Agendar cita</button>
 </section>
 <section class="card">
  <div class="card-head"><div><h2>Acciones rápidas</h2><p>Operaciones frecuentes</p></div></div>
  <div class="quick">
   <button class="btn btn-plain" onclick="irA('registro')"><strong>📱 Nuevo equipo</strong><small>Registrar recepción</small></button>
   <button class="btn btn-plain" onclick="irA('facturacion')"><strong>🧾 Factura</strong><small>Crear documento</small></button>
   <button class="btn btn-plain" onclick="exportarDatos()"><strong>💾 Respaldo</strong><small>Guardar datos</small></button>
   <button class="btn btn-plain" onclick="document.getElementById('importFile').click()"><strong>📥 Restaurar</strong><small>Importar datos</small></button>
  </div>
 </section>
</aside>
</div>

<section class="card" id="historial" style="margin-top:18px">
 <div class="card-head"><div><h2>Historial de reparaciones</h2><p>Busca y administra todos los equipos registrados</p></div></div>
 <div class="filters"><input id="buscar" placeholder="🔎 Cliente, modelo, IMEI o reparación..." oninput="renderRegistros()"><select id="filtroEstado" onchange="renderRegistros()"><option value="">Todos los estados</option><option>Pendiente</option><option>En reparación</option><option>Reparado</option><option>Entregado</option></select><select id="filtroCategoria" onchange="renderRegistros()"><option value="">Todas las categorías</option><option>Pantalla</option><option>Batería</option><option>Puerto de carga</option><option>Cámara</option><option>Software</option><option>Placa / electrónica</option><option>Audio / micrófono</option><option>Otro</option></select></div>
 <div class="table-wrap"><table><thead><tr><th>Foto</th><th>Cliente</th><th>Equipo</th><th>Categoría</th><th>Servicio</th><th>Estado</th><th>Entrega</th><th>Precio</th><th>Acciones</th></tr></thead><tbody id="lista"></tbody></table></div>
 <div id="vacio" style="padding:25px;text-align:center;color:#8895a8">No hay registros.</div>
</section>

<section class="card" id="facturacion" style="margin-top:18px">
 <div class="card-head"><div><h2>Factura profesional</h2><p>Documento listo para imprimir, guardar como PDF o compartir</p></div><span style="font-size:10px;color:#22a06b;font-weight:800">● DOCUMENTO DIGITAL</span></div>
 <div class="form-grid">
  <div><label>Cliente</label><input id="factCliente"></div><div><label>Teléfono</label><input id="factTelefono"></div><div><label>Celular / modelo</label><input id="factModelo"></div>
  <div><label>IMEI / serial</label><input id="factImei"></div><div><label>Precio (RD$)</label><input id="factPrecio" type="number" min="0" step=".01"></div><div><label>Reparación</label><input id="factReparacion"></div>
  <div><label>N.º factura</label><input id="factNumero" readonly></div><div><label>Fecha</label><input id="factFecha" type="date"></div><div class="span3"><label>Detalle / garantía / observaciones</label><textarea id="factDetalle"></textarea></div>
 </div>
 <div class="form-actions"><button class="btn btn-primary" onclick="generarFacturaPDF()">▣ Descargar PDF</button><button class="btn btn-green" onclick="compartirFactura()">↗ Compartir PDF</button><button class="btn btn-plain" onclick="limpiarFactura()">Limpiar</button></div>
 <div id="invoicePreview" style="margin-top:18px"></div>
</section>

<input id="importFile" type="file" accept=".json,application/json" hidden>
<div class="footer">TORRES MOBIL REPARACIÓN • Gestión de taller y servicio técnico</div>
</div>
</main>
</div>

<div class="modal" id="citaModal"><div class="modal-card"><h2 style="margin-top:0">Agendar cita</h2><div class="form-grid" style="grid-template-columns:1fr 1fr"><div><label>Cliente</label><input id="citaCliente"></div><div><label>Teléfono</label><input id="citaTelefono"></div><div><label>Fecha y hora</label><input id="citaFecha" type="datetime-local"></div><div><label>Tipo</label><select id="citaTipo"><option>Recepción</option><option>Entrega</option><option>Diagnóstico</option><option>Otro</option></select></div><div style="grid-column:1/-1"><label>Nota</label><textarea id="citaNota"></textarea></div></div><div class="form-actions"><button class="btn btn-primary" onclick="guardarCita()">Guardar</button><button class="btn btn-plain" onclick="cerrarCita()">Cancelar</button></div></div></div>
<div class="modal" id="camaraModal"><div class="modal-card"><h2 style="margin-top:0">Cámara del equipo</h2><video id="videoCam" autoplay playsinline style="width:100%;border-radius:11px;background:#07101f"></video><div class="form-actions"><button class="btn btn-primary" onclick="capturarFoto()">📸 Capturar</button><button class="btn btn-plain" onclick="cerrarCamara()">Cancelar</button></div></div></div>
<div class="toast" id="toast"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script>
const $=id=>document.getElementById(id);
let registros=JSON.parse(localStorage.getItem('tm_registros_v2')||'[]'),citas=JSON.parse(localStorage.getItem('tm_citas_v2')||'[]'),editando=-1,fotoActual='',streamCam=null;
function hoy(){return new Date().toISOString().slice(0,10)}
function dinero(n){return Number(n||0).toLocaleString('es-DO',{minimumFractionDigits:2,maximumFractionDigits:2})}
function esc(s){return String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#039;'}[c]))}
function save(){localStorage.setItem('tm_registros_v2',JSON.stringify(registros));localStorage.setItem('tm_citas_v2',JSON.stringify(citas));actualizarDashboard();renderRegistros();renderAgenda()}
function toast(t){$('toast').textContent=t;$('toast').style.display='block';setTimeout(()=>$('toast').style.display='none',2300)}
function irA(id){document.getElementById(id).scrollIntoView({behavior:'smooth',block:'start'})}
$('fecha').value=hoy();$('factFecha').value=hoy();$('factNumero').value='TM-'+Date.now().toString().slice(-7);
$('fotoArchivo').addEventListener('change',e=>{const f=e.target.files[0];if(!f)return;const r=new FileReader();r.onload=()=>setFoto(r.result);r.readAsDataURL(f)});
function setFoto(d){fotoActual=d||'';const im=$('fotoPreview');im.src=fotoActual;im.style.display=fotoActual?'block':'none'}
function quitarFoto(){setFoto('');$('fotoArchivo').value=''}
async function abrirCamara(){
  // Natively habilita el acceso a la cámara; usamos la API estándar del navegador/WebView,
  // que también funciona dentro de la app y mantiene compatibilidad con escritorio.
  try{
    if(!navigator.mediaDevices || !navigator.mediaDevices.getUserMedia){
      toast('La cámara no está disponible; usa Galería.'); return;
    }
    streamCam=await navigator.mediaDevices.getUserMedia({video:{facingMode:{ideal:'environment'},width:{ideal:1280},height:{ideal:720}},audio:false});
    $('videoCam').srcObject=streamCam;$('camaraModal').classList.add('open');
  }catch(e){toast('No se pudo abrir la cámara; usa Galería.')}
}
function capturarFoto(){const v=$('videoCam'),c=$('canvasFoto');c.width=v.videoWidth||1000;c.height=v.videoHeight||750;c.getContext('2d').drawImage(v,0,0,c.width,c.height);setFoto(c.toDataURL('image/jpeg',.82));cerrarCamara();toast('Fotografía guardada')}
function leerRegistro(){return{cliente:$('cliente').value.trim(),telefono:$('telefono').value.trim(),modelo:$('modelo').value.trim(),imei:$('imei').value.trim(),precio:Number($('precio').value||0),categoria:$('categoria').value,reparacion:$('reparacion').value.trim(),estado:$('estado').value,fecha:$('fecha').value,entrega:$('entrega').value,descripcion:$('descripcion').value.trim(),foto:fotoActual,id:Date.now()}}
$('phoneForm').addEventListener('submit',e=>{e.preventDefault();const r=leerRegistro();if(!r.cliente||!r.modelo||!r.reparacion){toast('Completa cliente, modelo y reparación');return}if(editando>=0){r.id=registros[editando].id;registros[editando]=r;toast('Registro actualizado')}else{registros.unshift(r);toast('Equipo registrado')}editando=-1;limpiarRegistro();save();irA('historial')})
function limpiarRegistro(){$('phoneForm').reset();$('fecha').value=hoy();setFoto('');editando=-1}
function editar(i){const r=registros[i];editando=i;['cliente','telefono','modelo','imei','precio','categoria','reparacion','estado','fecha','entrega','descripcion'].forEach(k=>$(k).value=r[k]||'');setFoto(r.foto||'');irA('registro')}
function eliminar(i){if(confirm('¿Eliminar este registro?')){registros.splice(i,1);save();toast('Registro eliminado')}}
function facturar(i){const r=registros[i];$('factCliente').value=r.cliente||'';$('factTelefono').value=r.telefono||'';$('factModelo').value=r.modelo||'';$('factImei').value=r.imei||'';$('factPrecio').value=r.precio||'';$('factReparacion').value=r.reparacion||'';$('factFecha').value=r.fecha||hoy();$('factDetalle').value=r.descripcion||'';$('factNumero').value='TM-'+Date.now().toString().slice(-7);actualizarFactura();irA('facturacion')}
function badge(s){let c=s==='Pendiente'?'b-pendiente':s==='En reparación'?'b-reparacion':s==='Reparado'?'b-reparado':'b-entregado';return '<span class="badge '+c+'">'+esc(s)+'</span>'}
function renderRegistros(){const q=$('buscar')?.value.toLowerCase()||'',fe=$('filtroEstado')?.value||'',fc=$('filtroCategoria')?.value||'';const arr=registros.map((r,i)=>({...r,i})).filter(r=>(!q||`${r.cliente} ${r.modelo} ${r.imei} ${r.reparacion}`.toLowerCase().includes(q))&&(!fe||r.estado===fe)&&(!fc||r.categoria===fc));$('lista').innerHTML=arr.map(r=>`<tr><td>${r.foto?`<img class="thumb" src="${r.foto}">`:'📱'}</td><td><b>${esc(r.cliente)}</b><br><small>${esc(r.telefono)}</small></td><td><b>${esc(r.modelo)}</b><br><small>${esc(r.imei)}</small></td><td>${esc(r.categoria)}</td><td>${esc(r.reparacion)}</td><td>${badge(r.estado)}</td><td>${r.entrega?new Date(r.entrega).toLocaleString('es-DO'):'—'}</td><td><b>RD$ ${dinero(r.precio)}</b></td><td><button class="btn btn-primary" onclick="facturar(${r.i})">Factura</button> <button class="btn btn-amber" onclick="editar(${r.i})">Editar</button> <button class="btn btn-red" onclick="eliminar(${r.i})">×</button></td></tr>`).join('');$('vacio').style.display=arr.length?'none':'block'}
function actualizarDashboard(){$('sTotal').textContent=registros.length;$('sPend').textContent=registros.filter(r=>r.estado==='Pendiente').length;$('sRep').textContent=registros.filter(r=>r.estado==='En reparación').length;$('sReady').textContent=registros.filter(r=>r.estado==='Reparado').length;$('sValue').textContent='RD$ '+dinero(registros.reduce((a,r)=>a+Number(r.precio||0),0))}
function abrirCita(){$('citaModal').classList.add('open');$('citaFecha').value=new Date(Date.now()+3600000).toISOString().slice(0,16)}
function cerrarCita(){$('citaModal').classList.remove('open')}
function guardarCita(){const c={id:Date.now(),cliente:$('citaCliente').value.trim(),telefono:$('citaTelefono').value.trim(),fecha:$('citaFecha').value,tipo:$('citaTipo').value,nota:$('citaNota').value.trim()};if(!c.cliente||!c.fecha){toast('Completa cliente y fecha');return}citas.push(c);save();cerrarCita();['citaCliente','citaTelefono','citaNota'].forEach(id=>$(id).value='');toast('Cita agendada')}
function renderAgenda(){const arr=[...citas].sort((a,b)=>a.fecha.localeCompare(b.fecha)).filter(c=>new Date(c.fecha)>=new Date(Date.now()-86400000));$('agendaLista').innerHTML=arr.length?arr.slice(0,7).map(c=>`<div class="appointment"><b>${esc(c.cliente)} · ${esc(c.tipo)}</b><span>${new Date(c.fecha).toLocaleString('es-DO')}</span><small>${esc(c.nota||'Sin nota')}</small></div>`).join(''):'<p style="color:#8b96a8;font-size:11px">No hay citas próximas.</p>'}
function actualizarFactura(){const f={cliente:$('factCliente').value,telefono:$('factTelefono').value,modelo:$('factModelo').value,imei:$('factImei').value,precio:Number($('factPrecio').value||0),reparacion:$('factReparacion').value,numero:$('factNumero').value,fecha:$('factFecha').value,detalle:$('factDetalle').value};$('invoicePreview').innerHTML=`<div class="invoice-paper"><div class="invoice-head"><div><h3>TORRES MOBIL REPARACIÓN</h3><small>Servicio técnico profesional · Celulares y dispositivos</small></div><div style="text-align:right"><b>FACTURA</b><br><small>${esc(f.numero)}</small><br><small>${esc(f.fecha||'')}</small></div></div><div class="invoice-body"><div class="invoice-info"><div class="ibox"><b>Cliente</b>${esc(f.cliente||'—')}<br>${esc(f.telefono||'—')}</div><div class="ibox"><b>Equipo</b>${esc(f.modelo||'—')}<br>${f.imei?'IMEI / Serial: '+esc(f.imei):''}</div></div><div class="invoice-line"><span><b>${esc(f.reparacion||'Servicio técnico')}</b><br><small>${esc(f.detalle||'')}</small></span><strong>RD$ ${dinero(f.precio)}</strong></div><div class="invoice-total"><span>TOTAL</span><span>RD$ ${dinero(f.precio)}</span></div><p style="font-size:9px;color:#8792a4">Gracias por preferir Torres Mobil Reparación. Conserve este comprobante.</p></div></div>`}
['factCliente','factTelefono','factModelo','factImei','factPrecio','factReparacion','factNumero','factFecha','factDetalle'].forEach(id=>$(id).addEventListener('input',actualizarFactura))
function datosFactura(){return{cliente:$('factCliente').value.trim(),telefono:$('factTelefono').value.trim(),modelo:$('factModelo').value.trim(),imei:$('factImei').value.trim(),precio:Number($('factPrecio').value||0),reparacion:$('factReparacion').value.trim(),numero:$('factNumero').value.trim(),fecha:$('factFecha').value,detalle:$('factDetalle').value.trim()}}
function crearPDF(){const f=datosFactura();if(!f.cliente||!f.modelo||!f.reparacion||!f.precio){toast('Completa cliente, modelo, reparación y precio');return null}const doc=new jspdf.jsPDF();doc.setFillColor(16,24,39);doc.rect(0,0,210,43,'F');doc.setFillColor(52,120,246);doc.rect(0,43,210,3,'F');doc.setTextColor(255,255,255);doc.setFont('helvetica','bold');doc.setFontSize(21);doc.text('TORRES MOBIL REPARACIÓN',15,19);doc.setFont('helvetica','normal');doc.setFontSize(9);doc.text('Servicio técnico profesional · Celulares y dispositivos',15,27);doc.text('FACTURA',195,18,{align:'right'});doc.text('N.º '+f.numero,195,26,{align:'right'});doc.text('Fecha: '+f.fecha,195,34,{align:'right'});doc.setTextColor(15,23,42);doc.setFillColor(247,249,252);doc.roundedRect(15,54,85,35,3,3,'F');doc.roundedRect(110,54,85,35,3,3,'F');doc.setFont('helvetica','bold');doc.setFontSize(10);doc.text('DATOS DEL CLIENTE',20,62);doc.setFont('helvetica','normal');doc.text(doc.splitTextToSize('Nombre: '+f.cliente,75),20,70);doc.text('Teléfono: '+(f.telefono||'N/A'),20,80);doc.setFont('helvetica','bold');doc.text('DATOS DEL EQUIPO',115,62);doc.setFont('helvetica','normal');doc.text(doc.splitTextToSize('Modelo: '+f.modelo,75),115,70);doc.text('IMEI/Serial: '+(f.imei||'N/A'),115,80);doc.setFillColor(226,232,240);doc.rect(15,99,180,9,'F');doc.setFont('helvetica','bold');doc.text('SERVICIO',20,105);doc.text('IMPORTE',190,105,{align:'right'});doc.setFont('helvetica','normal');doc.text(doc.splitTextToSize(f.reparacion,130),20,117);doc.text('RD$ '+dinero(f.precio),190,117,{align:'right'});doc.line(15,125,195,125);let y=137;if(f.detalle){doc.setFont('helvetica','bold');doc.text('DETALLES / GARANTÍA',20,y);doc.setFont('helvetica','normal');doc.setFontSize(9);const n=doc.splitTextToSize(f.detalle,170);doc.text(n,20,y+7);y+=10+n.length*5}y+=12;doc.setFillColor(237,244,255);doc.roundedRect(120,y,75,22,3,3,'F');doc.setTextColor(31,78,155);doc.setFont('helvetica','bold');doc.setFontSize(11);doc.text('TOTAL A PAGAR',125,y+9);doc.setFontSize(14);doc.text('RD$ '+dinero(f.precio),190,y+17,{align:'right'});doc.setTextColor(100,116,139);doc.setFontSize(9);doc.setFont('helvetica','italic');doc.text('Gracias por preferir Torres Mobil Reparación.',105,268,{align:'center'});doc.text('Conserve este comprobante.',105,274,{align:'center'});return doc}
function generarFacturaPDF(){const d=crearPDF();if(d)d.save('Factura_'+datosFactura().numero+'.pdf')}
async function compartirFactura(){
  const d=crearPDF(); if(!d)return;
  const f=datosFactura(),name='Factura_'+f.numero+'.pdf',blob=d.output('blob'),file=new File([blob],name,{type:'application/pdf'});
  // En Natively y navegadores compatibles, Web Share permite enviar el PDF como archivo.
  if(navigator.share && navigator.canShare && navigator.canShare({files:[file]})){
    try{await navigator.share({title:'Factura '+f.numero,text:'Factura de Torres Mobil Reparación',files:[file]});return}catch(e){if(e.name==='AbortError')return}
  }
  d.save(name); setTimeout(()=>alert('El PDF fue descargado. Puedes enviarlo por WhatsApp como documento.'),250);
}
function limpiarFactura(){['factCliente','factTelefono','factModelo','factImei','factPrecio','factReparacion','factDetalle'].forEach(id=>$(id).value='');$('factFecha').value=hoy();$('factNumero').value='TM-'+Date.now().toString().slice(-7);actualizarFactura()}
function exportarDatos(){const data={version:2,fecha:new Date().toISOString(),registros,citas},a=document.createElement('a');a.href=URL.createObjectURL(new Blob([JSON.stringify(data)],{type:'application/json'}));a.download='Torres_Mobil_Respaldo.json';a.click();URL.revokeObjectURL(a.href)}
$('importFile').addEventListener('change',e=>{const f=e.target.files[0];if(!f)return;const r=new FileReader();r.onload=()=>{try{const d=JSON.parse(r.result);if(!Array.isArray(d.registros))throw 0;registros=d.registros;citas=Array.isArray(d.citas)?d.citas:[];save();toast('Datos restaurados')}catch{toast('Respaldo no válido')}};r.readAsText(f)})
actualizarDashboard();renderRegistros();renderAgenda();actualizarFactura();
</script>

</html>
