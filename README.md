@keyframes fanim {0% {background-position: 0% 0%;}25% {background-position: 100% 100%;} 50% {background-position: 0% 100%;} 75% {background-position: 50% 50%;} 100% {background-position: 0% 0%;}}
body{background-color:#101010;font-family:var(--gaya-font);padding: 25px;-webkit-user-select: none; -ms-user-select: none; user-select: none;} a{text-decoration:none;}
body::before{content:"\00A9  irvan setiawan";color:white;opacity:.3;font-size:12px;position:fixed;bottom:25px;left:25px;z-index:2}
#bodyblur{opacity:1;animation: jj 7s infinite;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);z-index:-1;transition:all 1s ease;} #wallpaper{transition:all 3s ease;}
#beneranblur{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);-webkit-backdrop-filter:blur(3px); backdrop-filter:blur(3px);transition:all 3s ease;}
@keyframes jj{0%  {transform: scale(1.1);} 50% {transform: scale(1.2);} 100% {transform: scale(1.1);}}

@keyframes kont{0%  {left:-1px; top:-3px;} 50% {left:1px; top:3px;} 100% {left:-1px; top:-3px;}}
blockquote{opacity:0;visibility:hidden;transition:all .3s ease;position:relative;margin-top:120px;margin-left:0;margin-right:0;}
blockquote{width:400px;background:var(--warna-bg);border-radius:var(--bingkai);border-left:2px solid var(--warna-bingkai);border-right:2px solid var(--warna-bingkai);color:var(--warna-teks);text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);text-align:center;line-height:1.3em;padding:20px;}
p{color:var(--warna-teks);font-size:18px;font-weight:400;line-height:1.4em;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);transition:all .5s ease;}
#kalimat{font-size:20px;font-weight:700;transform:scale(.1);}
#kalimatc{font-size:16px}
#kalimatd{font-family:var(--gaya-font2);font-size:22px;font-weight:700;}

#katajawab{font-weight:400;margin:0;display:none;}
@keyframes rts{from {transform:scale(.1);} to {transform:scale(1);}}
@keyframes rto{from {transform:scale(1);} to {transform:scale(1.1);}}
@keyframes aniopa{0% {transform: scale(1);} 50% {transform: scale(.75);} 100% {transform: scale(1);}}
#katabawah{transform:scale(.1);font-size:30px;font-weight:400}
#katatiga{font-size:18px;} #kataempat{font-size:13px;font-weight:400;text-align:right;}
@keyframes rtf{from {transform: rotate(0deg);} to {transform: rotate(360deg);}} @keyframes rt{from {transform: scale(.9);/* transform: rotate(-5deg); */} to {transform: scale(1);/* transform: rotate(5deg); */}}
#bq img{display:none;padding:10px;width:130px;height:130px;margin:20px 0 0 0;}
#akhiran{display:none;color:#FFC700;font-size:14px;text-align:center;background:rgba(0,0,0,.55);text-shadow: 0px;padding:10px;border-radius:var(--bingkai);line-height:10px;transition:all .2s ease;} #akhiran:hover{transform: scale(.9);opacity:.5;}

#Tombol{position:relative;opacity:0;margin:0;margin-top:-100px;display:flex;align-items:left;list-style:none;transform: scale(.1);transition:all 1s ease;}
#Tombol a{cursor:pointer;display:inline-flex;align-items:center; margin:0;margin:12px 0 12px 0;transition:all .2s ease;padding:10px;outline:0;border-left:2px solid var(--warna-bingkai);border-right:2px solid var(--warna-bingkai); border-radius:var(--bingkai);line-height:15px;background:var(--warna-bg);color:var(--warna-teks);font-size:14px;font-weight:700;white-space:nowrap;overflow:hidden;z-index:1} 
/* #Tombol a:hover{border-left:4px solid var(--warna-bingkai);border-right:4px solid var(--warna-bingkai);transform: scale(.90);opacity:.98;} */
#buttonv2{position:absolute;font-size:15px;color:white;background:var(--warna-bg);padding:10px;border-radius:8px;line-height:10px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);opacity:0}

.lovein{font-size:50px;display:flex;align-items:center;justify-content:center;transition:all .3s ease;}
.lovein svg{width:80px;height:80px;fill:#fefefe}

.content2{display:block;text-align:center;width:100%;height:180px;margin-top:50px;}
.content2 > *{display:flex;align-items:center;justify-content:center;margin-top:15px;font-size:17px;color:white}
.image img{border-radius:10%;transform:scale(.1);transition:all .8s ease;}
#k2 .image > *{margin-bottom:40px;} #k2{font-weight:700;font-size:17px;color:white;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);} #final1{transition:all 3s ease;}

#idkirim{font-size:13px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);color:white;transition:all .5s ease;}
#idkirim{opacity:0;visibility:hidden;margin-top:100px} #idkirim:hover{transform:scale(.8);}

.content2{display:none;}
#Content{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;position:relative;opacity:0;margin-top:50px;width:100%;height:180px;transition:all 1s ease;}
#Content > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:15px;}
#Content img{display:none;background:rgba(255,255,255,.5);border:2px double var(--warna-bingkai);border-radius:8%;padding:10px;width:110px;height:110px;margin:20px 0 0 0;}
#fotoakhir{opacity:.1;transition:all 1.2s ease;transform: scale(.1);}

#fotolove img{transition:all .5s ease;width:75px;height:75px;padding:0;background:none}
#suratin img{display:inline-flex;background:rgba(255,255,255, 1);border-radius:10%;padding:10px;width:140px;height:110px;transition:all .3s ease;}
#suratin img:hover{transform:scale(.9);}

.swal2-modal > *{font-size:17px;}
.swal2-title{line-height:1.3em;font-size:17px;text-align:center;padding:15px 30px 0 30px;}
.swal2-container.swal2-backdrop-show{background: rgba(0,0,0,.75);}
.swal2-timer-progress-bar-container > *{opacity:.5;background:#00B6FF;margin:0 5px}
.swal2-modal{max-width:250px;background:rgba(255,255,255,1);border: 1px solid #fff;border-radius:var(--bingkai);top:-70px;}

.fa-heart {opacity:.3;color:white;font-size: 27px;position: absolute;animation:  heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: translateY(-10vh) ;} 100%{transform: translateY(100vh) ;}}
#linkmp3, #fotoakhir2, #pesanditolak > *, #kalimat2, #kalimatb2, #kalimatc2{display:none}
