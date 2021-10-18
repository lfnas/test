# Análise Preditiva SINASC 2019 - Modelo para previsão do peso de recém-nascidos

#### Aluno: [Luiz Felipe Nascimento da Silva](https://github.com/lfnas).
#### Orientador: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para a monografia](---). 

---

### Resumo

Em decorrência das diversas pesquisas no âmbito da saúde pública, observa-se que a prematuridade associada ao baixo peso de recém-nascidos são possíveis causas da mortalidade perinatal, neonatal e infantil. Em mesmo passo, o acompanhamento pré-natal qualificado, pode auxiliar na identificação precoce desses incidentes e outros como: má formação, problemas genéticos etc. em razão disso, esses fatores devem ser melhor avaliados e explorados, viabilizando uma melhor resolução e tratamento a gestantes. Nesse sentido, e mediante a implementação de novas tecnologias, volta-se a atenção a promoção e formulação de modelos preditivo que possam associar e mensurar o desempenho futuro e/ou evolução de elementos biológicos e sociais das gestantes, isto é, modelos de predição que demonstrem ou sinalizem indícios (correlação) para grupos de riscos antes do nascimento. No presente trabalho, buscou-se a previsão do peso dos recém-nascidos,  tendo em vista, a relevância do peso na sobrevida da criança, possibilitando um estudo mais amplo, considerando as classificações oficiais de pesos de nascidos vivos. Em tempo, a previsão realizada é associada às diversas variáveis, reunidas em uma base de dados unificada, podendo citar: herança genética, condições de cuidado, histórico materno, fatores sociais, idade da mãe e tipo de parto, consequentemente, o modelo possibilita a identificação das gestantes que necessitem de maior atenção nas unidades de atenção básica, seja por uma condição biológica ou social, voltadas, também ao risco da gestação. A base utilizada para este trabalho é proveniente do Sistema de Informação sobre Nascidos Vivos (SINASC), que é um Sistema que facilita a visualização das evoluções de séries históricas, para o presente estudo será utilizado, somente um dataset, referente ao ano de 2019 dos nascimentos ocorridos no Estado do Rio de Janeiro.

### Abstract

As a result of several researches in the scope of public health, it is observed that prematurity associated with low birth weight of newborns are possible causes of perinatal, neonatal and infant mortality. At the same time, qualified prenatal care can help in the early identification of these incidents and others such as: malformation, genetic problems, etc. for this reason, these factors should be better evaluated and explored, enabling a better resolution and treatment for pregnant women. In this sense, and through the implementation of new technologies, attention is focused on the promotion and formulation of predictive models that can associate and measure the future performance and/or evolution of biological and social elements of pregnant women, that is, prediction models that demonstrate or signal evidence (correlation) for risk groups before birth. In the present work, we sought to predict the weight of newborns, considering the relevance of weight in child survival, enabling a broader study, considering the official classifications of weights of live births. In time, the forecast made is associated with several variables, gathered in a unified database, including: genetic inheritance, care conditions, maternal history, social factors, mother's age and type of delivery, consequently, the model allows for identification of pregnant women who need more attention in primary care units, whether for a biological or social condition, also focused on the risk of pregnancy.

### 1. Introdução

No Brasil, o Ministério da Saúde dispõe de uma base de dados que reúne informações sobre diferentes variáveis que podem ter influência sobre os partos prematuros e o baixo peso de recém-nascidos, a referida base é proveniente do Sistema de Informação sobre Nascidos Vivos (SINASC), que é um Sistema que facilita a visualização das evoluções de séries históricas. Os dados, por sua vez, são coletadas pelos entes da federação (Estados e Municípios), e consolidados neste sistema nacional que compreende uma das maiores referências sobre os nascimentos do país.

O presente estudo utilizará, somente um fragmento da base integral, isto é, referente ao ano de 2019 dos nascimentos ocorridos no Estado do Rio de Janeiro. Em detalhes, o dataset possui dados anonimizados, disponível no site (https://datasus.saude.gov.br/transferencia-de-arquivos/), com 48 features e mais de 200 mil registros, demonstrando-se uma base significativa para diversos testes e aplicações, não somente para previsão de pesos.

Ressalta-se a aplicabilidade da base para o reconhecimento social, epidemiológico, geográfico etc. ou seja, elevando a disponibilidade no desenvolvimento de modelos analíticos e preditivos, possibilitando as autoridades nacionais e regionais de saúde pública na promoções de polítcias públicas.

### 2. Modelagem

Inicialmente, destaca-se o grande volume de dados estruturados trabalhados com o dataset, bem como as diversas relações entre variáveis presente, conforme informado na introdução a base é bem ampla e dispõe de dados quantitativos e qualitativos de diversas naturezas.

A abordagem é voltada ao foco do problema, isto é, a previsão de pesos de récem-nascidos, considerando a correlação, através das funções e visualizações foi realizados os procedimentos de tratamento dos dados. Em especial, divide-se em algumas fases que podem ser melhor observadas:

  * Análise Exploratória
  
  * Vizualização dos Dados
  
  * Avaliação da Variável “Peso”
  
  * Tratamento de Missing Valeus
  
  * Feature Selection
  
  * Modelos Utilizados

### 3. Resultados

O modelo baseado em Random Forest foi aquele que obteve maior acurácia dentre os testado, chegando a 81.19% com 6 árvores e 28 features e um job, sendo uma modelo enxuto, pois em nenhuma outra configuração com mais árvores ele conseguiu ser finalizado, retornando várias vezes ao início com reinicialização do Kernel.

Outros modelos também não atingiram o esperado retornando pouco ou quase nada em aspectos de acurácia na predição, sendo incluídos para fins comparativos, conforme a tabela do último código.


### 4. Conclusões


---

Matrícula: 192.671.165

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação em *Business Intelligence Master*

---
