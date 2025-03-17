- 👋 Hi, I’m @JeanPear-Rodriguez

en clase de introduccion a la programacion aperndi a realizar un arreglo.

<?php
	//echo "china";
	
 $vegetales = array("cebolla", "tomate", "pepino,", "yuca", "ajo" ,"apio");
 $vegetales[] ="calabaza";
 print_r($vegetales);
	
	//$nombres= ["Yubirizaida", "Makgiber", "Usnavy", "Melquiside", "Air Jordan"];
	
	//unset($nombres[3]);
	
	//print_r($nombres);
	
	$vegetalesEliminar = "cebolla";
	$llave = array_search($vegetalesEliminar, $vegetales);
	if($llave!==false){
	  unset($vegetales[$llave]);
	}
	print_r($vegetales)
?>;
