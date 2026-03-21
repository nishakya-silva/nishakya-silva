# <span id="typing"></span>

<div style="font-family: monospace; white-space: pre; line-height: 1; font-size: 10px; display: inline-block;" id="wave">
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
function typeLetter() {
  if (i < text.length) {
    typingEl.innerHTML += text.charAt(i);
    i++;
    setTimeout(typeLetter, 150);
  } else {
    // after typing, show wave
    document.getElementById("wave").style.display = "inline-block";
  }
}
typeLetter();
</script>
