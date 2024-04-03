1)

    <?php
    function func($p){
        if ($p < 0){
            echo "$p é negativo";
        }elseif ($p > 0){
            echo "{$p} é positivo"; 
        }else{
            echo "Seu número é zero";
        }
    }
    func(0);
    ?>

2)

    <?php
    function func($p){
        for($i=1;$i<11;$i++){
            echo "Número {$i}\n";
        }
    }
    func(0);
    ?>

3)

    <?php
    $frutas = [0, "Maçã", "Banana", "Melão", "Limão", "Figo"];
    for($i=1; $i<6; $i++){
        echo "$i. {$frutas[$i]}\n";
    }
    ?>

4)

    <?php
    $dados = [
        0 => "Nome: Fábio Henrique Tavares ",
        1 => "Idade: 30",
        2 => "Cidade: Campinas",
        3 => "Profissão: Futebolista"
        ];
    for($i=0;$i<4;$i++){
        echo "{$dados[$i]}\n";
    }
    ?>

5)

    <?php
    $dados = [
        0 => "Fábio",
        1 => "Campinas",
        2 => 30
        ];
    if($dados[2]<18){
        echo "{$dados[0]} é de {$dados[1]} e tem {$dados[2]} anos, logo, não pode dirigir";
    }else{
         echo "{$dados[0]} é de {$dados[1]} e tem {$dados[2]} anos, logo, pode dirigir";
    }
    ?>
