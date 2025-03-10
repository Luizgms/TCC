# Is Developer Sentiment Related to Software Bugs: An Exploratory Study on GitHub Commits
Referência:
Huq, Syed Fatiul; Sadiq, Ali Zafar; Sakib, Kazi. "Is Developer Sentiment Related to Software Bugs: An Exploratory Study on GitHub Commits," in SANER 2020, London, ON, Canada, 2020. DOI: 10.1109/SANER48275.2020.9054812.

## 1. Fichamento de Conteúdo
   O artigo investiga a relação entre o sentimento dos desenvolvedores e a introdução ou correção de bugs em commits no GitHub. Para isso, os autores analisam quatro tipos de commits: Fix-Inducing Changes (FICs) (commits que introduzem bugs), Parent of FICs (pFICs) (commits anteriores aos FICs), Fixing Changes (FCs) (commits que corrigem bugs) e Fix-Inducing Fixes (FIFs) (commits que, ao corrigirem um bug, introduzem novos erros). Utilizando a ferramenta Senti4SD, especializada em análise de sentimentos no domínio de engenharia de software, os autores identificam que todos os commits relacionados a bugs possuem sentimentos mais negativos do que commits regulares. Além disso, os commits que corrigem bugs (FCs) e aqueles que introduzem novos bugs ao tentar corrigir (FIFs) são os mais negativos. O estudo sugere que a análise de sentimentos pode ser usada como uma métrica para identificar potenciais problemas no desenvolvimento de software.

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
