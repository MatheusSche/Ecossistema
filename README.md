# Ecossistema

<h3>Tecnologias e Bibliotecas</h3>

-[x] Python

<h4>Bibliotecas</h4>

-[x] TKinter. 
-[x] threading. 

<h3>Apresentação</h3>
Esse trabalho foi desenvolvido na disciplina de Programação Concorrente.
O sistema simula um pequeno ecossistema, com tubarões, focas, peixes e algas, onde o usuário escolhe o numero de cada indivíduo assim como as calorias dos mesmos.
Quando um predador que está acima na cadeia alimentar encontra um de menor posição, o mesmo o devora e consome suas calorais.
A cada rodada os indivíduos perdem uma quantidade de calorias estabelecida.

-[x] Tubarão devora focas e peixes.
-[x] Foca devora peixes.
-[x] Peixe come algas.

Ao iniciar a simulação, também é iniciado um Timer e um contador de indivíduos no sistema.
Cada indivíduo é representado por uma thread, assim como o timer.
Foram utilizados semáforos para a sincronização das threads.
