# Characterizing Commits in Open-Source Software

Ferreira, Mívian M.; Gonçalves, Diego Santos; Bigonha, Mariza A. S.; Ferreira, Kecia A. M. "Characterizing Commits in Open-Source Software," in XXI Brazilian Symposium on Software Quality (SBQS ’22), November 7–10, 2022, Curitiba, Brazil. ACM, New York, NY, USA, 10 pages. doi: 10.1145/3571473.3571508

## 1. Fichamento de Conteúdo

O artigo aborda a caracterização de commits em projetos de software open-source no GitHub, destacando como seu entendimento pode evitar vieses em pesquisas que analisam dados de commits. O estudo analisa aproximadamente 1 milhão de commits de 24 repositórios populares de projetos baseados em Java, considerando quatro aspectos principais: (i) tamanho dos commits em número total de arquivos; (ii) tamanho dos commits considerando apenas arquivos de código-fonte Java; (iii) tamanho dos commits categorizados por atividade; e (iv) intervalo de tempo entre commits feitos pelos desenvolvedores. Os resultados indicam que o tamanho dos commits segue uma distribuição de cauda longa, com a maioria dos commits envolvendo entre 1 e 10 arquivos e entre 1 e 4 arquivos de código-fonte Java. Além disso, a análise revela que commits grandes não estão restritos a atividades de merge ou gestão e que o intervalo médio entre commits é de aproximadamente 8 horas. O estudo sugere que pesquisadores devem levar em conta essas características para evitar conclusões enviesadas ao analisar dados de commits. Para os profissionais, os achados podem auxiliar na gestão e planejamento de atividades de software.

## 2. Fichamento Bibliográfico

* A maioria dos commits em repositórios open-source contém entre 1 e 10 arquivos modificados, seguindo uma distribuição de cauda longa.

* O tamanho dos commits envolvendo apenas arquivos .java também segue uma distribuição de cauda longa, com a maioria modificando entre 1 e 4 arquivos.

* Os commits foram classificados em seis categorias principais: Merge, Engenharia Corretiva, Engenharia Progressiva, Reengenharia, Gestão e Outros.

* O tempo médio entre commits realizados por um desenvolvedor é de aproximadamente 8 horas, e essa distribuição se aproxima de uma distribuição normal.

* Commits de grande volume não se restringem a atividades de Merge ou Gestão, podendo ocorrer em outras categorias, como Engenharia Progressiva e Reengenharia.

## 3. Fichamento de Citações

* "The size of commits follows a heavy-tailed distribution; most commits involve one to 10 files."

* "On average, a developer proceeds a commit every eight hours."

* "The results indicate that the distributions are approximately Normal distributions."

* "Large commits do not occur only in Merge or Management activities."

* "We found that 30% of commits involve more than one activity type, indicating the extent of tangled changes in software repositories."
