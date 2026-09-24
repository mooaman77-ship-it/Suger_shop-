# Suger_shop-
Hello 👋  in the suger world 
from pathlib import Path
import zipfile

root = Path("/mnt/data/sugar-shop")
img = root / "images"
img.mkdir(parents=True, exist_ok=True)

html = r'''<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#ff5c9a">
<title>Sugar Shop</title>
<style>
:root{
  --pink:#ff5c9a;
  --pink-light:#fff0f6;
  --pink-soft:#ffd6e6;
  --chocolate:#4b241c;
  --chocolate-2:#6b3528;
  --cream:#fffaf7;
  --white:#fff;
  --text:#35201b;
  --shadow:0 12px 30px rgba(75,36,28,.12);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  font-family:Arial,"Tahoma",sans-serif;
  background:linear-gradient(180deg,var(--pink-light),#fff);
  color:var(--text);
}
button,a{font:inherit}
a{text-decoration:none;color:inherit}
.container{width:min(1120px,92%);margin:auto}

header{
  position:sticky;top:0;z-index:20;
  background:rgba(255,255,255,.94);
  backdrop-filter:blur(12px);
  border-bottom:1px solid #ffd5e5;
}
.nav{
  min-height:74px;display:flex;align-items:center;justify-content:space-between;gap:18px;
}
.logo{
  display:flex;align-items:center;gap:10px;
  font-size:25px;font-weight:900;color:var(--chocolate);
}
.logo-badge{
  width:46px;height:46px;border-radius:15px;
  display:grid;place-items:center;background:var(--pink);color:white;
  box-shadow:0 8px 20px rgba(255,92,154,.3);
}
nav{display:flex;gap:18px;flex-wrap:wrap}
nav a{font-weight:700;color:var(--chocolate)}
nav a:hover{color:var(--pink)}

.hero{
  padding:70px 0 45px;
}
.hero-grid{
  display:grid;grid-template-columns:1.1fr .9fr;gap:35px;align-items:center;
}
.badge{
  display:inline-block;padding:8px 14px;border-radius:999px;
  background:var(--pink-soft);color:var(--chocolate);font-weight:800;
}
h1{
  margin:16px 0 12px;font-size:clamp(42px,7vw,76px);
  line-height:.95;color:var(--chocolate);
}
h1 span{color:var(--pink)}
.hero p{font-size:19px;line-height:1.8;max-width:650px}
.cta{
  display:inline-flex;align-items:center;justify-content:center;
  margin-top:12px;padding:14px 24px;border-radius:16px;
  background:var(--pink);color:white;font-weight:900;
  box-shadow:0 10px 25px rgba(255,92,154,.28);
}
.hero-card{
  background:white;border-radius:30px;padding:12px;
  box-shadow:var(--shadow);transform:rotate(2deg);
}
.hero-card img{width:100%;height:390px;object-fit:cover;border-radius:22px;display:block}

.section{padding:55px 0}
.section-title{text-align:center;margin-bottom:30px}
.section-title h2{margin:0;color:var(--chocolate);font-size:34px}
.section-title p{color:#77554c}

.products{
  display:grid;grid-template-columns:repeat(3,1fr);gap:22px;
}
.card{
  background:white;border:1px solid #ffe0eb;border-radius:24px;
  overflow:hidden;box-shadow:var(--shadow);transition:.2s;
}
.card:hover{transform:translateY(-5px)}
.card img{width:100%;height:235px;object-fit:cover;display:block;background:#f6e8e2}
.card-body{padding:18px}
.card h3{margin:0 0 8px;color:var(--chocolate);font-size:21px}
.card p{margin:0 0 14px;color:#76574e;line-height:1.6}
.price{
  display:inline-block;padding:8px 12px;border-radius:12px;
  background:var(--pink-light);color:var(--pink);font-weight:900;
}
.category{
  margin:45px 0 18px;display:flex;align-items:center;gap:12px;
}
.category h3{margin:0;color:var(--chocolate);font-size:25px}
.category:after{content:"";height:2px;flex:1;background:#ffd5e5}

.delivery{
  background:linear-gradient(135deg,var(--chocolate),#7c3e30);
  color:white;border-radius:30px;padding:35px;
  display:flex;align-items:center;justify-content:space-between;gap:25px;
}
.delivery h2{margin:0 0 8px}01094943440
.delivery p{margin:0;line-height:1.7;color:#ffe9f1}
.phone{
  display:inline-flex;padding:14px 18px;border-radius:15px;
  background:var(--pink);font-weight:900;white-space:nowrap;
}
.note{
  margin-top:12px;font-size:13px;color:#ffe9f1;
}
footer{
  margin-top:50px;padding:28px 0;background:#351b16;color:#ffe9f1;text-align:center;
}
footer strong{color:#ff9fc1}

@media(max-width:820px){
  .hero-grid{grid-template-columns:1fr}
  .hero-card{transf
  (01094943440)
