**Experimento 5: Circuito Somador e Subtrator**

**Objetivos**
- Projetar e construir circuitos aritméticos básicos (somador/subtrator).

**Procedimento**
Projete e construa um circuito digital que realize as operações de soma e de subtração para números inteiros com sinal e com 3 bits. As entradas são os números A e B, números de 3 bits e com sinal, designados por **A2 A1 A0** e **B2 B1 B0**, respectivamente. O resultado é o número S, de três bits, formado por **S2 S1 S0**.

Há também uma entrada de controle op para indicar a operação, tal que:
- op = 0 → operação de soma
- op = 1 → operação de subtração

O overflow (por exemplo, 2+2 ou -2-3) deverá ser indicado por um LED vermelho $L_{OVR}$, tal que:
- aceso → overflow
- apagado → sem overflow (resultado correto)

O projeto do circuito lógico que indica o overflow deverá estar claro e justificado. Utilize botões como entradas lógicas: botão pressionado equivale a variável igual a 1 e botão solto equivale a variável igual a 0. Para a variável op use um botão do tipo retentivo, se disponível.

ATENÇÃO: circuitos integrados de portas lógicas e MUX podem ser usados a vontade. Por sua vez, é permitido o uso de apenas um CI somador (CD4008).

**Relatório**
O relatório deve ser trazido pronto para a aula de execução do experimento. O relatório deve ser organizado e conter:
- Nome e turma;
- Passo a passo do projeto, expressões lógicas das saídas do circuito;
- Diagrama lógico do circuito implementado;
- Uma tabela com o número de portas e CIs utilizados (por tipo de porta e CI).

**Critérios de avaliação**
- 5 pontos: inspeção da realização do experimento (funcionamento) e/ou arguições.
- 1 ponto: organização (só será computado se o circuito funcionar).
- 4 pontos: relatório.
- O aluno (ou a dupla) que faltar a aula de execução do experimento ou não realizar a atividade receberá nota zero (0,0).
- O relatório deve ser entregue na aula de realização do experimento. O aluno (ou a dupla) que não entregar o relatório receberá nota zero (0,0) na atividade.

**Atenção**: Fica a critério do professor alterar a distribuição da pontuação e prazos
apresentados no roteiro.
