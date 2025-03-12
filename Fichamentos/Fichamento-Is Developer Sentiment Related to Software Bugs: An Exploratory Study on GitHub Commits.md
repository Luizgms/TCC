# Is Developer Sentiment Related to Software Bugs: An Exploratory Study on GitHub Commits
Referência:
Huq, Syed Fatiul; Sadiq, Ali Zafar; Sakib, Kazi. "Is Developer Sentiment Related to Software Bugs: An Exploratory Study on GitHub Commits," in SANER 2020, London, ON, Canada, 2020. DOI: 10.1109/SANER48275.2020.9054812.

## 1. Fichamento de Conteúdo
 Este artigo explora a relação entre o sentimento do desenvolvedor e a introdução ou correção de bugs no software. Ao contrário dos estudos anteriores, que analisaram sentimentos em um contexto mais geral, aqui os autores investigam como a negatividade ou positividade das mensagens de commits pode indicar problemas no código.

Para isso, eles classificaram os commits em quatro categorias: commits que introduzem bugs, commits  que podem influenciar a introdução de bugs, commits que corrigem bugs, commits que, ao tentar corrigir um bug, acabam criando um novo.
  
Utilizando a ferramenta Senti4SD, os autores descobriram que todos os commits relacionados a bugs tendem a ser mais negativos do que os commits regulares. Além disso, commits de correção de bugs (FCs) e aqueles que criam novos bugs ao tentar corrigir (FIFs) apresentam os sentimentos mais negativos e menos neutros. Isso sugere que o estresse e a frustração do desenvolvedor ao lidar com erros podem afetar a qualidade do código produzido.

A ideia de que emoções negativas podem estar ligadas à introdução de bugs é  interessante. Se confirmada em estudos futuros, essa abordagem pode ser usada para prever problemas antes que eles aconteçam, ajudando equipes a intervir precocemente. No entanto, o estudo tem algumas limitações, como a falta de um modelo preditivo mais refinado e a necessidade de testes em um conjunto de dados ainda maior. Mesmo assim, os resultados são promissores e indicam um caminho relevante para melhorar a qualidade do software através da análise de sentimentos.

## 2. Fichamento Bibliográfico
*    Fix-Inducing Changes (FICs): São commits que introduzem bugs no software. Esses commits tendem a ter mensagens mais negativas do que commits regulares.
*    Fixing Changes (FCs): Commits que corrigem bugs. São mais negativos do que commits comuns, refletindo a frustração do desenvolvedor ao lidar com erros.
*    Fix-Inducing Fixes (FIFs): Correções de bugs que, por erro, introduzem novos bugs. Esses commits são os mais negativos e menos neutros, sugerindo alta carga emocional e estresse do desenvolvedor.
*    Senti4SD: Ferramenta de análise de sentimentos especializada em engenharia de software, que considera termos técnicos como "bug" e "error" sem atribuir a eles conotações emocionais padrão.
*    Relação entre sentimentos e bugs: O estudo encontrou que commits negativos e com pouca neutralidade estão mais propensos a introduzir ou corrigir bugs, sugerindo que a emoção do desenvolvedor pode influenciar a qualidade do código.
## 3. Fichamento de Citações
*    "Commits that introduce, precede or fix bugs are significantly more negative than regular Commits." 
*    "Fix-inducing fixes (FIFs) are the most negative commits, showing a strong correlation between high emotional intensity and the introduction of new bugs." 
*    "Neutrality is more predominant in regular Commits, whereas commits related to bugs exhibit higher emotional intensity." 
*    "Senti4SD provides a domain-specific sentiment analysis approach, adjusting sentiment scores for words commonly used in software development." 
*    "The results suggest that monitoring developer sentiment could help predict bug-prone commits, aiding software quality assurance." 
