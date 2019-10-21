# medindenvers
<html>
  <body>
Medin Denvers 
<div class="wrapper"> 
    
  <div class="button animation">
    <p>BUTTON</p>
  </div> 
</div>
p {
  animation-duration: 3s;
  animation-name: slidein;
}

@keyframes slidein {
  from {
    margin-left: 100%;
    width: 300%
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}
var e = document.getElementById("watchme");
e.addEventListener("animationstart", listener, false);
e.addEventListener("animationend", listener, false);
e.addEventListener("animationiteration", listener, false);

e.className = "slidein";
</body>
