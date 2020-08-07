<?php

echo "Validação de numero PAR/IMPAR";

$num = readline ("Informe o numero que deseja validar: ");

if (($num % 2) == 0){
echo "O" . $num . "é par";
return false;
}
else{
  echo "O" . $num . "é impar";
}