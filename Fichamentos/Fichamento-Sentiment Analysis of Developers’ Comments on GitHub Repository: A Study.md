# Sentiment Analysis of Developers’ Comments on GitHub Repository: A Study
Referência:
Kumar, Aman; Khare, Manish; Tiwari, Saurabh. "Sentiment Analysis of Developers’ Comments on GitHub Repository: A Study," in The 14th International Conference on Advanced Computational Intelligence (ICACI), July 15-17, 2022, Wuhan, China. https://doi.org/10.1109/ICACI55529.2022.9837754
## 1. Fichamento de Conteúdo

  Este artigo investiga os sentimentos dos desenvolvedores em issues, pull requests e commits no GitHub. O objetivo é compreender como as emoções variam ao longo do tempo, dependendo do dia da semana, do tempo de vida do projeto e da linguagem de programação utilizada. A pesquisa se baseia na premissa de que emoções podem afetar a produtividade e qualidade do codigo em projetos open-source.

Para a análise, os autores ultilizaram o pyGitHub para coletar comentários de diversos repositórios e aplicaram a ferramenta SentiStrength para classificar os sentimentos por linguagem de programação. Foram analisados repositórios populares de Python, Java, C, C++ e .NET, escolhidos com base na quantidade de estrelas no GitHub. Além disso, foram agrupados os comentários por períodos de tempo desde a criação do projeto, a fim de identificar variações emocionais ao longo do tempo.

Os resultados revelaram que comentários escritos às segundas-feiras são mais negativos do que em outros dias, possivelmente devido ao retorno ao trabalho. Além disso, issues e pull requests apresentam sentimentos mais negativos do que commits, pois envolvem a discussão de problemas e mudanças no código. Em termos de linguagem, projetos em Python e Java possuem mais comentários positivos, enquanto C e C++ tendem a ter comentários mais negativos, possivelmente devido à maior complexidade dessas linguagens.

## 2. Fichamento Bibliográfico
*    SentiStrength: Ferramenta de análise de sentimentos que atribui valores entre -5 e 5 às palavras de um texto, considerando contexto e modificadores para ajustar os escores emocionais (p. 92)​.
*   _Programming Language Sentiment_ (Sentimento por Linguagem de Programação): Conceito analisado no artigo que relaciona a linguagem de programação utilizada no projeto com a polaridade e sentimento dos comentários. O estudo mostrou que Python e Java apresentam mais comentários positivos do que C e C++ (p. 95).
*    pyGitHub: Biblioteca em Python usada para interagir com a API do GitHub e coletar os comentários analisados no estudo. Facilitou a extração de dados dos repositórios para a análise de sentimentos (p. 92)​

## 3. Fichamento de Citações
*    _"Comments written on Monday have more negative polarity emotions as compared to other days of the week."_
*    _"Issue comments and pull request comments tend to have more negative emotions compared to commit comments."_
*    _"The sentiment of developers in a project is mostly negative in the early stages, becoming more positive after two or more years."_
*    _"We observed that Python and Java repositories have more positive comments compared to C and C++ projects."_
*    _"Our study highlights the importance of understanding developer emotions to improve collaboration in open-source projects."_
