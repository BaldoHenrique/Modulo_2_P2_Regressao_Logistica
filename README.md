# Projeto 2 - Classificação usando dados de Cancer de Mama 
  - Breast Cancer Coimbra Data Set - UCI
  
## Entrega
  - O projeto deve ser entregue até a segunda-feira da 4ª semana de aula, envie o link do GitHub ou HTML na atividade no Moodle.
  - O prazo máximo é terça-feira da 4ª semana de aula, valendo 20% a menos da nota.
  
## Dados do Certificado
  - Linguagem: Python
  - Tecnologias: Pandas, Numpy e Sklearn
  - Carga horária: 20 horas

## Introdução
  - O conjunto de dados de Cancer Mama esta localizado na plataforma UCI no seguinte link - https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra. O objetivo deste conjunto de dados é classificar se um individuo possui ou não cancer de mama a partir destas variaveis obtidas através do exame de sangue.
  - Segue a descrição das variaveis:
     - Age: idade em anos
     - BMI: indice de massa corporal (kg/m2)
     - Glucose: nivel de glicose no sangue (mg/dL)
     - Insulin: nivel de insulina no sangue (µU/mL)
     - HOMA: nivel de resistencia a insulina
     - Leptin: leptina (ng/mL)
     - Adiponectin: Adiponectina (µg/mL)
     - Resistin: Resistina (ng/mL)
     - MCP-1: nivel de proteina MCP-1 (pg/dL)
     - Classification: é classificado como 1 sem cancer (grupo controle) e 2 com cancer (grupo paciente)
     
  - Para mais informações, segue o link do artigo: https://bmccancer.biomedcentral.com/articles/10.1186/s12885-017-3877-1

  - referencia:
     - Patrício, M., Pereira, J., Crisóstomo, J., Matafome, P., Gomes, M., Seiça, R., & Caramelo, F. (2018). Using Resistin, glucose, age and BMI to predict the presence of breast cancer. BMC Cancer, 18(1).

## Sobre este projeto
  - Neste projeto treine os conhecimentos aprendidos até o momento e que entenda algumas das dificuldades que pode ter quando for aplicar os mesmos.
  - Os principais pontos que serão avaliados:
     - Levantamento de hipoteses
     - Manipulação de dados e criação de gráficos simples com o Pandas
     - Criar um modelo usando regressão logistica e justificar

## Preparação do ambiente
  - Acessem o link - https://archive.ics.uci.edu/ml/machine-learning-databases/00451/dataR2.csv e faça o download do conjunto de dados.

## Exercicio 1. (2.0 pontos)
  - Escreva em até quatro frases, uma breve apresentação sobre suas ideias do conjunto de dados e adicione qualquer contexto que possa ajudar os leitores a entendê-la.

## Exercicio 2. (3.0 pontos)
  -   Explore seu conjunto de dados e crie uma história em torno deles! Pense sobre o objetivo que deseja transmitir para seus leitores.

  - Você precisa criar uma visualização explicativa, ajudando o leitor a identificar uma ou mais ideias-chave no conjunto de dados. Assim, qual visualização você acha interessante destacar?
  - Obtenha o feedback de suas ideias e de sua(s) visualização(ões), se possivel apresente esse grafico com pelo menos uma outra pessoa e questione:
  1. O que você percebe na visualização?
  2. Quais perguntas você tem sobre o conjunto de dados?
  3. Há algo que você não entende nas visualizações?
  - Após o feedback, o que você mudaria?
  - Apresente suas nova(s) visualização(ões) a partir do feedback:
 
## Exercicio 3. (5.0 pontos)
  - Construa um modelo de regressão logistica para predizer a variável Classification com statsmodels.api.
  - Coloque abaixo a saida do seu modelo usando seu_modelo.summary().
  - Faça outro modelo usando a biblioteca sklearn e usem o parametro random_state com valor 10.
  - Coloque abaixo a matriz de confusão do modelo feito:
  - Prencha as métricas a partir da matriz de confusão obtida (lembrando que a classe negativa é 1 - sem cancer e a classe positiva é 2 - com cancer)
  - Observando a matriz de confusão, o seu modelo tende a obter mais erros do tipo I ou do tipo II?

