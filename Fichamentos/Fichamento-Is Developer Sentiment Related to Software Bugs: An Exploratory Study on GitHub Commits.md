# Is Developer Sentiment Related to Software Bugs: An Exploratory Study on GitHub Commits
Referência:
Huq, Syed Fatiul; Sadiq, Ali Zafar; Sakib, Kazi. "Is Developer Sentiment Related to Software Bugs: An Exploratory Study on GitHub Commits," in SANER 2020, London, ON, Canada, 2020. https://doi.org/10.1109/SANER48275.2020.9054801.

## 1. Fichamento de Conteúdo
Este artigo explora a relação entre os sentimentos dos desenvolvedores e a introdução ou correção de bugs no código. Os autores analisam diferentes tipos de commits para verificar se há uma relação entre sentimento e qualidade do código.

Para a análise, foram extraídos commits de 13 repositórios populares do GitHub e categorizados em quatro tipos: _Fix-Inducing Changes_ (FICs), _Parent of FICs_ (pFICs), _Fixing Changes_ (FCs) e _Fix-Inducing Fixes_ (FIFs) . A ferramenta Senti4SD, foi utilizada para classificar os sentimentos nas mensagens de commit.

Os resultados mostraram que todos os commits relacionados a bugs são mais negativos do que commits regulares. Em especial, commits FIFs foram os mais negativos e menos neutros, indicando que a frustração do desenvolvedor pode levar à introdução de novos erros. Além disso, FCs com mensagens muito negativas têm maior chance de se tornarem FIFs, sugerindo que o estresse e a pressão podem comprometer a qualidade das correções. O estudo reforça que a análise de sentimentos pode ser uma ferramenta útil para prever e mitigar problemas de qualidade no código.

## 2. Fichamento Bibliográfico
*    _Fix-Inducing Changes_ (FICs): São commits que introduzem bugs no software. Esses commits tendem a ter mensagens mais negativas do que commits regulares.
*    _Fixing Changes_ (FCs): Commits que corrigem bugs. São mais negativos do que commits comuns, refletindo a frustração do desenvolvedor ao lidar com erros.
*    _Fix-Inducing Fixes_ (FIFs): Correções de bugs que, por erro, introduzem novos bugs. Esses commits são os mais negativos e menos neutros, sugerindo alta carga emocional e estresse do desenvolvedor.
*    Senti4SD: Ferramenta de análise de sentimentos especializada em engenharia de software, que considera termos técnicos como "bug" e "error" sem atribuir a eles conotações emocionais padrão.

## 3. Fichamento de Citações
*    _"Commits that introduce, precede or fix bugs are significantly more negative than regular Commits."_
*    _"Fix-inducing fixes (FIFs) are the most negative commits, showing a strong correlation between high emotional intensity and the introduction of new bugs."_
*    _"Neutrality is more predominant in regular Commits, whereas commits related to bugs exhibit higher emotional intensity."_
*    _"Senti4SD provides a domain-specific sentiment analysis approach, adjusting sentiment scores for words commonly used in software development."_
*    _"The results suggest that monitoring developer sentiment could help predict bug-prone commits, aiding software quality assurance."_
