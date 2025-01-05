**Experimento 8**

**Objetivos**
- Projetar circuitos sequenciais com Máquinas de Estados Finitos.

**Procedimento**

Considere o sistema de semáforos mostrado na Figura 1, em que o cruzamento é formado por duas ruas: uma rua principal, com os semáforos S1 e S2, e uma rua secundária com o semáforo S3. Cada faixa de trânsito tem um sensor capaz de identificar a existência de carros tentando passar pelo cruzamento, isto é:
- O sinal emitido pelo sensor P1 assume nível lógico 1 quando há carros na faixa norte-sul da rua principal;
- O sinal emitido pelo sensor P2 assume nível lógico 1 quando há carros na faixa sul-norte da rua principal;
- O sinal emitido pelo sensor P3 assume nível lógico 1 quando há carros na faixa única da rua secundária.

O semáforo Si, i = 1, 2, 3, abre (acende a luz verde) quando Si = 1 e fecha (acende a luz vermelha) quando Si = 0. Projete um circuito para controlar os semáforos em função dos sinais emitidos pelos sensores e, também, em função do tempo decorrido, satisfazendo as especificações a seguir:
1. Os semáforos da rua principal não poderão abrir enquanto o semáforo da rua secundária estiver aberto, e vice-versa.
2. Quando não houver carros em nenhuma das faixas ou houver carros apenas nas faixas da rua principal, os sinais da rua principal devem permanecer abertos por tempo indeterminado.
3. Quando houver carros apenas nas faixas da rua secundária, o sinal da rua secundária deve permanecer aberto por tempo indeterminado.
4. Se carros chegarem nas faixas da rua principal enquanto o sinal da rua secundária estiver aberto, então o sinal da rua secundária deverá fechar 10 segundos após a chegada do carro na rua principal ou quando não houver mais carros na rua secundária (o que ocorrer primeiro). Os sinais da rua principal devem abrir quando o da rua secundária fechar.
5. Se um carro chegar na rua secundária enquanto os sinais da rua principal estiverem abertos, então os sinais da rua principal deverão fechar 16 segundos após a chegada do carro na rua secundária ou quando não houver mais carros na rua principal (o que ocorrer primeiro). O sinal da rua secundária deve abrir quando os sinais da rua principal fecharem.
6. Se houver carros em uma das faixas da rua principal quando o sinal da rua secundária abrir, então esse sinal deve ficar aberto apenas enquanto houver carros na rua secundária, não excedendo o tempo de 10 segundos aberto.
7. Se houver carros na rua secundária quando o sinal da rua principal abrir, então esse sinal deve ficar aberto apenas enquanto houver carros na rua principal, não excedendo o tempo de 16 segundos aberto.

**Observação 1**: Use um sinal de clock com período de aproximadamente 1 segundo. Caso não se consiga um período de exatamente 1s, arredonde os tempos de 10 e 16 segundos das especificações para 10 e 16 ciclos de clock, respectivamente.

**Observação 2**: É permitido o uso de qualquer componente dentre aqueles incluídos na lista de componentes sugeridos da disciplina, divulgada no SIGAA.

**Relatório**

O relatório deve ser trazido pronto para a aula de execução do experimento. O relatório deve ser organizado e conter:
- Nome e turma;
- Explicações e justificativas de como foi implementado o circuito, descreva o funcionamento de cada parte do circuito;
- Diagrama de transição de estados;
- Tabela de transição de estado;
- Tabela de acionamento dos FFs;
- Simplificações realizadas e justificativas de como foi implementado o projeto;
- Diagrama do circuito lógico implementado.

**Critérios de avaliação**
- 5 pontos: inspeção da realização do experimento (funcionamento) e/ou arguições.
- 1 ponto: organização (só será computado se os circuitos funcionarem).
- 4 pontos: relatório.
- O aluno (ou a dupla) que faltar as aulas de execução do experimento ou não realizar a atividade receberá nota zero (0,0).
- O relatório deve ser entregue na aula de realização do experimento. O aluno (ou a dupla) que não entregar o relatório receberá nota zero (0,0) na atividade.

**Atenção**: Fica a critério do professor alterar a distribuição da pontuação e prazos apresentados no roteiro.
