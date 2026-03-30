<?php

// Cálculo de Índice de Massa Corporal

echo "IMC \n";
echo "\n";

$peso = 75;
$altura = 1.71;
$imc = $peso / $altura **2;


echo "peso: $peso \n";

echo "altura: $altura \n";

echo "imc: $imc \n";

if ($imc < 16) { // verifica se o imc é menor que 16
echo "Magreza grau 3 \n";
} elseif ($imc >= 16 && $imc <= 16.9) { // verifica se o imc está entre 16 e 16,9
echo "Magreza grau 2 \n";
} elseif ($imc >= 17 && $imc <= 18.4) {// verifica se o imc está entre 17 e 18,4
echo "Magreza grau 1 \n";
} elseif ($imc >= 18.5 && $imc <= 24.9) { // verifica se o imc está entre 18,5 e 24,9 
echo "Eutrofia \n";
} elseif ($imc >= 25 && $imc <= 29.9) { // verifica se o imc está entre 25 e 29,9 
echo "Pré-obesidade \n";
} elseif ($imc >= 30 && $imc <= 34.9) { // verifica se o imc está entre 30 e 34,9
echo "Obesidade moderada - grau 1 \n";
} elseif ($imc >= 35 && $imc <= 39.9) { // verifica se o imc está entre 35 e 39,9
echo "Obesidade severa - grau 2 \n";
} elseif ($imc = 40) { // verifica se o imc é igual a 40
echo "Obesidade muito severa - grau 3 \n";
}
