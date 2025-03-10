Sentiment Analysis of Commit Comments in GitHub: An Empirical Study
Referência:
Guzman, Emitza; Azócar, David; Li, Yang. "Sentiment Analysis of Commit Comments in GitHub: An Empirical Study," in MSR '14, May 31 - June 1, 2014, Hyderabad, India. DOI: 10.1145/2597073.2597118.

1. Fichamento de Conteúdo
O artigo investiga como emoções são expressas nos comentários de commits em projetos open-source no GitHub, analisando fatores como linguagem de programação, horário e dia da semana do commit, distribuição geográfica da equipe e aprovação do projeto. Para isso, os autores aplicam análise de sentimentos utilizando a ferramenta SentiStrength, que avalia a polaridade emocional das mensagens. Os resultados mostram que projetos escritos em Java possuem uma maior incidência de comentários negativos, enquanto projetos com equipes distribuídas geograficamente apresentam maior positividade. Além disso, os commits realizados às segundas-feiras tendem a ter uma carga emocional mais negativa. Apesar de os valores médios de sentimento tenderem à neutralidade, foi possível identificar padrões emocionais relevantes. O estudo reforça a importância de considerar diferentes métricas de emoção para melhor compreender o impacto do ambiente colaborativo no desenvolvimento de software.

2. Fichamento Bibliográfico
SentiStrength é uma ferramenta lexical de análise de sentimentos que atribui valores entre -5 e 5 às palavras de um texto, considerando modificadores e contexto para ajustar os escores de emoção (p. 3).
Commit comments negativos em Java: Projetos desenvolvidos em Java apresentaram comentários de commits significativamente mais negativos em comparação a outras linguagens como C, C++, JavaScript e Python (p. 5).
Influência do dia da semana: Commits feitos às segundas-feiras tendem a expressar emoções mais negativas do que os realizados em outros dias da semana (p. 6).
Distribuição geográfica e emoções: Projetos com equipes mais distribuídas geograficamente apresentam uma correlação positiva com o número de comentários de commits positivos (p. 7).
Correlação com aprovação do projeto: Não foi encontrada uma correlação significativa entre a quantidade de estrelas recebidas por um projeto no GitHub e a média geral dos sentimentos expressos nos commits (p. 8).

3. Fichamento de Citações
"Projects developed in Java tend to have more negative commit comments." (p. 5)
"Commit comments written on Mondays tend to a more negative emotion." (p. 6)
"We found no significant correlation between the emotion score of the commit comments and the number of countries or continents in which each project was distributed." (p. 7)
"Projects with a higher distribution, either country or continent wise, tend to have a higher amount of positive emotions in their positive commit comments." (p. 7)
"We tested the correlation between the average emotion score of each project and its number of stars but found no correlation." (p. 8)
"The definition of further metrics concerning emotions for open source projects will be the subject of future work." (p. 9)
