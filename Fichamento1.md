**Referência:**  
Kavaler, D.; Trockman, A.; Vasilescu, B.; Filkov, V. *"Tool Choice Matters: JavaScript Quality Assurance Tools and Usage Outcomes in GitHub Projects."* IEEE/ACM International Conference on Software Engineering (ICSE), 2021. doi: 10.1109/ICSE43902.2021.00027

### 1. Fichamento de Conteúdo
O artigo investiga como a escolha e o uso de ferramentas de garantia de qualidade (*quality assurance*, QA) impactam projetos JavaScript hospedados no GitHub. Os autores analisaram dados de **1.601 projetos npm ativos**, focando em três categorias de ferramentas: *linters*, gerenciadores de dependências e ferramentas de cobertura de testes. As métricas avaliadas foram: prevalência de issues, churn de código, número de pull requests (PRs) e número de contribuidores.

Os principais achados incluem:

- **Trocas de ferramentas**: Muitos projetos substituíram ferramentas dentro da mesma categoria, indicando insatisfação ou necessidade de adaptação.
- **Impacto das ferramentas**: Apenas algumas ferramentas mostraram efeitos consistentemente positivos nas métricas analisadas.
- **Ordem de adoção**: A sequência em que as ferramentas foram adotadas influenciou os resultados observados.

### 2. Conceitos e Definições
- *Linters*: Ferramentas que analisam o código-fonte em busca de erros, más práticas ou inconsistências de estilo.
- *Dependency managers*: Ferramentas que gerenciam as dependências de um projeto, incluindo versões e atualizações.
- *Test coverage tools*: Ferramentas que medem a extensão dos testes automatizados em relação ao código-fonte.
- *Prevalência de issues*: Número de problemas ou bugs reportados em um projeto ao longo do tempo.
- *Churn de código*: Quantidade de alterações no código-fonte, incluindo adições, modificações e remoções.
- *Pull requests (PRs)*: Solicitações de integração de código de um branch para o branch principal do projeto.
- *Contribuidores*: Número de desenvolvedores que contribuem ativamente para o projeto.

### 3. Fichamento de Citações
- *"We treat each tool adoption event as an intervention and examine its impact on project outcomes."*
- *"Only some tools within the same category seem to be generally beneficial."*
- *"The order in which tools are adopted matters."*
- *"*standardJS*, *coveralls*, and *david* stand out as tools associated with post-adoption issue prevalence benefits."*
