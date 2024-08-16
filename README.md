<svg width="600" height="100" viewBox="0 0 600 100" xmlns="http://www.w3.org/2000/svg">
  <style>
    .github-text {
      font-family: 'Courier New', Courier, monospace;
      font-size: 40px;
      fill: #333; /* Padrão de cor do GitHub */
      white-space: pre;
    }

    .cursor {
      font-family: 'Courier New', Courier, monospace;
      font-size: 40px;
      fill: #333;
      animation: blink 1s steps(2, start) infinite;
    }

    @keyframes type {
      0% { width: 0; }
      100% { width: 100%; }
    }

    @keyframes blink {
      50% { opacity: 0; }
    }

    .typing-animation {
      overflow: hidden;
      border-right: .15em solid #333; /* Cursor */
      white-space: nowrap;
      letter-spacing: .15em;
      animation: type 4s steps(30, end) 1s 1 normal both, blink 0.5s step-end infinite;
    }
  </style>
  
  <rect width="100%" height="100%" fill="#f5f5f5" />
  <text x="50%" y="50%" text-anchor="middle" dominant-baseline="middle" class="github-text typing-animation">
    Emilly Maczevski
  </text>
  <text x="50%" y="50%" text-anchor="middle" dominant-baseline="middle" class="cursor">|</text>
</svg>
