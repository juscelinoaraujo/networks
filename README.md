# Algoritmos e Estruturas de Dados II

**Autor: Juscelino Pereira de Araújo**

Este repositório destina-se ao compartilhamento dos artefatos produzidos na disciplina DCA3702 - Algoritmos e Estruturas de Dados II, ministrada pelo professor Ivanovitch Medeiros da Universidade Federal do Rio Grande do Norte (UFRN) no semestre 2025.1. Cada seção irá tratar de um diferente projeto desenvolvido ao longo do semestre.

## Projeto 1 - Redes Temporais de Coautoria

As redes de coautoria em trabalhos científicos são um importante ferramenta indicativa de colaboração entre pesquisadores, refletindo tanto a integração acadêmica quanto o compartilhamento do conhecimento produzido entre diferentes instituições. Por meio delas, é possível observar como o desenvolvimento científico se articula de maneira coletiva, favorecendo a inovação, o aumento da produtividade científica e a disseminação de ideias. Assim, a análise das redes de coautoria permite identificar pesquisadores mais influentes, grupos de pesquisa com maior consolidação e possíveis lacunas de colaboração, servindo como ferramenta estratégica para o planejamento de políticas científicas e acadêmicas.

Neste projeto é feita uma análise das redes de coautoria no âmbito do Programa de Pós-Graduação em Engenharia Elétrica e de Computação da Universidade Federal do Rio Grande do Norte (PPGEEC/UFRN) desde o ano 2010 até o presente. Tal análise é relevante por permitir uma compreensão aprofundada da evolução da colaboração entre seus docentes, discentes e parceiros externos. Esse tipo de estudo possibilita identificar tendências de pesquisa, áreas com maior interação científica e o impacto da produção acadêmica do programa ao longo do tempo. Além disso, ao mapear essas redes, pode-se avaliar o alcance e a inserção do PPGEEC no cenário nacional e internacional, bem como subsidiar ações que promovam uma maior integração entre pesquisadores e fortaleçam a excelência acadêmica do programa.

### Evoluçao das redes de coautoria do PPGEEC ao longo dos anos



Uma primeira análise feita sobre os dados das redes de coautoria do PPGEEC é a sua evolução ao longo do tempo de acordo com algumas métricas. Foram escolhidas as seguintes para fundamentar a análise:
* Densidade;
* Número de vétices;
* Número de arestas;
* Número médio de vizinhos;
* Distribuição do número de vizinhos.

O gráfico a seguir mostra a evolução comparada, mediante séries temporais, entre as métricas de densidade, número de arestas, número de vértices e número médio de arestas. Os valores foram normalizados entre 0 e 1 para possibilitar uma comparação mais adequada. É possível ver uma tendência de crescimento até 2019 no número de vértices, número de arestas e número médio de vizinhos. A patir de 2020 passam a ser peceptíveis sinais de queda que muito provavelmente são os efeitos do início da pademia do novo coronavírus. 

![](fig/evolucao.png)

O gráfico a seguir, do tipo *ridgeline*, traz uma estimativa das funções de densidade de probabilidade do número de vizinhos em cada uma das edes anuais. A cor da área sob a curva da distribuição de cada ano está relacionada à quantidade de arestas no grafo. Tal escolha foi feita patindo do princípio de que ao analisar redes de coautoria, mais significativa que a quantidade de pesquisadores é a existência de colaboação entre os pesquisadores presentes.

![](fig/ridgeline.png)

### Redes de coautoria do PPGEEC nos períodos referentes às avaliações quadrienais da CAPES

![](fig/quad_2010_2012.png)
![](fig/quad_2013_2016.png)
![](fig/quad_2017_2020.png)
![](fig/quad_2021_2024.png)

### Um subgrafo com vértices de alto grau e rede ego do vértice de maior grau

![](fig/geral.png)
![](fig/subgrafo.png)
![](fig/valentim_ego_net.png)
![](fig/valentim_ego_subnet.png)

Maiores detalhes sobre as análises feitas podem ser encontrados neste [notebook](). Há também um [vídeo explicativo]() sobre o trabalho realizado.

*Na elaboração dos textos que dão suporte às análises técnicas apresentadas neste documento, fez-se uso da ferramenta ChatGPT, da OpenAI. Todo o texto foi revisado minuciosamente pelo autor para garantir precisão e adequação ao contexto.*
