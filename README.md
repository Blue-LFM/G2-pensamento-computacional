Trabalho Avaliativo – G2
Disciplina: Pensamento Computacional

|Integrante:                   |  Responsabilidade no trabalho:                                    |
|------------------------------|-------------------------------------------------------------------|
|Luis Eduardo do Moraes Ferrão |  Escrita, organização da ideia, testes, apresentação              |
|Letícia Fernanda Martinazzo   |  Criação da lógica, construção da simulação, testes, apresentação |

Primeira etapa: Criação da ideia
1 - Qual será a ideia principal do trabalho? 
Criar um console portátil do clássico jogo da cobrinha (Snake) utilizando Arduino e um display LCD Nokia 5110, reproduzindo a experiência dos antigos celulares e videogames portáteis, modificando-o para poder ser jogado em dupla.
 
2 - Como essa ideia surgiu?
Surgiu de um projeto feito no instructables que faz possível jogar o jogo da cobrinha em arduino, então tivemos a ideia de aprimorar e fazer possível jogar em dupla o mesmo jogo.

3 - Por que a dupla escolheu essa proposta?
Porque une programação, eletrônica, prática e criatividade em um projeto concreto e divertido, além de ser viável para o nosso nível.

4 - Qual situação, problema ou necessidade será trabalhada?
A necessidade de aplicar nossos aprendizados de lógica de programação e controle do arduino em um projeto real, tangível e funcional, saindo do ambiente puramente teórico da sala de aula.
 
5 - O que a dupla pretende criar ao final?
Um mini-console portátil físico, com Arduino Nano, display Nokia 5110 LCD, botões direcionais e alimentação por bateria, capaz de rodar o jogo da cobrinha de forma completa (movimentação, pontuação e detecção de colisão). 

Segunda etapa: Definição do problema ou necessidade
1 - O que precisa ser resolvido, melhorado ou representado?
A necessidade de transformar conceitos abstratos de programação(o jogo da cobrinha) em algo concreto e funcional. 

2 - Quem poderia utilizar ou se beneficiar desta solução?
Estudantes de cursos de tecnologia(como os da AMF), entusiastas do movimento maker e qualquer pessoa interessada em aprender criação de projetos em arduino.
 
3 - Por que essa solução faria sentido?
Porque a gente aprende muito mais ao construir algo que funciona de verdade. O jogo exige que nós dominemos a leitura de botões, controle de display, lógica de movimentação e todo o resto aprendido em aula. 

4 - O que aconteceria se essa solução fosse aplicada na prática?
Teríamos em mãos um projeto físico funcional que demonstra a programação em C++ para Arduino, manipulação de entradas e controle de display — um objeto que pode ser jogado, apresentado e evoluído com novas funcionalidades. 

Terceira etapa: Planejamento da solução
1 - O que a solução deverá fazer?
Executar o jogo da cobrinha com 2 cobras: mover as cobrinhas pela tela, detectar se elas comeram o alimento, crescer a cada item consumido, registrar a pontuação e encerrar o jogo ao colidir com a parede, com a outra ou com o próprio corpo. 

2 - Quais informações serão necessárias para ela funcionar?
Posição atual de cada segmento da cobra, direção de movimento vigente, posição do alimento na tela, pontuação acumulada e estado atual do jogo (em andamento ou encerrado). 

3 -Quais ações deverão acontecer?
Leitura contínua dos quatro botões direcionais, atualização da posição da cobra a cada ciclo, verificação de colisão com bordas e com o próprio corpo, verificação se a cabeça chegou à posição do alimento, geração de nova posição de alimento, atualização do display e exibição da pontuação em tempo real. 

4 - Quais decisões a solução precisará tomar?
Se a direção pressionada é válida (não é possível inverter o sentido diretamente), se houve colisão e o jogo deve encerrar, se o alimento foi consumido e a cobra deve crescer, e se a velocidade deve aumentar conforme a pontuação sobe. 

5 - Qual será o resultado esperado?
Um jogo completamente funcional no arduino físico, com resposta rápida aos botões, display atualizado em tempo real, pontuação visível durante a partida e exibição de tela de fim de jogo ao ocorrer uma colisão. 
