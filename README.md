<div align="center">

  <h1 class="glitch" data-glitch="ReNodeX">ReNode<span style="color:#ff0044">X</span></h1>
  
  <p class="glitch-small" data-glitch="r _ . v">r _ . v</p>

</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');
  
  .glitch {
    font-family: 'Share Tech Mono', monospace;
    font-size: 110px;
    font-weight: 700;
    color: white;
    position: relative;
    display: inline-block;
    letter-spacing: 8px;
  }

  .glitch::before,
  .glitch::after {
    content: attr(data-glitch);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }

  .glitch::before {
    animation: glitch1 0.4s infinite;
    color: #00ffea;
    z-index: -1;
    clip-path: polygon(0 0, 100% 0, 100% 35%, 0 35%);
  }

  .glitch::after {
    animation: glitch2 0.5s infinite;
    color: #ff0044;
    z-index: -2;
    clip-path: polygon(0 65%, 100% 65%, 100% 100%, 0 100%);
  }

  @keyframes glitch1 {
    0%   { transform: translate(0); }
    20%  { transform: translate(-3px, 3px); }
    40%  { transform: translate(-3px, -3px); }
    60%  { transform: translate(3px, 3px); }
    80%  { transform: translate(3px, -3px); }
    100% { transform: translate(0); }
  }

  @keyframes glitch2 {
    0%   { transform: translate(0); }
    20%  { transform: translate(3px, -3px); }
    40%  { transform: translate(3px, 3px); }
    60%  { transform: translate(-3px, -3px); }
    80%  { transform: translate(-3px, 3px); }
    100% { transform: translate(0); }
  }

  .glitch-small {
    font-family: 'Share Tech Mono', monospace;
    font-size: 30px;
    margin-top: -20px;
    opacity: 0.9;
  }
</style>
