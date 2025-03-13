# Self-Admitted Technical Debt and Comments’ Polarity: An Empirical Study

Referência:
Cassee, Nathan; Zampetti, Fiorella; Novielli, Nicole; Serebrenik, Alexander; Di Penta, Massimiliano. "Self-Admitted Technical Debt and Comments’ Polarity: An Empirical Study." Empirical Software Engineering (2022) 27:139. https://doi.org/10.1007/s10664-021-10031-3

## 1. Fichamento de Conteúdo

O artigo analisa como desenvolvedores documentam a dívida técnica autoassumida (SATD) em comentários de código, explorando se a polaridade dessas anotações indica urgência ou gravidade do problema.

Os autores analisaram manualmente 1038 comentários SATD de projetos open-source, categorizando-os por tipo de dívida e tom emocional. Uma pesquisa com 46 desenvolvedores avaliou a percepção deles sobre o uso de comentários negativos para destacar problemas técnicos.

Os resultados mostram que 41% das SATDs estão ligadas a más decisões de implementação e 22% a funcionalidades incompletas. revelou também que embora 30% dos desenvolvedores usem comentários negativos como indicador de prioridade, 50% preferem discutir SATD em issue trackers como Jira. O estudo por fim reforça a importância de melhores ferramentas para gerencia automatica desses SATD.

## 2. Fichamento Bibliográfico

* _Self-Admitted Technical Debt_ (Dívida técnica autoadmitida): Refere-se a comentários e deixados pelos próprios desenvolvedores no código-fonte, indicando problemas técnicos conhecidos, como código mal estruturado, funcionalidades incompletas ou decisões de design que precisarão ser revisadas no futuro (página 1).

* _Polarity of SATD Comments_ (Polaridade dos Comentários SATD): Classificação da tonalidade emocional dos comentários SATD em negativa, neutra ou mista. Comentários com polaridade negativa tendem a indicar maior urgência ou frustração dos desenvolvedores em relação à dívida técnica mencionada (página 4).

* _Sentiment Analysis_ (Análise de Sentimentos): Técnica de processamento de linguagem natural usada para identificar e classificar a polaridade emocional de textos. No estudo, essa técnica foi aplicada para avaliar se comentários SATD expressam frustração, urgência ou neutralidade (página 6).

* _Issue Trackers_ (Rastreamento de Problemas): Ferramentas como Jira e GitHub Issues, que permitem o registro, categorização e acompanhamento de problemas e melhorias no código. O estudo aponta que muitos desenvolvedores preferem discutir SATD nesses sistemas, em vez de usar apenas comentários no código (página 10).
## 3. Fichamento de Citações

* _"The way a SATD comment is written, and specifically its polarity, may be a proxy indicator of the severity of the problem."_

* _"Self-Admitted Technical Debt comments are mainly used for annotating poor implementation choices (41%) and partially implemented functionality (22%)."_

* _"Around 30% of the survey respondents agree on using/interpreting negative sentiment as a proxy for priority."_

* _"Better tool support is required for SATD management, particularly in prioritizing technical debt resolution."_

* _"50% of developers indicate that it would be better to discuss SATD on issue trackers and not in the source code."_
