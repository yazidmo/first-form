<!doctype html>
<html>
<head> 
<title> css trials</title>
<meta charset="utf-8">
<style>
body {
padding: 0;
margin: 0;
background: #5fbfff;
}
.name {
padding: 5px;
margin: 5px;
background: azure;
}
.mail {
margin: 5px;
background: azure;
padding: 4px;
}
legend {
font-family: cursive;
font-size: 200%;
color: azure;
background: rose;
}
#date { 
background: azure;
padding: 2px;
border: 5px double blue;
margin: 6px 2px 4px;
}
#but {
background: #d99ac5;
}
#dl {
background: azure;
height: 24px;
width: 215px;
}
</style>
</head>
<body>
<form>
<fieldset>
<legend>fomulaire</legend>
<label> First name</label>
<input type="text" class="name" required placeholder="first-name" >
<div>
<label> Last name</label>
<input type="text" class="name" required placeholder="last-name"> </div>
<div><label> Email account</label></div>
<input type="email" class="mail" required> </div>
<div>
<label> Password</label></div>
<input 
type="password" 
class="mail" 
required minlength="7" 
maxlength="16"> 
<input id="but" type="submit" target="_blank">
<input id="but" type="reset">
<div >
<input id="eu" type="radio" name="residency" value="europe">
<label for="eu"> Europe</label></div><div>
<input id="af" type="radio" name="residency" value="africa">
<label for="af"> Africa</label></div><div>
<input id="nam" type="radio" name="residency" value="north america">
<label for="nam"> North America</label></div><div>
<input id="sam" type="radio" name="residency" value="south america">
<label for="sam"> South America</label></div><div>
<input id="as" type="radio" name="residency" value="asia">
<label for="as"> Asia</label></div><div>
<input id="oc" type="radio" name="residency" value="oceania">
<label for="oc"> Oceania</label></div>
<input id="but" type="file">
<input type="date" id="date">

</form>
<div id="dl">
<input list="lang" name="prog">
<datalist id="lang">
<option value="php" select>
<option value="python">
<option value="c">
<option value="c++">
<option value="html">
<option value="css">
</datalist>
</fieldset>
</body>
</html>
