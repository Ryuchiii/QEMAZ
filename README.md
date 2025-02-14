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
