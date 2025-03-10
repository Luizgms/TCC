# Sentiment Analysis of Commit Comments in GitHub: An Empirical Study
Referência:
Guzman, Emitza; Azócar, David; Li, Yang. "Sentiment Analysis of Commit Comments in GitHub: An Empirical Study," in MSR '14, May 31 - June 1, 2014, Hyderabad, India. DOI: 10.1145/2597073.2597118.

## 1. Fichamento de Conteúdo
Este artigo também analisa os sentimentos dos desenvolvedores no GitHub, mas com um foco mais amplo, considerando comentários em issues, pull requests e commits. O estudo busca identificar padrões emocionais ao longo do tempo, investigando como os sentimentos variam de acordo com o dia da semana, o curso do projeto e a linguagem de programação utilizada.

Os autores utilizaram SentiStrength para classificar os sentimentos dos comentários em milhares de repositórios. Descobriram que segundas-feiras, sextas-feiras e sábados são os dias com maior carga emocional negativa, o que pode estar relacionado à pressão por entregas no início e no final da semana. Além disso, comentários em issues e pull requests são frequentemente mais negativos do que aqueles em commits, já que muitas dessas mensagens refletem problemas no código ou solicitações de mudança.

Outro achado interessante foi a relação entre linguagem de programação e sentimento. Diferente do estudo anterior, este artigo identificou que Python e Java tendem a ter comentários mais positivos, enquanto C e C++ são mais negativos. Isso pode ser explicado pela complexidade e rigidez dessas últimas linguagens, que exigem mais esforço cognitivo e podem gerar frustrações.

O artigo é bem estruturado e reforça a importância de considerar o aspecto emocional na colaboração em código aberto. No entanto, senti falta de uma análise mais detalhada sobre a relação entre sentimentos e a qualidade do código produzido. Ainda assim, a pesquisa traz contribuições valiosas e sugere caminhos interessantes para futuros estudos.

## 2. Fichamento Bibliográfico
* SentiStrength é uma ferramenta lexical de análise de sentimentos que atribui valores entre -5 e 5 às palavras de um texto, considerando modificadores e contexto para ajustar os escores de emoção.
* Commit comments negativos em Java: Projetos desenvolvidos em Java apresentaram comentários de commits significativamente mais negativos em comparação a outras linguagens como C, C++, JavaScript e Python.
* Influência do dia da semana: Commits feitos às segundas-feiras tendem a expressar emoções mais negativas do que os realizados em outros dias da semana.
* Distribuição geográfica e emoções: Projetos com equipes mais distribuídas geograficamente apresentam uma correlação positiva com o número de comentários de commits positivos.
* Correlação com aprovação do projeto: Não foi encontrada uma correlação significativa entre a quantidade de estrelas recebidas por um projeto no GitHub e a média geral dos sentimentos expressos nos commits.

## 3. Fichamento de Citações
* "Projects developed in Java tend to have more negative commit comments." 
* "Commit comments written on Mondays tend to a more negative emotion." 
* "We found no significant correlation between the emotion score of the commit comments and the number of countries or continents in which each project was distributed." 
* "Projects with a higher distribution, either country or continent wise, tend to have a higher amount of positive emotions in their positive commit comments."
* "We tested the correlation between the average emotion score of each project and its number of stars but found no correlation." 
* "The definition of further metrics concerning emotions for open source projects will be the subject of future work."
