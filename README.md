![campus_marica](https://github.com/user-attachments/assets/0628a280-9887-4c1b-bbed-848426498ad1)
## TRABALHO P1 - PROBABILIDADE E ESTATÍSTICA
Curso: Engenharia de Software
Professor: Rafael Mynssem<br>
Período: 6<br>
Grupo: <br>
   - Angélica Gomes Da Silva<br>
   - João Pedro Portela da Trindade<br>
   - Priscila Paula Lima Tristão<br>
   - Quézia Trindade Moura<br>
   - Robson Ceia De Oliveira<br>
<hr>

## Introdução

Este projeto realiza uma análise estatística detalhada dos dados dos atletas que participaram das Olimpíadas ao longo de mais de 120 anos, utilizando o dataset "120 years of Olympic history: athletes and results" disponível no Kaggle. A análise foca em entender o perfil demográfico dos atletas, a evolução da participação olímpica e as correlações entre características físicas e o desempenho dos atletas.

## Analise Descritiva
### Tratamento de Valores Ausentes

Para melhorar a qualidade dos dados e evitar vieses nos resultados, vamos preencher os valores ausentes.
Usamos a mediana para 'Age' (menos sensível a outliers) e a média para 'Height' e 'Weight', por grupo de 'Sport' e 'Sex.

### Análise de Outliers

Utilizamos um boxplot para visualizar os outliers, especialmente para a idade dos atletas.
Idades acima de 65 anos são consideradas atípicas, pois a maioria dos atletas olímpicos é jovem.
Removemos os registros com idade acima de 65 anos para evitar distorções.

### Análise Demográfica e Estatísticas Básicas

Após tratar os valores ausentes e outliers, exploramos as distribuições de idade, altura e peso para verificar a conformidade dos dados e entender a demografia dos atletas.

## Análise de Participação Olímpica ao Longo dos Anos

Neste gráfico de linha, visualizamos o número de atletas que participaram das Olimpíadas ao longo dos anos.
A análise é segmentada por temporada (verão e inverno) para verificar tendências de participação.

### Análise de Atletas por País (Top 10)

Aqui, analisamos os países com o maior número de atletas olímpicos.
Esse gráfico nos ajuda a identificar quais países historicamente tiveram mais representação nos jogos.

## Analise de Peso e Altura por Esporte

Nesta análise, examinamos a variável height (altura) dos atletas, agrupando-os por esporte para observar quais apresentam as maiores e menores alturas médias. O objetivo é identificar os cinco esportes com as maiores médias de altura e os cinco com as menores, e visualizar isso por meio de um boxplot.

## Análise de Correlações

Analisamos a relação entre idade, altura, peso e a conquista de medalhas.
Usamos pairplots e boxplots para verificar como essas variáveis podem afetar as conquistas.
<hr>

## Considerações Finais e Análise dos Resultados

Esta análise dos dados olímpicos revela padrões e insights profundos sobre a demografia dos atletas, suas performances e a evolução das competições ao longo do tempo. Com a realização de diversas etapas, incluindo o tratamento de dados, detecção de outliers e uma investigação minuciosa dos atributos físicos dos atletas, identificamos várias tendências relevantes.

#### Perfil Demográfico dos Atletas Olímpicos:

O perfil demográfico mostrou-se central para entender as diferenças entre modalidades e o impacto da idade na performance. A faixa etária predominante dos atletas está entre 20 e 30 anos, uma faixa considerada ótima para competições de alto rendimento. A análise revelou também que atletas com idade superior a 65 anos são casos isolados e, portanto, removê-los como outliers trouxe mais precisão na análise das características da idade, altura e peso. Em termos de altura e peso, observou-se que esses valores variam amplamente conforme o esporte, com modalidades como basquete e natação exigindo físicos mais específicos em comparação a outras, como a ginástica.

#### Influência da Altura e Peso nas Características Físicas de Atletas por Esporte

A análise dos dados de altura mostrou que esportes como basquete e voleibol têm as maiores médias, onde a altura é uma vantagem competitiva clara. Já esportes como ginástica e levantamento de peso apresentaram as menores médias, refletindo a demanda por maior controle corporal e força relativa. O boxplot destacou tanto as diferenças entre as médias quanto a variabilidade dentro de cada esporte, indicando que, embora a altura seja importante em alguns esportes, há diversidade de perfis físicos entre os atletas.

A análise dos dados de peso revelou que esportes como Cabo de guerra e Bobsled apresentam as maiores médias, onde o peso elevado é uma vantagem para força e impacto. Por outro lado, esportes como ginástica e patinação artística têm as menores médias de peso, devido à necessidade de agilidade e leveza. O boxplot destacou as diferenças nas médias e a variação dentro de cada esporte, mostrando que, embora o peso seja crucial em algumas modalidades, há diversidade nas características físicas dos atletas dentro de cada esporte.

### Crescimento da Participação Olímpica

Observou-se um crescimento na participação olímpica ao longo das décadas, especialmente após 1950, que coincidiu com o aumento de países participantes e o interesse global pelos Jogos Olímpicos. Esse aumento representa não apenas uma maior inclusão, mas também uma tendência de profissionalização e maior alcance do espírito olímpico. A segmentação entre as edições de verão e inverno revela que, enquanto os Jogos de Verão atraem mais participantes, os Jogos de Inverno também têm mostrado um aumento gradual na participação, refletindo o desenvolvimento dos esportes de neve e gelo em várias regiões.

### Representação e Desempenho por País

Estados Unidos, Rússia e Alemanha aparecem como as nações com maior número de atletas e conquistas. Esses países, notadamente, têm um histórico de investimento significativo em programas esportivos, o que os coloca em vantagem nos Jogos. O número de medalhas por país reflete não apenas a quantidade de atletas, mas também o foco em modalidades nas quais esses países são tradicionalmente fortes. Além disso, países com recursos limitados ainda enfrentam desafios para competir em larga escala, sugerindo que apoio e desenvolvimento esportivo são fatores críticos para o sucesso.

#### Correlações Entre Atributos e Conquista de Medalhas

A análise de correlações entre idade, altura, peso e a conquista de medalhas revelou algumas tendências interessantes. Notou-se que atletas medalhistas tendem a se concentrar em uma faixa etária menor, próxima ao pico da performance física. A altura e o peso dos medalhistas apresentaram leve correlação positiva, sugerindo que características físicas podem influenciar o desempenho dependendo da modalidade esportiva. No entanto, essas variáveis variam amplamente entre modalidades, e outras características, como treinamento e condições físicas específicas, também desempenham um papel vital.

## Conclusão Geral

Em suma, a análise dos dados dos atletas olímpicos destaca que a performance de elite é um reflexo de múltiplos fatores, incluindo demografia, suporte governamental, histórico de investimento esportivo e características físicas específicas que variam conforme a modalidade. Essa análise oferece uma visão integrada sobre o perfil de atletas olímpicos de sucesso e destaca a importância de políticas esportivas para fomentar talentos. Com a globalização dos Jogos Olímpicos e o avanço da tecnologia no esporte, espera-se que novas tendências e padrões continuem a emergir.
