# Characterizing Commits in Open-Source Software

Ferreira, Mívian M.; Gonçalves, Diego Santos; Bigonha, Mariza A. S.; Ferreira, Kecia A. M. "Characterizing Commits in Open-Source Software," in XXI Brazilian Symposium on Software Quality (SBQS ’22), November 7–10, 2022, Curitiba, Brazil. ACM, New York, NY, USA, 10 pages. https://doi.org/10.1145/3571473.3571508
## 1. Fichamento de Conteúdo

O artigo aborda a caracterização de commits em projetos de software open-source no GitHub, destacando como seu entendimento pode evitar vieses em pesquisas que analisam dados de commits. 

O estudo analisa aproximadamente 1 milhão de commits de 24 repositórios de projetos baseados em Java, considerando quatro características: tamanho dos commits em número total de arquivos, tamanho dos commits considerando apenas arquivos em java, tamanho dos commits categorizados por atividade e intervalo de tempo entre commits feitos pelos desenvolvedores. Os resultados indicam que o tamanho dos commits segue uma distribuição de cauda longa. 

Além disso, os autores revelam que commits grandes não estão restritos a atividades de merge ou gestão e que o intervalo médio entre commits é de aproximadamente 8 horas. O artigo sugere que pesquisadores devem levar em conta essas características para evitar conclusões enviesadas ao analisar dados de commits.

_-------------------------------------------------------

O artigo busca caracterizar commits em projetos open-source para evitar vieses em estudos com essa mesma proposta. Como os commits são a unidade básica para o versionamento do codigo, de acordo com os autores entender seus padrões ajuda a melhorar a análise e a gestão de projetos.

A metodologia envolve a análise de 1 milhão de commits de 24 projetos Open-source mais populares em Java. Foram extraídos dados sobre tamanho dos commits, categorias de alteração e intervalo de tempo entre commits, usando a API GraphQL do GitHub e classificação por palavras-chave.

Os resultados mostram que a maioria dos commits envolve poucos arquivos (1 a 10). O intervalo médio entre commits é de 8 horas, seguindo distribuição normal. O artigo relata também que em alguns momentos ocorre oque foi chamado de "Distribuição de Calda Longa" onde um unico commit se modificam centenas ou até milhares de arquivos. Esses commits extremos puxam a cauda da distribuição para a direita, criando uma curva com um pico alto seguido de uma cauda longa , O estudo é relevante para melhorar a interpretação de dados de repositórios, embora  análise focada apenas em Java possa limitar sua aplicabilidade a outras linguagens.

## 2. Fichamento Bibliográfico

* _Long Tail Distribution_ (Distribuição de Cauda Longa): Padrão estatístico onde a maioria dos commits altera poucos arquivos, mas há casos extremos em que centenas de arquivos são modificados. Esse fenômeno influencia a análise de produtividade e padrões de contribuição (página 3).

* Categorias de Commits: Classificação das alterações no código-fonte em seis categorias principais: Merge (fusões de branches), Engenharia Corretiva (correção de bugs), Engenharia Progressiva (adição de funcionalidades), Reengenharia (melhoria do código), Gestão (tarefas administrativas) e Outros (casos não categorizáveis) (página 6).

* _Time between commits_ (Tempo entre Commits): Tempo médio entre commits consecutivos feitos por um mesmo desenvolvedor, seguindo uma distribuição normal (página 8).

* API GraphQL do GitHub: Ferramenta utilizada para extrair e analisar os commits. O uso dessa API permite a obtenção eficiente de grandes volumes de dados sobre repositórios e atividades dos desenvolvedores (página 4).

## 3. Fichamento de Citações

* _"The size of commits follows a heavy-tailed distribution; most commits involve one to 10 files."_

* _"On average, a developer proceeds a commit every eight hours."_

* _"The results indicate that the distributions are approximately Normal distributions."_

* _"Large commits do not occur only in Merge or Management activities."_

* _"We found that 30% of commits involve more than one activity type, indicating the extent of tangled changes in software repositories."_
