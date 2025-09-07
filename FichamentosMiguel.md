
**Referência:**  
Kavaler, D.; Trockman, A.; Vasilescu, B.; Filkov, V. "Tool Choice Matters: JavaScript Quality Assurance Tools and Usage Outcomes in GitHub Projects." IEEE/ACM International Conference on Software Engineering (ICSE), 2021. doi: 10.1109/ICSE43902.2021.00027

### 1. Fichamento de Conteúdo
O artigo investiga como a escolha de ferramentas de garantia de qualidade (linters, gerenciadores de dependência e ferramentas de cobertura) afeta projetos JavaScript no GitHub. Com base em dados de milhares de projetos npm, os autores analisam o impacto da adoção de diferentes ferramentas sobre métricas como prevalência de issues, churn de código, número de PRs e contribuidores. As análises mostram que a escolha e a ordem de adoção das ferramentas têm impacto significativo, e que algumas ferramentas (como standardJS, david e coveralls) geram melhores resultados. O estudo reforça que decisões sobre ferramentas devem considerar contexto e evidências empíricas.

### 2. Fichamento Bibliográfico
- Ferramentas analisadas agrupadas em classes: linters, gerenciadores de dependência, cobertura de testes (p. 2).
- Métricas de resultado: issues, churn de código, PRs, contribuidores (p. 3).
- Métodos estatísticos com regressão de efeitos mistos (p. 4).
- Ordem de adoção influencia os resultados (p. 5).
- Algumas ferramentas geram impactos negativos dependendo do contexto (p. 6).

### 3. Fichamento de Citações
- "We treat each tool adoption event as an intervention..."
- "Only some tools within the same category seem to be generally beneficial."
- "The order in which tools are adopted matters."
- "standardJS, coveralls, and david stand out as tools associated with post-adoption issue prevalence benefits."

---


**Referência:**  
Golendukhina, V.; Lenarduzzi, V.; Felderer, M. "What is Software Quality for AI Engineers? Towards a Thinning of the Fog." CAIN’22, May 2022. doi: 10.1145/3522664.3528599

### 1. Fichamento de Conteúdo
O artigo investiga as estratégias de garantia de qualidade de software (SQA) adotadas durante o desenvolvimento, integração e manutenção de componentes baseados em IA/ML. A partir de entrevistas semiestruturadas com dez pequenas e médias empresas austríacas, os autores identificam 12 problemas comuns enfrentados na construção desses sistemas. Os principais problemas envolvem manipulação de dados, instabilidade de frameworks, comunicação entre equipes e erros invisíveis. A pesquisa mostra que os desafios são recorrentes em várias etapas do ciclo de vida e que as práticas de qualidade são aplicadas de forma ad hoc. O estudo conclui que é urgente adaptar métodos tradicionais de engenharia de software ao contexto específico de sistemas de IA.

### 2. Fichamento Bibliográfico
- Foram conduzidas entrevistas com representantes de 10 empresas austríacas de pequeno a médio porte (p. 2-3).
- Os principais problemas relatados envolvem preparação e qualidade dos dados, instabilidade de bibliotecas e falhas de comunicação entre equipes (p. 4-5).
- 70% das falhas de qualidade surgem na fase de desenvolvimento, seguidas por manutenção (50%) e integração (40%) (p. 6).
- As práticas mais comuns de garantia de qualidade são testes unitários, versionamento, testes de integração e feedbacks externos (p. 6-7).
- Poucas empresas utilizam padrões formais de qualidade como ISO; práticas são adaptadas ao contexto (p. 7).

### 3. Fichamento de Citações
- "AI-enabled systems are also software systems and therefore rely on software quality assurance."
- "We identified 12 issues in the development of AI/ML components."
- "Unit tests were the most frequently mentioned practice for quality issues detection in AI/ML code."
- "SQA for AI significantly differs from SQA for traditional SE."
- "There is a very limited number of training or guidelines... for AI code."

---

**Referência:**  
Lopuha, O. et al. "Test Design Methodology for Software Verification." 2023 IEEE Smart Information Systems and Technologies (SIST), Astana, Kazakhstan. doi: 10.1109/SIST58284.2023.10223573

### 1. Fichamento de Conteúdo
Este artigo apresenta uma metodologia de projeto de testes voltada à verificação de software, enfatizando a importância de processos estruturados e avaliação de riscos para a eficácia da testagem. Os autores propõem um modelo básico de processo de teste composto por 10 etapas, incluindo análise de artefatos, definição de objetivos e cenários de testes, execução e avaliação. Destacam-se o uso de prototipagem iterativa, análise de risco de falha e uma abordagem orientada a processos com base no modelo de maturidade de testes. A proposta visa otimizar custo, tempo e confiabilidade, permitindo um teste mais eficiente e eficaz de sistemas modulares.

### 2. Fichamento Bibliográfico
- Ênfase em abordagem orientada a processos e avaliação de risco de falhas (p. 3-4).
- Testes divididos em black-box e white-box (p. 5).
- Eficiência do teste medida pela fórmula: Defeitos resolvidos / Defeitos totais × 100 (p. 5).
- Utiliza modelo de maturidade de testes em 5 níveis para avaliação de processos (p. 7).
- Processo de teste inclui 10 passos: planejamento, execução, avaliação, documentação e melhoria (p. 6).

### 3. Fichamento de Citações
- "Testing is an integral part of the software development lifecycle and helps identify potential problems early."
- "Testing Efficiency = Resolved Defects / Total Defects × 100."
- "A risk-oriented approach is proposed... considering component failure and system profile."
- "The testing process consists of 10 steps and includes preparation, execution and evaluation of test results."
- "The maturity model... involves interviewing the project's leading experts and summarizing the results."

---

**Referência:**  
Tufano, R.; Pascarella, L.; Tufano, M.; Poshyvanyk, D.; Bavota, G. "Towards Automating Code Review Activities." ICSE 2021. doi: 10.1109/ICSE43902.2021.00027

### 1. Fichamento de Conteúdo
O artigo propõe o uso de redes neurais profundas (transformers) para automatizar parcialmente o processo de revisão de código. Foram desenvolvidos dois modelos: um voltado para o desenvolvedor (contribuidor), sugerindo alterações antes da submissão do código; e outro para o revisor, que gera automaticamente o código modificado a partir de comentários em linguagem natural. Os modelos foram treinados com 17.194 exemplos de revisões de código reais e obtiveram sucesso em 16% dos casos no primeiro cenário e até 31% no segundo. O estudo mostra que, embora os modelos ainda sejam limitados, eles têm potencial para apoiar o processo de revisão de código, poupando tempo e esforço dos desenvolvedores.

### 2. Fichamento Bibliográfico
- Arquitetura: transformer encoder-decoder (p. 2).
- Cenários: geração de código sem e com input em linguagem natural (p. 3).
- Base de dados: 17.194 exemplos (p. 3).
- Avaliação qualitativa e quantitativa dos resultados (p. 4-5).
- Acurácia entre 3% a 31% dependendo do cenário (p. 5).

### 3. Fichamento de Citações
- "The goal is not to replace developers... but to work with them in tandem."
- "We train a transformer model to translate the code submitted for review."
- "These preliminary results can pave the way to novel research in the area of automating code review."
- "The model has been trained with 17,194 triplets."

---


**Referência:**  
Trübenbach, D.; Müller, S.; Grunske, L. "A Comparative Evaluation on the Quality of Manual and Automatic Test Case Generation Techniques for Scientific Software." SBST'22, May 2022. doi: 10.1145/3526072.3527523

### 1. Fichamento de Conteúdo
Este artigo compara a eficácia entre testes criados manualmente e testes gerados automaticamente para o projeto científico ASE em Python. A ferramenta Pynguin foi usada com algoritmos como DynaMOSA, MIO e Whole Suite. A avaliação utilizou métricas de cobertura de branches e mutações. Os resultados mostram que os testes manuais superam significativamente os automáticos, em especial pela dificuldade em lidar com entradas complexas e a estrutura dos dados científicos. O estudo conclui que é necessária a evolução das ferramentas de geração automática para alcançar níveis aceitáveis de cobertura e eficácia em sistemas científicos.

### 2. Fichamento Bibliográfico
- Projeto analisado: ASE (Atomic Simulation Environment) (p. 2).
- Ferramentas e algoritmos: Pynguin com MIO, DynaMOSA, Whole Test Suite (p. 3).
- Métricas: branch coverage, mutation coverage (p. 3-4).
- Nenhum algoritmo automático superou os testes manuais (p. 5).
- Dificuldade com entradas complexas e estruturadas (p. 6).

### 3. Fichamento de Citações
- "None of the automated test case generation algorithms manage to come close to the coverages reached by the manually created test suite."
- "Testing techniques need to be integrated into the development workflows."
- "System states that are difficult to reach... appear to be a general problem."

---


**Referência:**  
Romano, S.; Zampetti, F.; Baldassarre, M.T.; Di Penta, M.; Scanniello, G. "Do Static Analysis Tools Affect Software Quality when Using Test-driven Development?" ESEM 2022. doi: 10.1145/3544902.3546233

### 1. Fichamento de Conteúdo
O artigo analisa se ferramentas de análise estática (SATs), como o SonarLint, afetam a qualidade do software ao utilizar TDD. Foram realizados dois experimentos com 92 estudantes utilizando TDD com e sem a ferramenta. Os resultados mostram que o uso do SAT melhora métricas como número de code smells, débito técnico e complexidade, mas também aumenta a dificuldade percebida do TDD. O estudo recomenda combinar ensino de TDD com SATs e incentiva o desenvolvimento de ferramentas melhores para esse cenário.

### 2. Fichamento Bibliográfico
- TDD: ciclos Red, Green, Refactor (p. 1).
- SAT avaliado: SonarLint, integrado ao Eclipse (p. 2).
- Métricas analisadas: code smells, débito técnico, complexidade (p. 4).
- Experimentos com 92 participantes (p. 2-3).
- SAT melhora qualidade, mas aumenta dificuldade percebida (p. 5).

### 3. Fichamento de Citações
- "The use of a SAT helped participants to significantly improve software quality."
- "TDD is perceived as more difficult when using a SAT."
- "We foster researchers to define a new generation of SATs."
