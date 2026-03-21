# <span id="typing"></span>

<div id="wave" style="font-family: monospace; white-space: pre; line-height: 1; font-size: 10px; display: none;">
⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣤⣤⣤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⣰⠟⠉⠀⠀⠉⠙⠻⣶⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢏⠀⠈⠉⠲⣄⠀⠀⠈⢻⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠈⠂⠀⠀⠀⢹⡇⠀⠀⠀⠹⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣀⣠⣤⣀⣀⣀⣀⣀⣠⣿⠃⠀⠀⠀⠀⠈⠻⣦⣀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠈⠉⠛⠛⠛⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠒⠒⠀
</div>

<script>
const text = "Nishakya Silva : Always learning, always evolving";
let i = 0;
const typingEl = document.getElementById("typing");
const waveEl = document.getElementById("wave");

function typeLetter() {
  if (i < text.length) {
    typingEl.innerHTML += text.charAt(i);
    i++;
    setTimeout(typeLetter, 150);
  } else {
    waveEl.style.display = "inline-block";
  }
}

typeLetter();
</script>
