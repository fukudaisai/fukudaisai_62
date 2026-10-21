<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>第62回福大祭 公式ウェブサイト</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Zen+Old+Mincho:wght@700;900&family=Zen+Kaku+Gothic+New:wght@400;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#fbf8f0;--ink:#2a2766;--text:#2b2a3a;--teal:#1f7d86;--gold:#e2a52a;--rust:#d65a24;--pink:#f0309c;--card:#ffffff;--line:#e4dfd0;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#15142b;--ink:#e9e7ff;--text:#dedcf0;--teal:#4fb7c0;--gold:#f0b940;--rust:#f0804a;--pink:#ff5cb8;--card:#1f1e3d;--line:#34325c;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#15142b;--ink:#e9e7ff;--text:#dedcf0;--teal:#4fb7c0;--gold:#f0b940;--rust:#f0804a;--pink:#ff5cb8;--card:#1f1e3d;--line:#34325c;color-scheme:dark}
html{scroll-padding-top:calc(60px + env(safe-area-inset-top,0px));scroll-behavior:smooth}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:"Zen Kaku Gothic New","Hiragino Sans","Yu Gothic",sans-serif;line-height:1.9;font-size:16px}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--bg);z-index:10}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:11;background:var(--bg);border-bottom:1px solid var(--line);display:flex;justify-content:space-between;align-items:center;padding:10px 20px;gap:12px}
header b{font-family:"Zen Old Mincho",serif;color:var(--ink);font-size:18px;white-space:nowrap}
nav{display:flex;gap:18px;overflow-x:auto;font-size:14px}
nav a{color:var(--ink);text-decoration:none;white-space:nowrap;font-weight:700}
nav a:hover,nav a:focus-visible{color:var(--rust);outline:none;text-decoration:underline}
.hero{position:relative;overflow:hidden;padding:64px 24px 0;text-align:center}
.blob{position:absolute;border-radius:50%;z-index:0}
.b1{width:420px;height:420px;background:var(--teal);top:-210px;right:-120px}
.b2{width:300px;height:300px;background:var(--gold);top:-90px;right:-170px;opacity:.9}
.b3{width:260px;height:260px;background:var(--rust);bottom:60px;left:-150px}
.hero>*{position:relative;z-index:1}
.catch{font-family:"Zen Old Mincho",serif;color:var(--rust);font-weight:700;font-size:clamp(17px,4vw,24px);margin:0 0 12px}
.title{font-family:"Zen Old Mincho",serif;font-weight:900;color:var(--ink);margin:0;line-height:1.05;font-size:clamp(88px,26vw,210px);letter-spacing:.02em}
.title small{display:block;font-size:.17em;letter-spacing:.2em;margin-bottom:.4em}
.en{font-family:"Zen Old Mincho",serif;font-style:italic;color:var(--gold);font-size:clamp(24px,6vw,40px);margin:6px 0 28px;font-weight:700}
.date{margin:40px -24px 0;background:var(--gold);color:#1d1b40;font-family:"Zen Old Mincho",serif;font-weight:900;font-size:clamp(22px,6.2vw,52px);padding:18px 10px;line-height:1.3}
.date span{font-size:.6em}
.date small{display:block;font-family:"Zen Kaku Gothic New",sans-serif;font-size:14px;font-weight:700;margin-top:2px}
section{max-width:860px;margin:0 auto;padding:72px 24px 0}
h2{font-family:"Zen Old Mincho",serif;font-weight:900;color:var(--ink);font-size:clamp(28px,6vw,40px);margin:0 0 6px;display:inline-block;border-bottom:6px solid var(--pink);line-height:1.3}
h3{font-family:"Zen Old Mincho",serif;color:var(--teal);font-size:clamp(20px,4.4vw,26px);margin:20px 0 10px}
p{margin:0 0 1.1em;max-width:38em}
.verse{border-left:5px solid var(--rust);padding:2px 0 2px 16px;margin:20px 0;font-family:"Zen Old Mincho",serif;font-weight:700;color:var(--ink);line-height:2}
.sign{text-align:right;font-weight:700;color:var(--ink);max-width:38em}
.live{background:var(--card);border:2px solid var(--ink);border-radius:18px;padding:24px;margin-top:20px}
.live dl{display:grid;grid-template-columns:5.5em 1fr;gap:6px 12px;margin:0}
.live dt{font-weight:700;color:var(--teal)}
.live dd{margin:0}
.live .note{margin:14px 0 0;color:var(--rust);font-size:14px;font-weight:700}
.info{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:20px}
.box{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:22px}
.box h3{margin-top:0}
.box p{margin:0 0 .5em}
a{color:var(--teal);font-weight:700;overflow-wrap:anywhere}
.btn{display:inline-block;background:var(--pink);color:#fff;text-decoration:none;border-radius:999px;padding:10px 24px;margin-top:8px}
.btn:hover,.btn:focus-visible{filter:brightness(.92)}
footer{margin-top:80px;background:var(--ink);color:#fff;text-align:center;padding:36px 20px;font-size:14px}
footer b{font-family:"Zen Old Mincho",serif;font-size:20px;display:block;margin-bottom:6px}
.stripe{height:10px;background:linear-gradient(90deg,var(--teal) 0 25%,var(--gold) 25% 50%,var(--rust) 50% 75%,var(--pink) 75%)}
.group{margin:0 0 28px;max-width:100%}.group img{width:100%;height:auto;display:block;border-radius:18px;border:3px solid var(--ink)}
.chair{margin:22px 0 26px}.chair img{width:100%;max-width:460px;height:auto;display:block;border-radius:18px;border:3px solid var(--pink)}
figcaption{font-size:13px;margin-top:6px;color:var(--text)}
@media (max-width:640px){.info{grid-template-columns:1fr}header b{font-size:15px}}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<header>
  <b>第62回福大祭</b>
  <nav>
    <a href="#theme">テーマ</a>
    <a href="#message">実行委員長挨拶</a>
    <a href="#live">お笑いライブ</a>
    <a href="#access">会場・お問い合わせ</a>
  </nav>
</header>

<div class="hero">
  <div class="blob b1"></div><div class="blob b2"></div><div class="blob b3"></div>
  <p class="catch">今しかない青春を、<br>今しかできない楽しみ方で</p>
  <h1 class="title"><small>第62回</small>福大祭</h1>
  <p class="en">Fukudaisai</p>
  <div class="date">2026.10.31<span>(土)</span> – 11.1<span>(日)</span><small>福島大学 金谷川キャンパス</small></div>
</div>
<div class="stripe"></div>

<section id="theme">
  <figure class="group"><img src="data:image/jpeg;base64,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
