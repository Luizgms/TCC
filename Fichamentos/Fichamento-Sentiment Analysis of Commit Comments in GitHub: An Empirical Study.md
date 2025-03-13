# Sentiment Analysis of Commit Comments in GitHub: An Empirical Study
Referência:
Guzman, Emitza; Azócar, David; Li, Yang. "Sentiment Analysis of Commit Comments in GitHub: An Empirical Study," in MSR '14, May 31 - June 1, 2014, Hyderabad, India. https://doi.org/10.1145/2597073.2597118.

## 1. Fichamento de Conteúdo
O artigo investiga as emoções expressas nos comentários de commits em projetos open-source no GitHub. Os autores analisam a relação entre os sentimentos dos desenvolvedores e fatores como a linguagem de programação utilizada, o dia da semana em que os commits são feitos e a distribuição geográfica das equipes. 

Para realizar a análise, os pesquisadores coletaram 60.425 comentários de commits em 90 projetos populares do GitHub. Foi utilizada a ferramenta SentiStrength. Além disso, testes estatísticos, como o Wilcoxon Rank Sum Test, foram aplicados para verificar se diferenças observadas eram estatisticamente significativas.

Os resultados indicaram que projetos desenvolvidos em Java apresentam comentários mais negativos do que os escritos em C, C++, JavaScript e Python. Além disso, commits realizados às segundas-feiras são mais propensos a expressar emoções negativas. Por fim, os autores atestaram que equipes geograficamente distribuídas apresentaram comentários mais positivos, possivelmente devido à necessidade de uma comunicação mais clara e respeitosa para uam melhor compreensão. Apesar da predominância de comentários neutros, o estudo sugere que padrões emocionais podem influenciar o ambiente colaborativo.

## 2. Fichamento Bibliográfico
* SentiStrength é uma ferramenta lexical de análise de sentimentos que atribui valores entre -5 e 5 às palavras de um texto, considerando modificadores e contexto para ajustar os escores de emoção.
  
* _Lexical Sentiment Analysis_ (Análise de Sentimentos Lexical): Técnica que identifica sentimentos em textos com base em dicionários predefinidos de palavras positivas e negativas. No artigo, essa abordagem foi utilizada para avaliar as emoções nos comentários de commits (p. 3)​.
  
* _Geographical Distribution_ (Distribuição Geográfica): Refere-se à dispersão de uma equipe de desenvolvimento ao redor do mundo. O estudo encontrou uma correlação entre equipes distribuídas globalmente e comentários mais positivos nos commits (p. 5)​.

* _Wilcoxon Rank Sum Test_ (Teste de Soma de Postos de Wilcoxon): Teste estatístico não paramétrico utilizado no artigo para comparar a distribuição dos sentimentos em diferentes grupos de commits, identificando diferenças significativas entre eles (p. 6)​


## 3. Fichamento de Citações
* _"Projects developed in Java tend to have more negative commit comments."_
* _"Commit comments written on Mondays tend to a more negative emotion."_
* _"We found no significant correlation between the emotion score of the commit comments and the number of countries or continents in which each project was distributed."_
* _"Projects with a higher distribution, either country or continent wise, tend to have a higher amount of positive emotions in their positive commit comments."_
* _"We tested the correlation between the average emotion score of each project and its number of stars but found no correlation."_
* _"The definition of further metrics concerning emotions for open source projects will be the subject of future work."_
