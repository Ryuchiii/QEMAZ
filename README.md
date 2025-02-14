<html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
<script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
<link href="" rel="stylesheet" type="text/css" />
<head>
<title>Script HTML Feeldream Repl Co</title>
</head>
<style>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Sriracha:wght@400;700&display=swap');
:root {
--warna-bg: rgba(0, 0, 0, .4); 
--warna-teks: white;
--warna-bingkai: rgba(255, 255, 255, .7);
--bingkai: 10px;
--gaya-font: 'Ubuntu', sans-serif;
--gaya-font-sec: 'Sriracha', sans-serif;
}
body{background-color:#101010;font-family:var(--gaya-font);padding: 25px;-webkit-user-select: none; -ms-user-select: none; user-select: none;} a{text-decoration:none;}
body::before{content:"\00A9  feelthisray (formerly Rayys)";padding:8px;border-radius:12px;background:black;color:white;opacity:.7;font-size:9px;position:fixed;bottom:20px;left:20px;z-index:999}
#bgbelakang{display:block;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.4);-webkit-backdrop-filter:blur(2px); backdrop-filter:blur(2px);transition:all 1s ease;}
#bgbelakang img{transition:all 1.7s ease;opacity:0;width:100%;height:100%}
#fotolove img{transition:all .5s ease;width:75px;height:75px;padding:0;background:none}
#loveIn img{display:inline-flex;background:none;width:130px;height:130px;transition:all .3s ease;} 
#ket, #kot, #ketgeser, .halo{text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);font-size:17px;font-weight:700;color:white}
#ket, #kot{transform: scale(1) !important;margin-top:20px !important;font-size:16px;font-weight:700;font-family:var(--gaya-font-sec);opacity:1}
#kot a{font-weight:700;color:yellow}
#ketgeser{position:absolute;margin-top:30px;font-size:10px;font-weight:400;transform:scale(0);opacity:0;transition:all .7s ease;}
@keyframes leaves {0% {transform: scale(1.0);} 100% {transform: scale(.85);}}
.lovein{margin-top:25vh;background:#fff;border-radius:50%;width:40px;height:40px;padding:10px;font-size:30px;display:flex;align-items:center;text-align:center;justify-content:center;transition:all .3s ease;}
.lovein:hover{cursor:pointer}
.lovein svg{stroke:#ff0000;stroke-width:1.3;fill:none;width:35px;height:35px}
@keyframes kont{0%  {left:-1px; top:-3px;} 50% {left:1px; top:3px;} 100% {left:-1px; top:-3px;}}
blockquote{opacity:0;visibility:hidden;transition:all 1s ease;position:relative;margin-left:0;margin-right:0;}
blockquote{width:400px;min-height:30px;background:none;color:var(--warna-teks);text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);text-align:center;line-height:1.3em;padding:25px;border: 0px solid var(--warna-bingkai);border-radius:var(--bingkai);}
.awalan{margin-top:20px;width:250px;min-height:25px;padding:12px;font-size:13px;color:white;background:rgba(0,0,0,.5);border:1px solid #fff;border-radius:20px;display:flex;align-items:center;text-align:left}
.awalan svg{margin-right:15px;width:25px;height:25px;stroke:white}
p{opacity:0;color:var(--warna-teks);font-size:15px;font-weight:700;line-height:1.4em;margin:0px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);transform: scale(.1);transition:all .3s ease;}
#text-container{opacity:1;transform: scale(1);}
.word {opacity: 0; transition: opacity 1s ease-in-out; display: inline-block;margin-right: 5px;}
#spasi::before{content:"\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0"}
#kalimat, #kalimatc{opacity:1;transform: scale(1);}
#kalimatc{font-size:18px;font-weight:700}
#katajawab{font-weight:400;margin:0;display:none;}
@keyframes rto{from {transform:scale(1);} to {transform:scale(1.1);}}
@keyframes aniopa{0% {transform: scale(1);} 50% {transform: scale(.75);} 100% {transform: scale(1);}}
#katabawah{transform:scale(.1);font-size:30px;font-weight:400}
#katatiga{font-size:18px;} #kataempat{font-size:13px;font-weight:400;text-align:right;}
@keyframes rtf{from {transform: rotate(0deg);} to {transform: rotate(360deg);}} @keyframes rt{from {transform: scale(.9);/* transform: rotate(-5deg); */} to {transform: scale(1);/* transform: rotate(5deg); */}}
#bq img{display:none;padding:10px;width:130px;height:130px;margin:20px 0 0 0;}
#bq img:first-child{display:inline-flex}
#akhiran{display:none;color:#FFC700;font-size:14px;text-align:center;background:rgba(0,0,0,.55);text-shadow: 0px;padding:10px;border-radius:var(--bingkai);line-height:10px;transition:all .2s ease;} #akhiran:hover{transform: scale(.9);opacity:.5;}
#pergeseran{opacity:0;visibility:hidden;transition:all 1s ease;display:flex;flex-wrap:nowrap;align-items:flex-start;justify-content:flex-start;position:relative;max-width:500px;padding:0 20px; overflow-y:hidden;overflow-x:scroll;scroll-behavior:smooth;scroll-snap-type:x mandatory; -ms-overflow-style:none;-webkit-overflow-scrolling:touch}
#pergeseran p{background:#003A76;color:white;border: 1px dashed #fff;border-radius:8px;padding:8px;display:flex;flex-wrap:nowrap;text-align:center;font-size:16px;font-weight:700;align-items:center;justify-content:center;flex-shrink:0; width:90%; min-height:130px;margin:0 15px 0 0; scroll-snap-align:center} #pergeseran > *:last-child{margin-right:0} #pergeseran:after{content:'';display:block;flex-shrink:0; align-self:stretch;padding-left:20px}
#pergeseran p b{display:block;} #pergeseran p b img{width:80px;height:80px;margin:20px 0;}
#tm{color:#FFB400;transition:all .5s ease;} #tm:hover{transform: scale(.7);}
#idgeser{position:relative;top:30vh;font-size:17px;color:white}
#contTom{opacity:0;margin:0;display:flex;align-items:left;list-style:none;transition:all 1s ease;}
.button{cursor:pointer;display:inline-flex;align-items:center; margin:0;margin:12px 0 12px 0;transition:all .3s ease;padding:10px;outline:0;border:1px solid var(--warna-bingkai); border-radius:var(--bingkai);line-height:15px;background:var(--warna-bg);color:var(--warna-teks);font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;z-index:1} 
.button:hover{transform: scale(.90);opacity:.98;}
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
#Content{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;position:relative;opacity:0;margin-top:50px;width:100%;height:180px}
#Content > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:15px;}
#Content img{display:none;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);width:90px;height:90px;background: rgba(255, 255, 255, 0.7);border: 1px solid rgba(255, 255, 255, 0.3);border-radius: 50%;padding:10px;margin:20px 0 0 0;}
.swal2-modal > *{font-size:16px}
.swal2-title{line-height:1.3em;margin-right:20px;margin-left:20px;font-size:18px;text-align:center;padding:15px 30px 0 30px;}
.swal2-timer-progress-bar-container > *{opacity:.3;background:#007AFF;margin:0 5px}
.swal2-modal{background:rgba(255,255,255,1);border: .7px solid #fff;border-radius:var(--bingkai);top:-60px;}
.fa-heart {opacity:.18;color:white;font-size: 20px;position: absolute;animation:  heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: translateY(-10vh) ;} 100%{transform: translateY(100vh) ;}}
.overlay {position: fixed;top: 0;left: 0;width: 100%;height: 100%;display: flex;justify-content: center;align-items: center;z-index:100;}
.loading-message {font-size: 14px;font-weight: bold;color:white;text-align: center;}
</style>
<body>

	<audio src="https://feeldreams.github.io/audio/sygbanget.mp3" id="linkmp3" class="sembunyi"></audio>

   <div id="bgbelakang">
     <!-- Wallpaper --><img src="" id="wallpaper"/>
   </div>

   <div class="overlay">
     <div class="loading-message">Harap tunggu...</div>
   </div>

   <div id='Content'>
   	
   <p id="ket">Klik di bawah ya <3</p>
   <div><div id="loveIn" class="awalan">
     <svg class='line' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><g transform='translate(2.000000, 2.000000)'><path d='M9.27542857,0.714285714 C14.0030476,0.714285714 17.836381,4.54666667 17.836381,9.2752381 C17.836381,14.0038095 14.0030476,17.8361905 9.27542857,17.8361905 C4.54685714,17.8361905 0.71447619,14.0038095 0.71447619,9.2752381 C0.71447619,4.54666667 4.54685714,0.714285714 9.27542857,0.714285714 Z'></path><path d='M17.8989524,16.487619 C18.678,16.487619 19.3094286,17.12 19.3094286,17.8980952 C19.3094286,18.6780952 18.678,19.3095238 17.8989524,19.3095238 C17.1199048,19.3095238 16.4875238,18.6780952 16.4875238,17.8980952 C16.4875238,17.12 17.1199048,16.487619 17.8989524,16.487619 Z'></path></g></svg>
     <label>S.id/sygbanget</label>
   </div></div>

   <!-- Foto Atas --><div><img id="fotosatu" src=""/><img id="fotodua" src=""/><img id="fototiga" src=""/><img id="fotoempat" src=""/><img id="fotolima" src=""/><img id="fotoenam" src=""/><img id="fototujuh" src=""/></div>

   <div><blockquote id='bq'>
   <p id="kalimat"></p>
   <p id="text-container"></p>
   <p id="kalimatc"></p>
   </blockquote></div>

   <!-- Tombol Kirim Pesan --><div id="contTom"><a id="By" class='button' onClick="sjawab()">Klik Ini</a></div>

   </div>

<!-- Jangan Edit Bagian Ini --><script>

  function showDiv() {pergantian();setTimeout(kpemb,100);document.getElementById('Content').style = "opacity:1;margin-top:10vh;animation:kont 5s infinite;";document.querySelector("body").style.animation = "none 8s ease infinite";} function kpemb() {bq.style = "opacity:1;visibility:visible;margin-top:5px";}

  function loadfoto(){
    wallpaper.src = "https://feeldreams.github.io/pics/citynight.jpg";
    
    gambar1 = "https://feeldreams.github.io/mikir.gif";
    gambar2 = "https://feeldreams.github.io/pusn.gif";
    gambar3 = "https://feeldreams.github.io/pusn2.gif";
    gambar4 = "https://feeldreams.github.io/pandapanah.gif";
    //gambar5 = "https://feeldreams.github.io/weee.gif";
    
    //gambar6 = "https://feeldreams.github.io/gigitin.gif";
    //gambar7 = "https://feeldreams.github.io/mmm.gif";

    fotosatu.src = gambar1;
    fotodua.src = gambar2;
    fototiga.src = gambar3;
    fotoempat.src = gambar4;
    //fotolima.src = gambar5;
    //fotoenam.src = gambar6;
    //fototujuh.src = gambar7;
  }

  function tombol(){contTom.style="opacity:1;transform: scale(1);";ftom=1;} ftom=0; function fakhiran(){document.getElementById("akhiran").style = "display:inline-flex";}
  const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040',}); const swalsy = Swal.mixin({confirmButtonText: 'Iya', allowOutsideClick: false,}); const swalst = Swal.mixin({allowOutsideClick: false, showConfirmButton: false, timer: 1200, timerProgressBar: true, didOpen: () => {Swal.showLoading();const b = Swal.getHtmlContainer().querySelector('b');timerInterval = setInterval(() => {Swal.getTimerLeft()}, 100)},willClose: () => {clearInterval(timerInterval)}}); const style = document.createElement('style'); var today = new Date();var dd = String(today.getDate()).padStart(2, '0');var mm = String(today.getMonth() + 1).padStart(2, '0');var yyyy = today.getFullYear();const monthNames = ["Januari", "Februari", "Maret", "April", "Mei", "Juni", "Juli", "Agustus", "September", "Oktober", "November", "Desember"];today = dd + ' ' + monthNames[today.getMonth()] + ' ' + yyyy;
  function otomatis() {befanimkata();setTimeout(animkata,200);} function befanimkata(){kalimat.style="transform:scale(.5);";} function animkata() {kalimat.style="transform:scale(1);";}

  function otomatis2() {befanimkataa();setTimeout(animkataa,200);} function befanimkataa(){kalimatc.style="transform:scale(.3);font-size:14px;margin-top:30px;";} function animkataa() {kalimatc.style="transform:scale(1);font-size:14px;margin-top:30px;";}

  function finalakhir(){ftom=2;otomatis2();By.innerHTML = "Kirim Pesan";kalimatc.innerHTML = "Jawabanmu: " + pesanwhatsapp;} function sjawab(){if(ftom==1){kalimatc.innerHTML = "";otomatis2();jawab();} if(ftom==2){menuju();}}

  var aa=0,katangetik;function ngetik() {if(aa<katangetik.length){kalimat.innerHTML += katangetik.charAt(aa);aa++;setTimeout(ngetik,50);}}
  function bawahlagi(){kalimatc.style="margin-top:10px;";kalimatc.innerHTML = emot;}
  function kemunculanber(){setInterval(berjatuhan,200);}
  const body = document.querySelector("body"); audio = new Audio('' + linkmp3.src); function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
  
  function tfkata(){fkata+=1;} function bersihkan(){kalimat.innerHTML = "";}
  
  const words = ["Sayang", "Banget", "Sama", "Kamu"];
  const textContainer = document.getElementById('text-container');
  let index = 0;
  function displayText() {
  	kalimat.style.display="none";
      if (index < words.length) {
        const word = document.createElement('span');
        word.className = 'word';
        word.textContent = words[index];
        textContainer.appendChild(word);
        index++;

        setTimeout(() => {
          word.style.opacity = 1;
        }, 70); // Waktu dalam milidetik (0.1 detik)

        setTimeout(() => {
          displayText();
        },280);
      } else {
        setInterval(berjatuhan,200);
        setTimeout(bawahlagi, 800);
      }
    }
    
  fkata=1;function gantikata(){
        if(fkata==1){otomatis();kalimat.innerHTML = kata1;}
        if(fkata==2){otomatis();kalimat.innerHTML = kata2;fotosatu.style="display:none";fotodua.style="display:inline-flex;"}
        if(fkata==3){otomatis();kalimat.innerHTML = kata3;fotodua.style="display:none";fototiga.style="display:inline-flex;"}
        if(fkata==4){kalimat.innerHTML="";displayText();fototiga.style="display:none";fotoempat.style="display:inline-flex";}
        setTimeout(tfkata, 200);
  }

</script> <!-- Sampai Sini -->

<script type="text/javascript">

       async function menuju(){await swals.fire('Kirim pesan ke WhatsApp aku, ya!');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;}

       async function jawab(){
           var { value: jawaban } = await swals.fire({
               title: 'Ketik Pesan Kamu &#128073;&#128072;', 
               input: 'text', allowOutsideClick: false, showCancelButton: false,
           });
           if(jawaban && jawaban.length < 21){
           	window.jawaban = jawaban;
               pesanwhatsapp = jawaban;
               finalakhir();
           } else {
               await swals.fire('Ups!', 'Jawaban tidak boleh kosong atau lebih dari 20 karakter, ya!');jawab();
           }
       }

  function pergantian(){
      setTimeout(gantikata,300); //1
      setTimeout(gantikata,1400); //2
      setTimeout(gantikata,3100); //3
      setTimeout(gantikata,4000); //4
  }
  
      async function pertama(){
         kata1 = "Eeee";
         kata2 = "Aku.. 🫠";
         kata3 = "Aku 👉👈";
         emot = "🥰🤭😍😆🫰";
         
         fotosatu.style="display:inline-flex";audio.play();showDiv()
       } 
  
Content.style="display:none";
window.addEventListener("load", (event) => {
  var overlay = document.querySelector(".overlay");
  overlay.style.display = "none";
  loadfoto();
  wallpaper.style="opacity:.3";
  Content.style = "opacity:1;margin-top:25vh";
});

    fungsiAwal=0;
    document.getElementById("loveIn").onclick = function() {
      if(fungsiAwal==0){
        loveIn.style="transition:all .7s ease;opacity:0";
        ket.style="transition:all .7s ease;opacity:0";
        fungsiAwal=1;setTimeout(initengahan,300);
      }
    }
    
  function initengahan(){
    loveIn.style="display:none";
    ket.style="display:none";
    Content.style = "opacity:1;margin-top:7vh";
    setTimeout(pertama,200);
  }
</script>
</body>
</html>
