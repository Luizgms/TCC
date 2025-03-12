# Self-Admitted Technical Debt and Comments’ Polarity: An Empirical Study

Referência:
Cassee, Nathan; Zampetti, Fiorella; Novielli, Nicole; Serebrenik, Alexander; Di Penta, Massimiliano. "Self-Admitted Technical Debt and Comments’ Polarity: An Empirical Study." Empirical Software Engineering (2022) 27:139. doi: 10.1007/s10664-022-10183-w

## 1. Fichamento de Conteúdo

O artigo analisa a relação entre o débito técnico autodeclarado pelos desenvolvedores e a forma como eles expressam seus comentários no código-fonte. Os autores buscam compreender se a maneira como um SATD(Self-Admitted Technical Deb) é escrito pode indicar a gravidade do problema ou a urgência para resolvê-lo.

O estudo se baseia em uma análise manual de 1038 comentários SATD e em uma pesquisa com 46 desenvolvedores profissionais. Os resultados mostram que a maioria dos SATDs está relacionada a escolhas de implementação ruins e funcionalidades que fora parcialmente implementadas. Um ponto interessante do estudo é a descoberta de que comentários mais negativos tendem a estar ligados a funcionalidades inacabadas que dependem de outras partes do sistema para serem finalizadas. Isso pode indicar um nível maior de frustração por parte dos desenvolvedores, além de ser um alerta sobre a complexidade da dependência entre módulos em projetos de software.

O artigo também traz uma visão interessante sobre como os desenvolvedores lidam com o SATD: cerca de 30% dos entrevistados acreditam que um tom negativo pode ser um indicativo de maior prioridade, enquanto 50% preferem que o SATD seja discutido em issue trackers, em vez de ser simplesmente documentado no código. Essa discussão é crucial, pois reflete a dificuldade de gerenciar a dívida técnica de forma eficiente, especialmente em projetos open-source, onde a colaboração é descentralizada. A pesquisa sugere que a gestão de SATD poderia ser aprimorada com ferramentas automatizadas que identifiquem e priorizem essas anotações, facilitando a manutenção e evolução do software.

## 2. Fichamento Bibliográfico

* _Self-Admitted Technical Debt_ (Dívida técnica autoadmitida): Refere-se a comentários e deixados pelos próprios desenvolvedores no código-fonte, indicando problemas técnicos conhecidos, como código mal estruturado, funcionalidades incompletas ou decisões de design que precisarão ser revisadas no futuro (página 1).

* _Polarity of SATD Comments_ (Polaridade dos Comentários SATD): Classificação da tonalidade emocional dos comentários SATD em negativa, neutra ou mista. Comentários com polaridade negativa tendem a indicar maior urgência ou frustração dos desenvolvedores em relação à dívida técnica mencionada (página 4).

* _Sentiment Analysis_ (Análise de Sentimentos): Técnica de processamento de linguagem natural usada para identificar e classificar a polaridade emocional de textos. No estudo, essa técnica foi aplicada para avaliar se comentários SATD expressam frustração, urgência ou neutralidade (página 6).

* _Issue Trackers_ (Rastreamento de Problemas): Ferramentas como Jira e GitHub Issues, que permitem o registro, categorização e acompanhamento de problemas e melhorias no código. O estudo aponta que muitos desenvolvedores preferem discutir SATD nesses sistemas, em vez de usar apenas comentários no código (página 10).
## 3. Fichamento de Citações

* "The way a SATD comment is written, and specifically its polarity, may be a proxy indicator of the severity of the problem."

* "Self-Admitted Technical Debt comments are mainly used for annotating poor implementation choices (41%) and partially implemented functionality (22%)."

* "Around 30% of the survey respondents agree on using/interpreting negative sentiment as a proxy for priority."

* "Better tool support is required for SATD management, particularly in prioritizing technical debt resolution."

* "50% of developers indicate that it would be better to discuss SATD on issue trackers and not in the source code."
