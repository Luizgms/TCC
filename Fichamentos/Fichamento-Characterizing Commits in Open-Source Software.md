# Characterizing Commits in Open-Source Software

Ferreira, Mívian M.; Gonçalves, Diego Santos; Bigonha, Mariza A. S.; Ferreira, Kecia A. M. "Characterizing Commits in Open-Source Software," in XXI Brazilian Symposium on Software Quality (SBQS ’22), November 7–10, 2022, Curitiba, Brazil. ACM, New York, NY, USA, 10 pages. doi: 10.1145/3571473.3571508

## 1. Fichamento de Conteúdo

O artigo aborda a caracterização de commits em projetos de software open-source no GitHub, destacando como seu entendimento pode evitar vieses em pesquisas que analisam dados de commits. 

O estudo analisa aproximadamente 1 milhão de commits de 24 repositórios populares de projetos baseados em Java, considerando quatro aspectos principais: (i) tamanho dos commits em número total de arquivos; (ii) tamanho dos commits considerando apenas arquivos de código-fonte Java; (iii) tamanho dos commits categorizados por atividade; e (iv) intervalo de tempo entre commits feitos pelos desenvolvedores. Os resultados indicam que o tamanho dos commits segue uma distribuição de cauda longa, com a maioria dos commits envolvendo entre 1 e 10 arquivos e entre 1 e 4 arquivos de código-fonte Java. 

Além disso, a análise revela que commits grandes não estão restritos a atividades de merge ou gestão e que o intervalo médio entre commits é de aproximadamente 8 horas. O estudo sugere que pesquisadores devem levar em conta essas características para evitar conclusões enviesadas ao analisar dados de commits. Para os profissionais, os achados podem auxiliar na gestão e planejamento de atividades de software.

## 2. Fichamento Bibliográfico

* _Long Tail Distribution_ Distribuição de Cauda Longa: Padrão estatístico onde a maioria dos commits altera poucos arquivos, mas há casos extremos em que centenas de arquivos são modificados. Esse fenômeno influencia a análise de produtividade e padrões de contribuição (página 3).

* Categorias de Commits: Classificação das alterações no código-fonte em seis categorias principais: Merge (fusões de branches), Engenharia Corretiva (correção de bugs), Engenharia Progressiva (adição de funcionalidades), Reengenharia (melhoria do código), Gestão (tarefas administrativas) e Outros (casos não categorizáveis) (página 6).

* _Time between commits_ Tempo entre Commits: Tempo médio entre commits consecutivos feitos por um mesmo desenvolvedor, seguindo uma distribuição normal (página 8).

* API GraphQL do GitHub: Ferramenta utilizada para extrair e analisar os commits. O uso dessa API permite a obtenção eficiente de grandes volumes de dados sobre repositórios e atividades dos desenvolvedores (página 4).

## 3. Fichamento de Citações

* "The size of commits follows a heavy-tailed distribution; most commits involve one to 10 files."

* "On average, a developer proceeds a commit every eight hours."

* "The results indicate that the distributions are approximately Normal distributions."

* "Large commits do not occur only in Merge or Management activities."

* "We found that 30% of commits involve more than one activity type, indicating the extent of tangled changes in software repositories."
