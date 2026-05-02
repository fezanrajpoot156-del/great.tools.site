Color Picker Tool
<h3>Color Picker</h3>
<input type="color" onchange="show(this.value)">
<p id="color"></p>

<script>
function show(c){
document.getElementById("color").innerText = "Selected: " + c;
document.body.style.background = c;
}
</script>
