# Cognitivo
CASE 



Como foi a definição da sua estratégia de modelagem?
R) o database não possui legendas, logo, ficou dificil em criar uma intuição sobre qual feature/atributo teria correlação com a saida do pricing.
Deste modo, escolhi algumas colunas que apresentavam valores numericos que provavelmente eram de avaliações dos clientes e uma tabela de dado tipo string representando os bairros das residencias. Foi escolhido a ML de REDE NEURAIS ARTIFICIAIS do tipo perceptron multipla camada e testada 3 topologias.


 Como foi definida a função de custo utilizada?
 R) A função de custo foi pela utilização do backpropagation, onde há o ajuste do erro depois de uma época (apresentação de todos os dados) do database de treino
 
 
 
Qual foi o critério utilizado na seleção do modelo final?
R) o menor erro médio quadratico (MSE) e teste por tréplica, ou seja, foi escolhido o modelo que apresentava melhor média de desempenho em 3 testes. 
Os teste por tréplica foi necessário, pois as RNA iniciam com pesos sinápticos aleatórios.


 Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este
método?
R) O databse foi separado em 90% para treinamento dos algoritmos e 10% para teste, visando validar o modelo. O método é comumente utilizado na aplicação e validação de algoritmos de ML. 

Quais evidências você possui de que seu modelo é suficientemente bom?
R) pergunta capciosa... Podemos utilizar o R2 que quantifica o quão bom é o seu modelo. Outra abordagem envolvendo o problema de pricing seria comparar o valor predicto e o valor real + um desvio padrão, para verificar se o modelo é aceitável. Entretanto quero deixar claro que fiz o case em apenas uma tarde. quero apenas mostrar a metodologia e dissertar sobre o que foi feito. Em momento nenhum me preocupei em gerar O MELHOR modelo e em resolver todos os problemas de uma só vez. A aplicação de ML envolve outras técnicas como DATA AUGMENTATION, FEATURE ENGINEERING, FEATURE EXTRACTION, FEATURE SELECTION que não foram abordadas nesse case. 

obrigado!!!!!!!!!!!!!!!!!!!!!
