# HamayeshZendegiBehtar.php
https://quera.org/problemset/10325
<?php
list($r, $c) 
		= explode(' ', readline("Enter 2 number: "));


$r = (int)$r;
$c = (int)$c;
function hamayesh($r, $c){
	$ra = 11 - $r;
	$ca = 21 - $c;
	if($c < 11){
		echo "Right $ra $c";
	}else{
		echo "Left $ra $ca";
	}
}
echo hamayesh($r, $c);
