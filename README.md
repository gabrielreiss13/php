# php

  default;
  echo "insira uma operação válida";
}
  
?>  
</body>
</html>

Exercicio 2

<?php
$a = 26;
$b = -5;
$c = 2;

$delta = $b * $b - 4 * $a * $c;

if ($delta < 0) {
    echo "A equação não possui raízes reais.";
} else {
    $x1 = (-$b + sqrt($delta)) / (2 * $a);
    $x2 = (-$b - sqrt($delta)) / (2 * $a);
    
    echo "As raízes da equação são: x1 = $x1 e x2 = $x2";
}

?>

Exercicio 3
a)<?php
$matriz = array (
array      (1.5, 2.5, 3.5),
array      (4.5, 5.5, 6.5),
array      (7.5, 8.5, 9.5)
      );
     

       for($l=0; $l<3; $l++){
       for($c=0; $c<3; $c++){
                if(condição)
        echo $matriz[$l][$c];
   
                }
     echo"<br>";
            }

?>
