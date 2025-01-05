**Experimento 2: Controle de Nível em um Tanque de Derivado de Petróleo**

Neste experimento, iremos projetar um circuito lógico com base em uma descrição de problema prático. O circuito a ser desenvolvido será utilizado hipoteticamente para controlar o nível de um tanque de derivado de petróleo [1].

Como mostrado na Figura 1, o tanque é equipado com um sensor A (nível alto) que emite o sinal "1" quando o tanque está cheio e um sensor B (nível baixo) que emite o sinal "1" quando o tanque está com o nível muito baixo. A válvula de saída do fluido do tanque, controlada por um operador, é operada pela válvula V. A válvula envia o sinal "1" para o circuito quando está aberta e "0" quando está fechada. No topo do tanque, há uma tubulação com um registro R que abastece o tanque com o derivado de petróleo. O circuito digital controla o registro: o registro é aberto quando a saída R é igual a "1" e é fechado quando a saída R é igual a "0".

**Figura 1:** Sistema de controle de nível de um tanque de derivado de petróleo. Fonte: [1].

Com base na descrição acima, o circuito digital a ser projetado deve ter três entradas, que receberão os sinais dos sensores A e B, bem como da válvula V. A saída do circuito controlará o registro R. O registro R deve ser aberto para encher o tanque sempre que a válvula V estiver aberta, a menos que o tanque esteja cheio, caso em que o registro deve permanecer fechado. Da mesma forma, quando a válvula estiver fechada e o tanque estiver com o nível muito baixo, o registro também deve ser aberto para encher o tanque, fechando-se assim que o nível atingir o mínimo aceitável.

**Observação:** Se houver combinações de entradas que sejam impossíveis de ocorrer na prática, considere que a saída R deve ser igual a zero (0) nesses casos.

Aqui estão as etapas do experimento:

1. Construa a tabela-verdade da saída do sistema.
2. Com base na tabela-verdade obtida no Item 1, encontre a expressão de R na forma Soma Padrão de Produtos (soma de mintermos). Com base nessa expressão, projete e simule um circuito lógico que implementa a lógica da saída R (utilize portas de duas entradas no diagrama lógico).
3. Simplifique a expressão usada no Item 2 para obter uma nova expressão na forma soma de produtos que seja mínima. Com base nessa nova expressão, projete e simule um circuito lógico que implementa a lógica da saída R (utilize portas de duas entradas no diagrama lógico).
4. Compare a complexidade dos circuitos obtidos nos Itens 2 e 3.
5. Monte em um protoboard o circuito lógico projetado no Item 3.
6. Quantos CIs foram necessários para implementar o circuito lógico projetado no Item 3? Seria possível implementar um circuito lógico equivalente utilizando apenas um CI de portas lógicas? Caso seja possível, projete esse circuito e implemente-o em um protoboard.

Para as entradas lógicas (variáveis A, B e V), utilize botões (botão apertado = variável 1, botão solto = variável 0) e um LED para indicar os níveis lógicos da saída (LED aceso = R = 1, LED apagado = R = 0).

**Observação Importante:** Este experimento requer a elaboração de um relatório detalhado, que deve ser entregue na aula de execução do experimento. O relatório deve conter seu nome e turma, além das respostas para os itens 1 a 6, incluindo a tabela-verdade, as expressões lógicas, simplificações realizadas e os diagramas lógicos dos circuitos implementados. 

**Critérios de Avaliação:**
- Inspeção da realização do experimento (funcionamento) e/ou arguições (6 pontos).
- Organização (1 ponto) - só será contabilizado se o circuito funcionar.
- Qualidade do relatório (3 pontos).

Lembre-se de que a ausência na aula de execução do experimento ou a não realização da atividade resultará em uma nota zero (0,0). Certifique-se de trazer o relatório pronto na aula de execução do experimento.
