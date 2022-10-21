# Prova-AC2-Algoritmos
QUESTÃO ÚNICA

Naruto é um jovem ninja que sonha em se tornar Hokage, o ninja líder de sua vila. Todos sabemos que o Naruto tem o poder de criar vários clones.

Faça um programa que otimize a criação dos clones do Naruto sabendo-se que cada clone criado consome 20 pontos da “energia” do Naruto.

a) Receba a quantidade de pontos de “energia” que o Naruto tem;

b) Receba a quantidade de clones desejada;

c) Receba a quantidade de clones por linha;

d) Quando o botão “criar clones” for clicado:

    d.1) (1 pt) Validar os campos de entrada da seguinte forma:

        i. A energia do item a) tem que estar entre 20 e 5.000;

        ii. A quantidade de clones do item b) tem que estar entre 0 e 250;

        iii. A quantidade de clones por linha do item c) tem que ser maior que 0;

        iv. Em caso de qualquer erro testado acima, emita um alert com a mensagem abaixo e não faça mais nada: 

            “ERRO NA ENTRADA DE DADOS – Energia tem que ser entre 20 e 5.000. Quantidade de Clones tem que ser entre 0 e 250. Quantidade de Clones por linha tem que ser maior que 0”.

    d.2) (1 pt) Caso tenha passado em todas as validações anteriores, valide se a “energia” do item a) é suficiente para criar a quantidade a quantidade de clones do item b) desejada, ou seja, o item a) tem que ser maior ou igual ao item b) multiplicado por 20. Caso contrário, emita um alerta com uma mensagem explicativa e não faça mais nada.

    d.3) (3 pts) Abaixo do botão, emitir todos os clones do Naruto, sendo que em cada linha terá somente a quantidade de clones informada no item c). Ajuste a altura da imagem para que não sejam exibidas imagens muito grandes na tela, o que dificultaria sua contagem.

    OBS: Use esse endereço de imagem abaixo para criar os clones do Naruto

    https://preview.redd.it/tudjq02jost71.jpg?auto=webp&s=ed558eeba8ee7c136febe2cd0084d2ab3661b9eb



e) (0.5 pt) Abaixo das imagens exibidas (sem apagá-las), emita o seguinte:

    ANÁLISE DA GERAÇÃO DE CLONES

    Energia Inicial: 99999  

    Qtde de Clones: 999

    Sobra de Energia: 99999

    OBS: 

        i. "Energia Inicial" é o valor recebido no item a);

        ii. "Qtde de Clones" é o valor recebido no item b);

        iii. "Sobra de Energia" é a Energia Inicial menos a Qtde de Clones vezes 20:   item a)  –  item b)  *  20.



f) (1.5 pts) Abaixo do item anterior, exibir uma das mensagens abaixo:

    i. “PROVAVELMENTE VOCE VAI GANHAR”, caso a Sobra de Energia seja maior que 1000 ou então a Qtde de Clones for maior que 50 e o percentual de sobra for maior ou igual  a 20%.

    ii. “A LUTA VAI SER MUITO BOA”, caso a Sobra de Energia seja maior que 500 ou então a Qtde de Clones entre 20 e 50 e o percentual de sobra for maior ou igual  a 10%.

    iii. Caso contrário, se nenhuma das mensagens anteriores forem exibidas, exiba: “TORÇA PARA O ADVERSÁRIO SER FRAQUINHO".

    OBS: Para obter o "percentual de sobra", basta dividir a "Sobra de Energia" pela "Energia Inicial" e multiplicar por 100.


g) (2.0 pts) Crie o diagrama de atividades do programa proposto


h) (1.0 pt) Use boas práticas de programação, tais como: Código organizado; bons nomes de variáveis; bons nomes de funções; bons nomes de ids; sem gambiarras; código sem "while" ou "if" desnecessários etc
