
# Ecossistema
<h3>Tecnologias e Bibliotecas</h3>

-[x] Python </br>

<h4>Bibliotecas</h4>



-[x] TKinter (interface gráfica). </br>
-[x] threading. </br>

<h3>Apresentação</h3>
Esse trabalho foi desenvolvido na disciplina de Programação Concorrente. </br>
O sistema simula um pequeno ecossistema, com tubarões, focas, peixes e algas, onde o usuário escolhe o numero de cada indivíduo assim como as calorias dos mesmos. </br>
Quando um predador que está acima na cadeia alimentar encontra um de menor posição, o mesmo o devora e consome suas calorais. </br>
A cada rodada os indivíduos perdem uma quantidade de calorias estabelecida. </br>

-[x] Tubarão devora focas e peixes. </br>
-[x] Foca devora peixes. </br>
-[x] Peixe come algas. </br>

Ao iniciar a simulação, também é iniciado um Timer e um contador de indivíduos no sistema.
Cada indivíduo é representado por uma thread, assim como o timer.
Foram utilizados semáforos para a sincronização das threads.
