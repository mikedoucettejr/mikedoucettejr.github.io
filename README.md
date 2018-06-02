JAVA SCRIPT is located on the classes page (classes.html) following the p tag with the main text.

HTML:

<p id="demo">Click on the button below</p>
<input type="button" onclick="Msg1()" value="Button">
<script src="main.js"></script>

Links to main.js which has:

function Msg1(){
  document.getElementById('demo').innerHTML = 'Hey <strong>Thanks!</strong>';
}
