# Sentiment Analysis of Commit Comments in GitHub: An Empirical Study
Referência:
Guzman, Emitza; Azócar, David; Li, Yang. "Sentiment Analysis of Commit Comments in GitHub: An Empirical Study," in MSR '14, May 31 - June 1, 2014, Hyderabad, India. DOI: 10.1145/2597073.2597118.

## 1. Fichamento de Conteúdo
O artigo explora como emoções são expressas nos comentários de commits de projetos open-source no GitHub e sua relação com fatores como linguagem de programação, dia da semana e distribuição geográfica das equipes pelo globo. Utilizando a ferramenta SentiStrength, os autores analisaram mais de 60 mil comentários de commits para determinar a polaridade emocional desses textos curtos,

Os resultados revelaram que projetos em Java tendem a apresentar comentários mais negativos do que em projetos feitos com Python ou Ruby. Além disso, commits realizados as segundas-feiras são geralmente mais negativos, possivelmente refletindo o desânimo do trabalho após o final de semana. Outra descoberta é que equipes mais distribuídas geograficamente produzem comentários mais positivos, o que pode indicar que times globais precisam ser mais cuidadosos na comunicação em uma lingua em comum.

O estudo tras pontos positivos, como o uso de um grande conjunto de dados. Porém, um ponto que poderia ser melhorado é a análise qualitativa dos comentários. Os autores apenas mediram a polaridade emocional dos comenterioS, seria interessante compreender o contexto dessas emoções e como elas impactam o desenvolvimento dos projetos.

## 2. Fichamento Bibliográfico
* SentiStrength é uma ferramenta lexical de análise de sentimentos que atribui valores entre -5 e 5 às palavras de um texto, considerando modificadores e contexto para ajustar os escores de emoção.
  
* _Lexical Sentiment Analysis_ (Análise de Sentimentos Lexical): Técnica que identifica sentimentos em textos com base em dicionários predefinidos de palavras positivas e negativas. No artigo, essa abordagem foi utilizada para avaliar as emoções nos comentários de commits (p. 3)​.
  
* _Geographical Distribution_ (Distribuição Geográfica): Refere-se à dispersão de uma equipe de desenvolvimento ao redor do mundo. O estudo encontrou uma correlação entre equipes distribuídas globalmente e comentários mais positivos nos commits (p. 5)​.

* _Wilcoxon Rank Sum Test_ (Teste de Soma de Postos de Wilcoxon): Teste estatístico não paramétrico utilizado no artigo para comparar a distribuição dos sentimentos em diferentes grupos de commits, identificando diferenças significativas entre eles (p. 6)​


## 3. Fichamento de Citações
* "Projects developed in Java tend to have more negative commit comments." 
* "Commit comments written on Mondays tend to a more negative emotion." 
* "We found no significant correlation between the emotion score of the commit comments and the number of countries or continents in which each project was distributed." 
* "Projects with a higher distribution, either country or continent wise, tend to have a higher amount of positive emotions in their positive commit comments."
* "We tested the correlation between the average emotion score of each project and its number of stars but found no correlation." 
* "The definition of further metrics concerning emotions for open source projects will be the subject of future work."
