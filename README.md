<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="UTF-8" content="pt-br">
<title>Hor&aacute;rio de Bras&iacute;lia</title>
<table class="editorDemoTable" border="1" text-align: center>
<tbody>
<tr>
<td><strong>Hor&aacute;rio de Bras&iacute;lia</strong></td>
<td><strong>Local</strong></td>
<td><strong>Pa&iacute;s</strong></td>
<td><strong>GeoLocaliza&ccedil;&atilde;o</strong></td>
<td><strong>Copiar</strong></td>
</tr>
<tr>
<td>18:00h ~ 21:00h</td>
<td>London Island (Kiribati)</td>
<td><img src="https://www.countryflags.io/NZ/shiny/24.png" /></td>
<td><input type="text" value="1.987149,-157.47713" id="1"></button></td>
<td><button type="button" onclick="myFunction(1)">Copiar</button></td>
</tr>

<tr>
<td>23:00h ~ 02:00h</td>
<td>Wellington (Nova Zel&acirc;ndia)</td>
<td><img src="https://www.countryflags.io/NZ/shiny/24.png" /></td>
<td><input type="text" value="-41.281784,174.768193" id="2"></button></td>
<td><button type="button" onclick="myFunction(2)">Copiar</button></td>
</tr>

</tbody>
</table>
</head>
<body>
<script>
function myFunction(event) {  
  var copyText = document.getElementById(event);
  copyText.select();
  copyText.setSelectionRange(0, 99999);
  document.execCommand("copy");
  //alert("Copied the text: " + copyText.value);
} 
</script>
</body>
</html>
