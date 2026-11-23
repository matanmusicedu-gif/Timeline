<title>ציר הזמן של המוזיקה</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Frank+Ruhl+Libre:wght@500;800;900&family=Assistant:wght@400;600;700&family=Rubik:wght@500;600;700&display=swap">
<style>
/* Layout: sticky tab bar with a mini "century ruler" whose window slides to the open period; one panel per period; teacher "reveal mode" covers blocks with staff-line cards that flip open on click. */
:root{
  --bg:#F4F6F9; --surface:#FFFFFF; --ink:#17202D; --muted:#586376; --line:#DCE1E8;
  --med:#5B4A8B; --ren:#23796A; --bar:#A26A10; --cla:#2C62A0; --rom:#AD3244; --c20:#C4531A;
  --display:"Frank Ruhl Libre", "David Libre", Georgia, serif;
  --body:"Assistant", "Segoe UI", Arial, sans-serif;
  --label:"Rubik", "Segoe UI", Arial, sans-serif;
  --p:var(--ink);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#10141B; --surface:#19202A; --ink:#E8EBF1; --muted:#9BA5B5; --line:#2B3441;
    --med:#A897DD; --ren:#5BC2A7; --bar:#E2AA4B; --cla:#80AEE8; --rom:#EC7E8E; --c20:#F2985F;
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#10141B; --surface:#19202A; --ink:#E8EBF1; --muted:#9BA5B5; --line:#2B3441;
  --med:#A897DD; --ren:#5BC2A7; --bar:#E2AA4B; --cla:#80AEE8; --rom:#EC7E8E; --c20:#F2985F;
  color-scheme:dark;
}
*{box-sizing:border-box}
body{background:var(--bg);color:var(--ink);font-family:var(--body);font-size:17px;line-height:1.6}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:10;background:var(--bg)}
.gut{max-width:1100px;margin:0 auto;padding-left:max(16px, env(safe-area-inset-left, 0px));padding-right:max(16px, env(safe-area-inset-right, 0px))}
.p-med{--p:var(--med)} .p-ren{--p:var(--ren)} .p-bar{--p:var(--bar)}
.p-cla{--p:var(--cla)} .p-rom{--p:var(--rom)} .p-c20{--p:var(--c20)}
h1,h2,h3{font-family:var(--display);text-wrap:balance;margin:0;line-height:1.15}
h2{font-size:clamp(1.5rem,4vw,2rem);font-weight:800}
h3{font-size:1.3rem;font-weight:800}
p{margin:0}
a{color:inherit}
button{font:inherit;color:inherit}
:focus-visible{outline:3px solid var(--cla);outline-offset:2px;border-radius:6px}
.eyebrow{font-family:var(--label);font-size:.8rem;font-weight:600;letter-spacing:.06em;color:var(--muted)}
.lead{color:var(--muted);max-width:62ch}
.num{font-family:var(--label);font-variant-numeric:tabular-nums}

/* Header + toolbar */
.top{padding-block:28px 14px;display:flex;flex-wrap:wrap;align-items:flex-end;justify-content:space-between;gap:14px 24px}
.top h1{font-size:clamp(1.9rem,5vw,2.8rem);font-weight:900}
.tools{display:flex;flex-wrap:wrap;gap:8px;align-items:center}
.tbtn{display:inline-flex;align-items:center;gap:8px;border:1.5px solid var(--line);background:var(--surface);border-radius:999px;padding:7px 14px;font-family:var(--label);font-size:.86rem;font-weight:500;cursor:pointer;transition:border-color .2s,background .2s}
.tbtn:hover{border-color:var(--muted)}
.tbtn:disabled{opacity:.45;cursor:default}
.switch{width:34px;height:20px;border-radius:999px;background:var(--line);position:relative;transition:background .25s;flex:none}
.switch::after{content:"";position:absolute;top:3px;inset-inline-start:3px;width:14px;height:14px;border-radius:50%;background:var(--surface);transition:inset-inline-start .25s}
[aria-pressed="true"] .switch{background:var(--ren)}
[aria-pressed="true"] .switch::after{inset-inline-start:17px}
.tbtn.primary{background:var(--ink);color:var(--bg);border-color:var(--ink)}
body:not(.reveal) .needs-reveal{display:none}

/* Sticky nav */
.nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:5;background:var(--bg);border-bottom:1px solid var(--line)}
.tabs{display:flex;gap:4px;overflow-x:auto;scrollbar-width:none;padding-block:6px 4px}
.tabs::-webkit-scrollbar{display:none}
.tab{flex:none;display:flex;align-items:center;gap:8px;border:0;background:none;padding:9px 14px;border-radius:10px;cursor:pointer;font-family:var(--label);font-size:.93rem;font-weight:500;color:var(--muted);white-space:nowrap;position:relative;transition:color .2s,background .2s}
.tab i{width:10px;height:10px;border-radius:50%;background:var(--p);flex:none;transition:transform .3s}
.tab:hover{background:var(--surface);color:var(--ink)}
.tab[aria-selected="true"]{color:var(--ink);background:var(--surface);font-weight:700;box-shadow:inset 0 -3px 0 var(--p)}
.tab[aria-selected="true"] i{transform:scale(1.35)}
.tab.star{color:var(--ren)}
.mini{position:relative;height:22px;margin-bottom:8px}
.mini .seg{position:absolute;top:8px;height:6px;background:var(--p);border:0;padding:0;cursor:pointer;opacity:.55;transition:opacity .3s}
.mini .seg:hover{opacity:1}
.mini .win{position:absolute;top:2px;height:18px;border:2.5px solid var(--ink);border-radius:5px;min-width:10px;transition:inset-inline-start .7s cubic-bezier(.6,0,.2,1),width .7s cubic-bezier(.6,0,.2,1);pointer-events:none}
.mini .lab{position:absolute;top:2px;font-family:var(--label);font-size:.7rem;color:var(--muted);font-variant-numeric:tabular-nums;pointer-events:none}

/* Panels */
main{padding-block:28px 72px}
.panel{display:flex;flex-direction:column;gap:28px}
@keyframes rise{from{opacity:0;transform:translateY(18px)}}
@keyframes wipe{from{clip-path:inset(0 0 0 100%)}}
@keyframes pop{0%{transform:scale(.6);opacity:0}70%{transform:scale(1.08)}}
.panel.enter .hero .pname{animation:wipe .8s cubic-bezier(.7,0,.2,1) backwards}
.panel.enter .stag{animation:rise .6s cubic-bezier(.2,.7,.2,1) backwards;animation-delay:calc(var(--i,0) * 90ms + 150ms)}

/* Period hero */
.hero{position:relative;overflow:hidden;border-radius:18px;padding:clamp(22px,4vw,40px);background:color-mix(in srgb,var(--p) 11%,var(--surface));display:flex;flex-direction:column;gap:10px}
.hero .ghost{position:absolute;inset-inline-end:-10px;bottom:-34px;font-family:var(--label);font-weight:700;font-size:clamp(5rem,18vw,11rem);line-height:1;color:var(--p);opacity:.08;pointer-events:none;font-variant-numeric:tabular-nums}
.pname{font-size:clamp(2.4rem,8vw,4.4rem);font-weight:900;color:var(--p)}
.bigyears{font-family:var(--label);font-weight:700;font-size:clamp(1.4rem,4vw,2rem);font-variant-numeric:tabular-nums;color:var(--ink)}
.hero .spirit{font-size:clamp(1.1rem,2.6vw,1.35rem);max-width:52ch}

/* Cards */
.cards{display:grid;grid-template-columns:1fr;gap:16px}
@media (min-width:760px){.cards{grid-template-columns:1fr 1fr}.wide{grid-column:span 2}}
.card{background:var(--surface);border:1px solid var(--line);border-radius:14px;padding:20px 22px;display:flex;flex-direction:column;gap:12px;min-width:0}
.card h3{color:var(--p);display:flex;align-items:center;gap:10px}
.card h3 small{font-family:var(--label);font-size:.78rem;font-weight:500;color:var(--muted)}
.comp{list-style:none;margin:0;padding:0;display:flex;flex-direction:column;gap:10px}
.comp li{display:flex;flex-direction:column}
.comp b{font-size:1.08rem}
.comp span{color:var(--muted);font-size:.93rem}
.comp .num{font-size:.82rem;color:var(--p)}
.feats{list-style:none;margin:0;padding:0;display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:10px}
.feats li{background:var(--bg);border-radius:10px;padding:12px 14px;line-height:1.45}
.feats .term{display:block;font-weight:700;color:var(--ink)}
.feats .gloss{color:var(--muted);font-size:.93rem}
.ev{list-style:none;margin:0;padding:0;display:flex;flex-direction:column;gap:0;position:relative}
.ev::before{content:"";position:absolute;inset-inline-start:5px;top:8px;bottom:8px;width:2px;background:var(--line)}
.ev li{position:relative;padding-inline-start:26px;padding-block:5px;display:flex;flex-direction:column}
.ev li::before{content:"";position:absolute;inset-inline-start:0;top:12px;width:12px;height:12px;border-radius:50%;background:var(--surface);border:2.5px solid var(--p)}
.ev li.music::before{background:var(--p)}
.ev b{font-family:var(--label);font-size:.82rem;color:var(--p);font-variant-numeric:tabular-nums}
.keyhint{font-size:.82rem;color:var(--muted);display:flex;gap:6px;align-items:center}
.keyhint i{width:9px;height:9px;border-radius:50%;background:var(--p);display:inline-block}
.tracks{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:12px}
.track{background:var(--bg);border-radius:10px;padding:14px 16px;display:flex;flex-direction:column;gap:6px;min-width:0}
.track .t{font-weight:700;font-size:1.06rem;line-height:1.35}
.track .o{color:var(--muted);font-size:.9rem;unicode-bidi:plaintext;text-align:start}
.track .meta{font-size:.9rem;color:var(--muted)}
.track .warn{font-size:.88rem;border-inline-start:3px solid var(--p);padding-inline-start:10px}
.links{display:flex;flex-wrap:wrap;gap:8px;margin-top:4px}
.yt{display:inline-flex;align-items:center;gap:7px;text-decoration:none;font-family:var(--label);font-weight:600;font-size:.85rem;padding:6px 13px;border-radius:999px;border:1.5px solid var(--p);color:var(--p);transition:background .2s,color .2s}
.yt:hover{background:var(--p);color:var(--surface)}
.yt svg{width:14px;height:14px;fill:currentColor}
.yt.sub{border-style:dashed;font-weight:500}
.bridge{background:color-mix(in srgb,var(--p) 8%,var(--surface))}
.bridge p{font-size:1.08rem;max-width:70ch}
.pager{display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
.pbtn{display:inline-flex;align-items:center;gap:10px;border:1.5px solid var(--line);background:var(--surface);border-radius:12px;padding:10px 16px;cursor:pointer;font-family:var(--label);font-weight:600}
.pbtn:hover{border-color:var(--p)}
.pbtn i{width:10px;height:10px;border-radius:50%;background:var(--p)}

/* Reveal covers */
.rv{position:relative}
.cover{position:absolute;inset:0;z-index:2;border:0;border-radius:inherit;cursor:pointer;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:4px;padding:8px;
  background:color-mix(in srgb,var(--p) 16%,var(--surface));color:var(--p);
  transform-origin:top center;transition:transform .55s cubic-bezier(.6,0,.3,1),opacity .45s ease .1s;overflow:hidden}
.cover::before{content:"";position:absolute;inset-inline:0;top:50%;height:49px;transform:translateY(-50%);
  background:repeating-linear-gradient(to bottom,transparent 0 11px,var(--p) 11px 12.5px);opacity:.22}
.cover span{position:relative;font-family:var(--display);font-weight:800;font-size:1.25rem;line-height:1.2;text-align:center}
.cover small{position:relative;font-family:var(--label);font-size:.78rem;font-weight:500;opacity:.85}
.cover .note{position:relative;font-size:1.6rem;line-height:1;transition:transform .3s}
.cover:hover .note{transform:translateY(-4px) rotate(-8deg)}
.cover:hover{background:color-mix(in srgb,var(--p) 24%,var(--surface))}
body:not(.reveal) .cover,.rv.shown .cover{transform:perspective(900px) rotateX(-92deg);opacity:0;pointer-events:none;visibility:hidden;transition:transform .55s cubic-bezier(.6,0,.3,1),opacity .45s ease .1s,visibility 0s .6s}
body.reveal .rv:not(.shown) > :not(.cover){visibility:hidden}
.rv.just > :not(.cover){animation:rise .55s cubic-bezier(.2,.7,.2,1) .18s backwards}
td.rv .cover{border-radius:0}
td.rv .cover span{font-size:1.5rem}
td.rv .cover::before{height:25px}

/* Overview */
.ruler-box{overflow-x:auto;padding-bottom:4px}
.ruler{position:relative;min-width:680px;height:96px}
.ruler .bar{position:absolute;top:0;inset-inline:0;height:46px;border-radius:8px;overflow:hidden}
.ruler .seg{position:absolute;top:0;bottom:0;background:var(--p);border:0;border-inline-start:2px solid var(--bg);padding:0;cursor:pointer;transition:filter .2s}
.ruler .seg:hover{filter:brightness(1.12)}
.ruler .seg span{position:absolute;inset-inline-start:10px;top:50%;transform:translateY(-50%);color:var(--bg);font-family:var(--label);font-weight:600;font-size:.85rem;white-space:nowrap}
.tick{position:absolute;top:46px;transform:translateX(50%);display:flex;flex-direction:column;align-items:center;font-family:var(--label);font-size:.78rem;font-variant-numeric:tabular-nums;color:var(--muted)}
.tick::before{content:"";width:1px;height:8px;background:var(--muted)}
.tick.low::before{height:26px}
.panel.enter .ruler .seg{animation:grow .8s cubic-bezier(.2,.7,.2,1) backwards;animation-delay:calc(var(--i) * 110ms + 100ms)}
@keyframes grow{from{clip-path:inset(0 0 0 100%)}}
.legend{display:flex;flex-wrap:wrap;gap:8px 18px;margin:0;padding:0;list-style:none}
.legend li{display:flex;align-items:center;gap:8px;font-size:.95rem}
.legend i{width:12px;height:12px;border-radius:3px;background:var(--p);flex:none}
.legend b{font-family:var(--label);font-weight:600;font-variant-numeric:tabular-nums}
.callout{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:14px 18px}
.callout strong{color:var(--rom)}
.block{display:flex;flex-direction:column;gap:14px}
.spine{list-style:none;margin:0;padding:0;position:relative;display:flex;flex-direction:column;gap:14px}
.spine::before{content:"";position:absolute;inset-inline-start:13px;top:10px;bottom:10px;width:3px;border-radius:2px;background:linear-gradient(to bottom,var(--med),var(--ren),var(--bar),var(--cla),var(--rom),var(--c20))}
.era{position:relative;margin-inline-start:44px;background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:14px 18px;display:flex;flex-direction:column;gap:8px}
.era::before{content:"";position:absolute;inset-inline-start:-40px;top:16px;width:21px;height:21px;border-radius:50%;background:var(--p);box-shadow:0 0 0 5px var(--bg)}
.era-head{display:flex;flex-wrap:wrap;align-items:baseline;gap:4px 14px}
.era-head h3{color:var(--p)}
.era-head .num{color:var(--p);font-weight:600}
.chips{list-style:none;margin:0;padding:0;display:flex;flex-wrap:wrap;gap:6px}
.chips li{background:var(--bg);border-radius:999px;padding:3px 12px;font-size:.9rem}
.chips b{font-family:var(--label);font-size:.78rem;color:var(--p);margin-inline-end:6px;font-variant-numeric:tabular-nums}
.more{align-self:flex-start;border:0;background:none;padding:0;cursor:pointer;font-family:var(--label);font-weight:600;font-size:.88rem;color:var(--p);text-decoration:underline;text-underline-offset:3px}
.table-box{overflow-x:auto;background:var(--surface);border:1px solid var(--line);border-radius:12px}
table{border-collapse:collapse;width:100%;min-width:900px;font-size:.94rem}
th,td{text-align:start;vertical-align:top;padding:13px 14px;border-bottom:1px solid var(--line)}
thead th{font-family:var(--label);font-weight:600;font-size:.8rem;color:var(--muted);background:var(--bg)}
tbody tr:last-child > *{border-bottom:0}
tbody th{border-inline-start:6px solid var(--p);white-space:nowrap}
tbody th .name{display:block;font-family:var(--display);font-size:1.18rem;font-weight:800;color:var(--p)}
td ul{margin:0;padding-inline-start:18px;display:flex;flex-direction:column;gap:3px}
.term{font-weight:700}
.gloss{color:var(--muted)}

/* Palestrina */
.pal .hero{--p:var(--ren)}
.grid2{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:16px}
.parts{display:flex;flex-wrap:wrap;gap:6px}
.parts span{font-family:var(--label);font-size:.85rem;border:1px solid var(--line);border-radius:6px;padding:3px 10px}
.chain{list-style:none;margin:0;padding:0;display:flex;flex-wrap:wrap;gap:8px;align-items:center}
.chain li{background:var(--bg);border-radius:8px;padding:6px 12px;font-size:.95rem}
.chain li b{font-family:var(--label);color:var(--ren);margin-inline-end:6px;font-variant-numeric:tabular-nums}
.chain .arr{background:none;padding:0;color:var(--muted)}
.myth{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px}
.myth > div{border-radius:10px;padding:14px 16px;background:var(--bg)}
.myth b{display:block;font-family:var(--label);font-size:.82rem;margin-bottom:4px}
.myth .m b{color:var(--rom)} .myth .f b{color:var(--ren)}
.card ul.plain{margin:0;padding-inline-start:20px;display:flex;flex-direction:column;gap:6px}
.question{font-family:var(--display);font-size:clamp(1.25rem,3vw,1.6rem);font-weight:500;line-height:1.4}
footer{font-size:.86rem;color:var(--muted);padding-bottom:32px}

@media (prefers-reduced-motion: reduce){
  *,*::before,*::after{animation:none!important;transition:none!important}
}
</style>

<div dir="rtl" lang="he">
  <header class="gut top">
    <div>
      <div class="eyebrow">שיעור מוזיקה · תולדות המוזיקה המערבית</div>
      <h1>ציר הזמן של המוזיקה</h1>
    </div>
    <div class="tools" role="toolbar" aria-label="כלי הצגה">
      <button class="tbtn" id="modeBtn" type="button" aria-pressed="true"><span class="switch" aria-hidden="true"></span>מצב חשיפה הדרגתית</button>
      <button class="tbtn primary needs-reveal" id="nextBtn" type="button">חשיפת הפריט הבא</button>
      <button class="tbtn needs-reveal" id="allBtn" type="button">חשיפת הכול</button>
      <button class="tbtn needs-reveal" id="resetBtn" type="button">כיסוי מחדש</button>
    </div>
  </header>

  <nav class="nav" aria-label="תקופות">
    <div class="gut">
      <div class="tabs" role="tablist" id="tabs"></div>
      <div class="mini" id="mini" aria-hidden="true"></div>
    </div>
  </nav>

  <main class="gut" id="main"></main>

  <footer class="gut">השנים של התקופות משוערות; בספרים שונים תמצאו הבדלים קטנים. קישורי ההאזנה פותחים חיפוש ביוטיוב, כדי שתוכלו לבחור את הביצוע. מקשי החצים עוברים בין הלשוניות, ומקש הרווח חושף את הפריט הבא.</footer>
</div>

<template id="palTpl">
  <div class="hero">
    <span class="ghost">1567</span>
    <span class="eyebrow stag" style="--i:0">נושא השיעור · רנסאנס</span>
    <h2 class="pname">מיסת האפיפיור מרצ'לוס</h2>
    <div class="bigyears stag" style="--i:1">Missa Papae Marcelli · 1567</div>
    <p class="spirit stag" style="--i:2">ג'ובאני פיירלואיג'י דה פלסטרינה (1525–1594). המיסה שלפי האגדה "הצילה" את הפוליפוניה בכנסייה.</p>
    <div class="links stag" style="--i:3"><a class="yt" target="_blank" rel="noopener" href="https://www.youtube.com/results?search_query=Palestrina+Missa+Papae+Marcelli+Tallis+Scholars"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M8 5v14l11-7z"/></svg>האזנה ביוטיוב</a></div>
  </div>
  <div class="cards">
    <article class="card rv stag" style="--i:1" data-label="מי היה פלסטרינה?">
      <h3>מי היה פלסטרינה?</h3>
      <p>נולד ב-1525 בעיירה פלסטרינה ליד רומא, ומשם שמו. כמעט כל חייו ניצח על מקהלות בכנסיות של רומא, כולל בבזיליקת פטרוס הקדוש. כתב יותר ממאה מיסות, וסגנונו נחשב עד היום לדוגמה של פוליפוניה "מושלמת".</p>
    </article>
    <article class="card rv stag" style="--i:2" data-label="מה זו מיסה?">
      <h3>מה זו מיסה?</h3>
      <p>הטקס המרכזי בכנסייה הקתולית. במיסה מולחנים טקסטים קבועים בלטינית:</p>
      <div class="parts" dir="ltr"><span>Kyrie</span><span>Gloria</span><span>Credo</span><span>Sanctus</span><span>Benedictus</span><span>Agnus Dei</span></div>
    </article>
    <article class="card rv wide stag" style="--i:3" data-label="הרקע ההיסטורי">
      <h3>הרקע ההיסטורי</h3>
      <ul class="chain">
        <li><b>1517</b>לותר מבקר את הכנסייה</li><li class="arr">←</li>
        <li>הכנסייה הקתולית מגיבה ברפורמה משלה</li><li class="arr">←</li>
        <li><b>1545–1563</b>מועצת טרנט</li><li class="arr">←</li>
        <li>ביקורת: בפוליפוניה לא שומעים את המילים</li>
      </ul>
      <p>בפוליפוניה כל קול נכנס בזמן אחר, וההברות מתערבבות. חלק מאנשי הכנסייה טענו שהמתפללים כבר לא מבינים מה שרים, ושהמוזיקה מסיחה את הדעת מהתפילה. גם מנגינות של שירי עם חילוניים בתוך מיסות הרגיזו אותם.</p>
      <p>המיסה נקראת על שם האפיפיור מרצ'לוס השני, שכיהן רק 22 יום ב-1555. לפי המסופר, הוא ביקש מהמקהלה שהמוזיקה תתאים לאווירת הטקס ושהמילים יישמעו בבירור.</p>
    </article>
    <article class="card rv wide stag" style="--i:4" data-label="אגדה או היסטוריה?">
      <h3>אגדה או היסטוריה?</h3>
      <div class="myth">
        <div class="m"><b>האגדה</b>המועצה עמדה לאסור לגמרי על פוליפוניה בכנסייה. פלסטרינה כתב את המיסה הזו, הוכיח שאפשר לשמור גם על יופי וגם על בהירות, וכך "הציל את הפוליפוניה".</div>
        <div class="f"><b>מה ידוע באמת</b>המועצה מעולם לא החליטה לאסור פוליפוניה. היא קבעה רק באופן כללי שבמוזיקה בכנסייה לא יהיה שום דבר "טמא" או חילוני. סיפור ההצלה התפרסם רק כעבור עשרות שנים, אבל המיסה אכן מדגימה בדיוק את מה שהכנסייה ביקשה.</div>
      </div>
    </article>
    <article class="card rv wide stag" style="--i:5" data-label="על מה להקשיב?">
      <h3>על מה להקשיב?</h3>
      <ul class="plain">
        <li><strong>שישה קולות:</strong> סופרן, אלט, שני טנורים ושני בסים, בלי כלי נגינה (א-קפלה).</li>
        <li><strong>בהירות הטקסט:</strong> בגלוריה ובקרדו, שבהם הרבה מילים, הקולות שרים לעתים קרובות את אותן הברות יחד, ולכן אפשר להבין את המילים.</li>
        <li><strong>מנגינות זורמות:</strong> הקווים נעים בעיקר בצעדים קטנים, בלי קפיצות חדות.</li>
        <li><strong>צליל מאוזן:</strong> דיסוננסים מעטים, שמופיעים בעדינות ונפתרים מיד. אף קול לא "משתלט" על האחרים.</li>
      </ul>
    </article>
    <article class="card rv stag" style="--i:6" data-label="משימת האזנה">
      <h3>משימת האזנה</h3>
      <p>השוו את הקיריה (מעט מילים, הקולות נכנסים בזה אחר זה) לגלוריה (הרבה מילים, הקולות שרים יחד). באיזה מהם קל יותר להבין את הטקסט, ולמה?</p>
    </article>
    <article class="card bridge rv stag" style="--i:7" data-label="שאלה לדיון">
      <h3>שאלה לדיון</h3>
      <p class="question">האם מוזיקה בטקס דתי צריכה קודם כול לשרת את המילים, או שמותר לה להיות יפה בפני עצמה גם אם לא מבינים מה שרים?</p>
    </article>
  </div>
</template>

<script>
(function(){
const PLAY='<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M8 5v14l11-7z"/></svg>';
const yt=q=>'https://www.youtube.com/results?search_query='+encodeURIComponent(q).replace(/%20/g,'+');
const F=(t,g,x)=>({t,g,x});

const P=[
{id:'medieval',cls:'p-med',name:'ימי הביניים',pre:'כ-',s:500,e:1400,
 spirit:'המוזיקה משרתת את הכנסייה: קול אחד, טקסט בלטינית, תפילה.',
 composers:[['הילדגרד פון בינגן','1098–1179','נזירה, הוגה ומלחינה, מהראשונות שאנו יודעים את שמן'],['פרוטן','פעל כ-1200','אסכולת נוטרדאם בפריז: אורגנום לארבעה קולות'],['גיום דה מאשו','כ-1300–1377','"מיסת נוטרדאם", מהמיסות השלמות הראשונות שכתב מלחין אחד']],
 features:[F('מונופוניה','קו מנגינה אחד, בלי ליווי','השירה הגרגוריאנית'),F('מודוסים','הסולמות של הכנסייה',''),F('אורגנום','קול שני שמצטרף למנגינה','ראשית הפוליפוניה'),F('כתב תווים','',"לידת התווים על קווים, ושירי טרובדורים חילוניים")],
 events:[['476','נפילת האימפריה הרומית המערבית'],['800','הכתרת קרל הגדול'],['כ-1025','גואידו מארצו: תווים על קווים ושמות הצלילים',1],['1096','מסע הצלב הראשון'],['1348','המגפה השחורה']],
 world:['הכנסייה במרכז החיים','מסעי הצלב','המגפה השחורה'],
 bridge:'הקול השני שנוסף לשירה הגרגוריאנית הופך בהדרגה לכמה קולות עצמאיים. ההומניזם מעביר את המבט מאלוהים אל האדם.',
 tracks:[
  {t:'בראשית',o:'Hildegard von Bingen – In principio omnes (Ordo Virtutum)',meta:'הילדגרד פון בינגן · כ-1151',links:[['האזנה ביוטיוב','Hildegard von Bingen In principio omnes']]},
  {t:'עת לעינוגים, מתוך "כרמינה בוראנה"',o:'Carmina Burana – Tempus est iocundum',meta:'המילים מכתב יד מכ-1230',warn:'הלחן המוכר הוא של קרל אורף מ-1937, כלומר מהמאה ה-20. אפשר לשאול את הכיתה מה כאן ימי-ביניימי ומה לא, ולהשוות לביצוע של השירים המקוריים.',links:[['הגרסה של אורף','Orff Carmina Burana Tempus est iocundum'],['השירים המקוריים','Carmina Burana medieval Codex Buranus songs',1]]}
 ]},
{id:'renaissance',cls:'p-ren',name:'רנסאנס',pre:'',s:1400,e:1600,
 spirit:'"לידה מחדש": האדם במרכז, השראה מיוון ומרומא, איזון ויופי.',
 composers:[["ז'וסקן דה פרה",'כ-1450–1521','"הנסיך של המוזיקה": מיסות, מוטטים ושירים'],['פלסטרינה','1525–1594','מוזיקת כנסייה, יותר ממאה מיסות'],['אורלנדו די לאסו','1532–1594','יותר מ-2,000 יצירות בכל סגנון ושפה']],
 features:[F('פוליפוניה חיקויית','כמה קולות עצמאיים שמחקים זה את זה',''),F('א-קפלה','שירה בלי כלי נגינה','רוב המוזיקה החשובה היא ווקאלית'),F('צליל רך ומאוזן','','הרבה טרצות וסקסטות, מעט דיסוננסים'),F('ציור מילים','המוזיקה מתארת את המילה','מיסה, מוטט ומדריגל')],
 events:[['כ-1450','הדפוס של גוטנברג'],['1492','קולומבוס מגיע לאמריקה'],['1501','פטרוצ\'י מדפיס תווים לראשונה',1],['1517','לותר והרפורמה הפרוטסטנטית'],['1545–1563','מועצת טרנט']],
 world:['הדפוס','גילוי אמריקה','הרפורמה ומועצת טרנט'],
 bridge:'רוצים לשמוע את המילים ולהרגיש דרמה. במקום הרבה קולות שווים: מנגינה אחת מעל קו בס. כך נולדת האופרה.',
 tracks:[
  {t:'הצרצר',o:'Josquin des Prez – El Grillo',meta:"ז'וסקן דה פרה · פורסם 1505 · פרוטולה (שיר חילוני איטלקי)",links:[['האזנה ביוטיוב','Josquin El Grillo']]},
  {t:"מיסת האפיפיור מרצ'לוס",o:'Palestrina – Missa Papae Marcelli',meta:'פלסטרינה · פורסמה 1567 · נושא השיעור',links:[['האזנה ביוטיוב','Palestrina Missa Papae Marcelli Tallis Scholars']]}
 ]},
{id:'baroque',cls:'p-bar',name:'בארוק',pre:'',s:1600,e:1750,
 spirit:'דרמה, ניגודים וקישוטים, כמו הארמונות והכנסיות המפוארים של התקופה.',
 composers:[['מונטוורדי','1567–1643','"אורפיאו", מהאופרות הראשונות'],['ויוואלדי','1678–1741','"ארבע העונות"'],['באך','1685–1750','פוגות, קנטטות, "הפסיון כמתי"'],['הנדל','1685–1759','האורטוריה "משיח"']],
 features:[F('באסו קונטינואו','קו בס וכלי אקורדים שמלווים כל הזמן',''),F('לידת האופרה','','סיפור שלם מושר על הבמה'),F('ניגודים','חזק מול חלש, סולן מול תזמורת',''),F('מז׳ור ומינור','','פוגה, קונצ\'רטו, סוויטה וקנטטה; צ\'מבלו ועוגב')],
 events:[['1607','"אורפיאו" של מונטוורדי',1],['1618–1648','מלחמת שלושים השנה'],['1643–1715','לואי ה-14 ומלוכה מוחלטת'],['1687','ניוטון וחוקי התנועה'],['1750','מות באך: סוף התקופה',1]],
 world:['מלחמת שלושים השנה','מלכים בעלי כוח מוחלט','המהפכה המדעית'],
 bridge:'אחרי באך הטעם משתנה: מהמורכב והמקושט אל הפשוט והבהיר. קהל חדש של אזרחים מתחיל ללכת לקונצרטים.',
 tracks:[
  {t:"סוויטה מס' 1 לצ'לו סולו, פרלוד",o:'J.S. Bach – Cello Suite No. 1 in G major, BWV 1007',meta:'באך · כ-1720',links:[['האזנה ביוטיוב','Bach Cello Suite No 1 BWV 1007 Prelude']]},
  {t:'קנטטה "התעוררו, קורא לנו הקול"',o:'J.S. Bach – Wachet auf, ruft uns die Stimme, BWV 140',meta:'באך · 1731',links:[['האזנה ביוטיוב','Bach Cantata BWV 140 Wachet auf']]}
 ]},
{id:'classical',cls:'p-cla',name:'קלאסי',pre:'',s:1750,e:1820,
 spirit:'סדר, בהירות ואיזון. מוזיקה ברוח הנאורות.',
 composers:[['היידן','1732–1809','"אבי הסימפוניה": 104 סימפוניות'],['מוצרט','1756–1791','יותר מ-600 יצירות, אופרות וקונצ\'רטים'],['בטהובן','1770–1827','9 סימפוניות; הגשר לרומנטיקה']],
 features:[F('הומופוניה','מנגינה ברורה עם ליווי',''),F('משפטים מאוזנים','','כמו שאלה ותשובה'),F('צורת סונטה','הצגה, פיתוח, חזרה',''),F('כלים והרכבים','','הסימפוניה ורביעיית המיתרים; הפסנתר מחליף את הצ\'מבלו')],
 events:[['המאה ה-18','תנועת הנאורות: שכל, מדע, זכויות האדם'],['1776','הכרזת העצמאות האמריקנית'],['1786','"נישואי פיגארו" של מוצרט',1],['1789','המהפכה הצרפתית'],['1799–1815','נפוליאון']],
 world:['הנאורות','המהפכה האמריקנית והצרפתית','נפוליאון'],
 bridge:'בטהובן מותח את הצורות הקלאסיות עד הקצה. רעיונות החירות מהמהפכות מביאים רצון לביטוי אישי.',
 tracks:[
  {t:'נישואי פיגארו, פתיחה',o:'Mozart – Le nozze di Figaro, K. 492: Overture',meta:'מוצרט · 1786 · אופרה',links:[['האזנה ביוטיוב','Mozart Le nozze di Figaro Overture']]},
  {t:'הסימפוניה החמישית, פרק ראשון',o:'Beethoven – Symphony No. 5 in C minor, Op. 67',meta:'בטהובן · 1808 · כבר מצביעה לכיוון הרומנטיקה',links:[['האזנה ביוטיוב','Beethoven Symphony No 5 first movement']]}
 ]},
{id:'romantic',cls:'p-rom',name:'רומנטי',pre:'',s:1820,e:1900,
 spirit:'רגש, דמיון, טבע והעולם הפנימי של האמן. המלחין כגיבור.',
 composers:[['שוברט','1797–1828','יותר מ-600 לידים'],['מנדלסון','1809–1847','קונצ\'רטו לכינור, "חלום ליל קיץ"'],['שופן','1810–1849','"משורר הפסנתר"'],['ואגנר, ורדי, ברהמס, צ\'ייקובסקי','','אופרות ענק, סימפוניות ובלטים']],
 features:[F('רגש עז','','ניגודים קיצוניים בעוצמה ובקצב'),F('תזמורת גדולה','','יותר כלים, יותר צבעים'),F('כרומטיקה','צלילים מחוץ לסולם',''),F('ליד','שיר אמנותי לקול ופסנתר','גם מוזיקה שמספרת סיפור, וירטואוזים ולאומיות')],
 events:[['המאה ה-19','המהפכה התעשייתית: כלים משוכללים, אולמות גדולים'],['1824','הסימפוניה התשיעית של בטהובן',1],['1848','"אביב העמים": מהפכות ברחבי אירופה'],['המאה ה-19','עליית הלאומיות']],
 world:['המהפכה התעשייתית','אביב העמים 1848','עליית הלאומיות'],
 bridge:'ההרמוניה נעשית כרומטית יותר ויותר, עד שהטונליות כמעט נשברת. מלחמות וטכנולוגיה משנות את העולם.',
 tracks:[
  {t:"קונצ'רטו לכינור במי מינור, אופוס 64",o:'Mendelssohn – Violin Concerto in E minor, Op. 64',meta:'מנדלסון · 1844',links:[['האזנה ביוטיוב','Mendelssohn Violin Concerto E minor Op 64']]},
  {t:'הליד "השמך" וחמישיית "השמך"',o:'Schubert – Die Forelle, D. 550 · Trout Quintet, D. 667',meta:'שוברט · 1817 ו-1819 · פרק 4 בחמישייה הוא וריאציות על מנגינת השיר. כדאי להשמיע קודם את השיר.',links:[['הליד','Schubert Die Forelle D 550 lied'],['החמישייה, פרק 4','Schubert Trout Quintet D 667 4th movement']]}
 ]},
{id:'modern',cls:'p-c20',name:'המאה ה-20',pre:'',s:1900,e:2000,
 spirit:'שוברים את הכללים: הרבה סגנונות במקביל, ניסויים וצלילים חדשים.',
 composers:[['דביסי','1862–1918','אימפרסיוניזם: צבעים וצלילים מעורפלים'],['סטרווינסקי','1882–1971','"פולחן האביב"'],['שנברג','1874–1951','שיטת 12 הטונים'],['גרשווין','1898–1937','"רפסודיה בכחול", "פורגי ובס"'],['פאול בן-חיים','1897–1984','עלה ב-1933; מאבות המוזיקה הישראלית']],
 features:[F('אטונליות','בלי צליל מרכזי','ושיטת 12 הטונים'),F('מקצבים לא סדירים','',''),F('ג׳אז ומוזיקה עממית','','משפיעים על המוזיקה הקלאסית'),F('צלילים חדשים','','מוזיקה אלקטרונית, מינימליזם, ובישראל "הסגנון הים-תיכוני"')],
 events:[['1913','"פולחן האביב": שערורייה בבכורה',1],['1914–1918','מלחמת העולם הראשונה'],['1924','"רפסודיה בכחול"',1],['1939–1945','מלחמת העולם השנייה והשואה'],['1948','קום מדינת ישראל']],
 world:['שתי מלחמות עולם והשואה','קום המדינה','הקלטה, רדיו וטלוויזיה'],
 bridge:'',
 tracks:[
  {t:'רפסודיה בכחול',o:'Gershwin – Rhapsody in Blue',meta:'גרשווין · 1924 · מפגש בין ג\'אז לתזמורת סימפונית',links:[['האזנה ביוטיוב','Gershwin Rhapsody in Blue']]},
  {t:'נעים זמירות ישראל',o:'Paul Ben-Haim – The Sweet Psalmist of Israel',meta:"פאול בן-חיים · 1953 · לצ'מבלו, נבל ותזמורת מיתרים · פרס ישראל 1957",links:[['האזנה ביוטיוב','Paul Ben-Haim Sweet Psalmist of Israel']]}
 ]}
];

const TABS=[{id:'overview',name:'סקירה וציר זמן',cls:''},...P.map(p=>({id:p.id,name:p.name,cls:p.cls})),{id:'palestrina',name:'נושא השיעור: פלסטרינה',cls:'p-ren',star:1}];
const pct=y=>((y-500)/1500*100);
const esc=s=>s;

/* ---------- tabs + mini ruler ---------- */
const tabsEl=document.getElementById('tabs');
tabsEl.innerHTML=TABS.map(t=>`<button class="tab ${t.cls}${t.star?' star':''}" role="tab" id="tab-${t.id}" aria-controls="panel-${t.id}" aria-selected="false" tabindex="-1" data-go="${t.id}">${t.id==='overview'?'':'<i></i>'}${t.name}</button>`).join('');
const mini=document.getElementById('mini');
mini.innerHTML=P.map(p=>`<button class="seg ${p.cls}" data-go="${p.id}" tabindex="-1" style="inset-inline-start:${pct(p.s)}%;width:${pct(p.e)-pct(p.s)}%"></button>`).join('')+
  `<span class="lab" style="inset-inline-start:0">500</span><span class="lab" style="inset-inline-end:0">2000</span><div class="win" id="win"></div>`;
const win=document.getElementById('win');

/* ---------- panels ---------- */
const main=document.getElementById('main');
const panel=(id,cls,html)=>`<section class="panel ${cls}" id="panel-${id}" role="tabpanel" aria-labelledby="tab-${id}" hidden>${html}</section>`;

function overviewHTML(){
  const segs=P.map((p,i)=>`<button class="seg ${p.cls}" style="--i:${i};inset-inline-start:${pct(p.s)}%;width:${pct(p.e)-pct(p.s)}%" data-go="${p.id}" aria-label="${p.name}">${(p.e-p.s)>=150?`<span>${p.name}</span>`:''}</button>`).join('');
  const ticks=[[500],[800],[1100],[1400],[1600],[1750],[1820,1],[1900],[2000,1]].map(([y,l])=>`<div class="tick${l?' low':''}" style="right:${pct(y)}%">${y}</div>`).join('');
  const legend=P.map(p=>`<li class="${p.cls}"><i></i>${p.name} <b>${p.pre?'כ-':''}${p.e-p.s} שנה</b></li>`).join('');
  const spine=P.map((p,i)=>`<li class="era rv stag ${p.cls}" style="--i:${i+3}" data-label="${p.name}"><div class="era-head"><h3>${p.name}</h3><span class="num">${p.pre}${p.s}–${p.e}</span></div><p>${p.spirit}</p><ul class="chips">${p.events.map(e=>`<li><b>${e[0]}</b>${e[1]}</li>`).join('')}</ul><button class="more" type="button" data-go="${p.id}">לדף התקופה ←</button></li>`).join('');
  const rows=P.map(p=>`<tr class="${p.cls}"><th scope="row"><span class="name">${p.name}</span><span class="num">${p.pre}${p.s}–${p.e}</span></th>
    <td class="rv" data-label="?"><ul>${p.composers.map(c=>`<li>${c[0]}${c[1]?` <span class="num gloss">(${c[1]})</span>`:''}</li>`).join('')}</ul></td>
    <td class="rv" data-label="?"><ul>${p.features.map(f=>`<li><span class="term">${f.t}</span>${f.g?` <span class="gloss">(${f.g})</span>`:''}</li>`).join('')}</ul></td>
    <td class="rv" data-label="?"><ul>${p.world.map(w=>`<li>${w}</li>`).join('')}</ul></td></tr>`).join('');
  return `
  <div class="block stag" style="--i:0">
    <div><div class="eyebrow">במבט אחד</div><h2>שש תקופות, 1,500 שנה</h2></div>
    <p class="lead">לחצו על תקופה בסרגל או בלשוניות כדי לפתוח את הדף שלה.</p>
    <div class="ruler-box"><div class="ruler" role="group" aria-label="סרגל זמן יחסי משנת 500 עד 2000"><div class="bar">${segs}</div>${ticks}</div></div>
    <ul class="legend">${legend}</ul>
  </div>
  <p class="callout stag" style="--i:1"><strong>שימו לב:</strong> ימי הביניים ארוכים יותר מכל שאר התקופות ביחד. ככל שמתקרבים לימינו, הסגנונות מתחלפים מהר יותר. השנים משוערות, והמעברים בין התקופות הדרגתיים.</p>
  <div class="block">
    <div class="stag" style="--i:2"><div class="eyebrow">ציר הזמן</div><h2>מה קרה בכל תקופה</h2></div>
    <ol class="spine">${spine}</ol>
  </div>
  <div class="block stag" style="--i:9">
    <div><div class="eyebrow">טבלת סיכום</div><h2>התקופות בטבלה אחת</h2></div>
    <div class="table-box"><table><thead><tr><th scope="col">תקופה</th><th scope="col">מלחינים בולטים</th><th scope="col">מאפיינים מוזיקליים</th><th scope="col">בעולם באותו זמן</th></tr></thead><tbody>${rows}</tbody></table></div>
  </div>`;
}

function periodHTML(p,i){
  const prev=TABS[i], next=TABS[i+2];
  const comp=p.composers.map(c=>`<li><b>${c[0]}</b>${c[1]?`<span class="num">${c[1]}</span>`:''}<span>${c[2]}</span></li>`).join('');
  const feats=p.features.map(f=>`<li><span class="term">${f.t}</span>${f.g?`<span class="gloss">${f.g}</span>`:''}${f.x?`<div>${f.x}</div>`:''}</li>`).join('');
  const ev=p.events.map(e=>`<li${e[2]?' class="music"':''}><b>${e[0]}</b>${e[1]}</li>`).join('');
  const tracks=p.tracks.map(t=>`<div class="track"><span class="t">${t.t}</span><span class="o" dir="ltr">${t.o}</span><span class="meta">${t.meta}</span>${t.warn?`<span class="warn">${t.warn}</span>`:''}<div class="links">${t.links.map(l=>`<a class="yt${l[2]?' sub':''}" target="_blank" rel="noopener" href="${yt(l[1])}">${PLAY}${l[0]}</a>`).join('')}</div></div>`).join('');
  const bridge=p.bridge?`<article class="card bridge wide rv stag" style="--i:5" data-label="מה הלאה?"><h3>בדרך ל${next.name}</h3><p>${p.bridge}</p></article>`:
    `<article class="card bridge wide rv stag" style="--i:5" data-label="ועכשיו?"><h3>ועכשיו: חזרה לרנסאנס</h3><p>סיימנו את הסיור בציר הזמן. עכשיו נחזור 400 שנה אחורה, אל רומא של המאה ה-16, ליצירה אחת: מיסת האפיפיור מרצ'לוס.</p></article>`;
  return `
  <div class="hero">
    <span class="ghost num">${p.s}</span>
    <span class="eyebrow stag" style="--i:0">תקופה ${i+1} מתוך 6</span>
    <h2 class="pname">${p.name}</h2>
    <div class="bigyears stag" style="--i:1">${p.pre}<span class="cnt" data-to="${p.s}">${p.s}</span>–<span class="cnt" data-to="${p.e}">${p.e}</span></div>
    <p class="spirit stag" style="--i:2">${p.spirit}</p>
  </div>
  <div class="cards">
    <article class="card rv stag" style="--i:1" data-label="מלחינים בולטים"><h3>מלחינים בולטים</h3><ul class="comp">${comp}</ul></article>
    <article class="card rv stag" style="--i:2" data-label="בעולם באותו זמן"><h3>בעולם באותו זמן</h3><ul class="ev">${ev}</ul><span class="keyhint"><i></i>נקודה מלאה = אירוע מוזיקלי</span></article>
    <article class="card rv wide stag" style="--i:3" data-label="איך זה נשמע?"><h3>איך זה נשמע?</h3><ul class="feats">${feats}</ul></article>
    <article class="card rv wide stag" style="--i:4" data-label="להאזנה"><h3>להאזנה</h3><div class="tracks">${tracks}</div></article>
    ${bridge}
  </div>
  <div class="pager">
    <button class="pbtn ${prev.cls}" type="button" data-go="${prev.id}">→ ${prev.cls?'<i></i>':''}${prev.name}</button>
    <button class="pbtn ${next.cls}" type="button" data-go="${next.id}">${next.cls?'<i></i>':''}${next.name} ←</button>
  </div>`;
}

main.innerHTML=panel('overview','',overviewHTML())+P.map((p,i)=>panel(p.id,p.cls,periodHTML(p,i))).join('')+panel('palestrina','pal p-ren','');
document.getElementById('panel-palestrina').appendChild(document.getElementById('palTpl').content.cloneNode(true));
const lastPager=document.createElement('div');lastPager.className='pager';
lastPager.innerHTML=`<button class="pbtn p-c20" type="button" data-go="modern">→ <i></i>המאה ה-20</button><button class="pbtn" type="button" data-go="overview">חזרה לסקירה ←</button>`;
document.getElementById('panel-palestrina').appendChild(lastPager);

/* ---------- reveal covers ---------- */
document.querySelectorAll('.rv').forEach(el=>{
  const b=document.createElement('button');
  b.type='button';b.className='cover';
  const lab=el.dataset.label||'';
  b.setAttribute('aria-label','חשיפה: '+(lab==='?'?'תא בטבלה':lab));
  b.innerHTML=lab==='?'?'<span>?</span>':`<span class="note" aria-hidden="true">♪</span><span>${lab}</span><small>לחצו לחשיפה</small>`;
  b.addEventListener('click',e=>{e.stopPropagation();reveal(el)});
  el.prepend(b);
});
function reveal(el){if(el.classList.contains('shown'))return;el.classList.add('shown','just');setTimeout(()=>el.classList.remove('just'),900);updateBtns()}
const store={get(k){try{return localStorage.getItem(k)}catch(e){return null}},set(k,v){try{localStorage.setItem(k,v)}catch(e){}}};
const modeBtn=document.getElementById('modeBtn'),nextBtn=document.getElementById('nextBtn'),allBtn=document.getElementById('allBtn'),resetBtn=document.getElementById('resetBtn');
let revealMode=store.get('revealMode')!=='off';
function applyMode(){document.body.classList.toggle('reveal',revealMode);modeBtn.setAttribute('aria-pressed',String(revealMode));updateBtns()}
modeBtn.addEventListener('click',()=>{revealMode=!revealMode;store.set('revealMode',revealMode?'on':'off');applyMode()});
const hiddenIn=()=>current?[...current.querySelectorAll('.rv:not(.shown)')]:[];
function updateBtns(){const n=hiddenIn().length;nextBtn.disabled=!n;allBtn.disabled=!n;resetBtn.disabled=!current||!current.querySelector('.rv.shown')}
function revealNext(){const h=hiddenIn();if(!h.length)return;reveal(h[0]);const r=h[0].getBoundingClientRect();if(r.bottom>innerHeight||r.top<120)h[0].scrollIntoView({behavior:matchMedia('(prefers-reduced-motion: reduce)').matches?'auto':'smooth',block:'center'})}
nextBtn.addEventListener('click',revealNext);
allBtn.addEventListener('click',()=>{hiddenIn().forEach((el,i)=>setTimeout(()=>reveal(el),i*70))});
resetBtn.addEventListener('click',()=>{current.querySelectorAll('.rv.shown').forEach(el=>el.classList.remove('shown','just'));updateBtns()});

/* ---------- navigation ---------- */
let current=null,currentId=null;
const ids=TABS.map(t=>t.id);
const reduce=()=>matchMedia('(prefers-reduced-motion: reduce)').matches;
function countUp(panel,fromStart){
  const els=panel.querySelectorAll('.cnt');if(!els.length)return;
  els.forEach((el,k)=>{const to=+el.dataset.to;const from=fromStart?fromStart[k]:to-150;if(reduce()){el.textContent=to;return}
    const t0=performance.now(),d=800;const step=t=>{const x=Math.min(1,(t-t0)/d),e=1-Math.pow(1-x,3);el.textContent=Math.round(from+(to-from)*e);if(x<1)requestAnimationFrame(step)};requestAnimationFrame(step)});
}
function show(id,focusTab){
  if(!ids.includes(id))id='overview';
  if(id===currentId)return;
  const prevP=P.find(p=>p.id===currentId);
  currentId=id;
  TABS.forEach(t=>{const b=document.getElementById('tab-'+t.id),on=t.id===id;b.setAttribute('aria-selected',String(on));b.tabIndex=on?0:-1});
  document.querySelectorAll('.panel').forEach(p=>p.hidden=true);
  current=document.getElementById('panel-'+id);
  current.hidden=false;current.classList.remove('enter');void current.offsetWidth;current.classList.add('enter');
  const p=P.find(x=>x.id===id);
  let s=500,e=2000; if(p){s=p.s;e=p.e} if(id==='palestrina'){s=1525;e=1594}
  win.style.insetInlineStart=pct(s)+'%';win.style.width=(pct(e)-pct(s))+'%';
  win.style.borderColor=p||id==='palestrina'?`var(--${p?p.cls.slice(2):'ren'})`:'var(--ink)';
  countUp(current,prevP?[prevP.s,prevP.e]:null);
  const tab=document.getElementById('tab-'+id);
  tab.scrollIntoView({block:'nearest',inline:'nearest'});
  if(focusTab)tab.focus({preventScroll:true});
  const head=document.querySelector('.top');const lim=head.offsetTop+head.offsetHeight;
  if(scrollY>lim)scrollTo({top:lim});
  if(location.hash!=='#'+id){try{history.replaceState(null,'','#'+id)}catch(err){location.hash=id}}
  updateBtns();
}
document.addEventListener('click',e=>{const g=e.target.closest('[data-go]');if(g){show(g.dataset.go,g.classList.contains('tab'))}});
addEventListener('hashchange',()=>show(location.hash.slice(1)));
document.addEventListener('keydown',e=>{
  if(e.altKey||e.ctrlKey||e.metaKey)return;
  const a=document.activeElement,tag=a&&a.tagName;
  if(tag==='INPUT'||tag==='TEXTAREA')return;
  const i=ids.indexOf(currentId);
  if(e.key==='ArrowLeft'&&i<ids.length-1){e.preventDefault();show(ids[i+1],a&&a.classList.contains('tab'))}
  else if(e.key==='ArrowRight'&&i>0){e.preventDefault();show(ids[i-1],a&&a.classList.contains('tab'))}
  else if(e.key===' '&&(a===document.body||!a||a.tagName==='MAIN')&&document.body.classList.contains('reveal')){e.preventDefault();revealNext()}
});

applyMode();
show(location.hash.slice(1)||'overview');
})();
</script>
