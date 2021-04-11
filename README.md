# Abrir-Pop-Up-no-Centro-da-P-gina
Abrir Pop-Up no Centro da Página

<script>
	var win = null;
	function NovaJanela(pagina,nome,w,h,scroll){
	LeftPosition = (screen.width) ? (screen.width-w)/2 : 0;
	TopPosition = (screen.height) ? (screen.height-h)/2 : 0;
	settings = 'location=no,toolbar=no,directories=no,status=no,height='+h+',width='+w+',top='+TopPosition+',left='+LeftPosition+',scrollbars='+scroll+',resizable';
	win = window.open(pagina,nome,settings);
	}
</script>


<a href="http://www.terminalroot.com.br/" onclick="NovaJanela(this.href,'nomeJanela','820','560','yes');return false">Abrir Pop-Up</a>
