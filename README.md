## Javascript
**File Hosting :**
Silahkan upload **timer.min.js**. Bila suah memakai jQuery terbaru tidak perlu menggunakan file tersebut

**Blogger :**
Upload ke hosting, atau saya sarankan di Google Drive. Kemudian masukkan kode pemanggilnya sebelum kode **</head>**.
Contoh :
> ```<script src="/timer.min.js" type="text/javascript"/>
> </head>```
Bila suah memakai jQuery terbaru tidak perlu menggunakan file tersebut

## CSS
**File Hosting :**
Jangan lupa upload file CSSnya.

**Blogger :**
Taruh kode CSS nya di Template, Edit HTML

## Cara Menggunakan
Taruh kode ini di halaman yang ingin dipasang CountDown nya :

<script type='text/javascript'>
//
var seconds = **10**;
function generate() {
var id;
id = setInterval(function () {
if (seconds
window.location = '**LINK TUJUAN**';
}else {
btn.style.display = "none";
menunggu.style.display = "inline";
document.getElementById('tunggu').innerHTML = --seconds;
}
}, 1000);}
//]]>
</script>
<button onclick="generate()" id="btn">Download</button>
<div id="menunggu">File otomatis terunduh dalam <span id="tunggu"/> detik