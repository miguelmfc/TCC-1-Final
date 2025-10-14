**Referência:**  
Romano, S.; Zampetti, F.; Baldassarre, M.T.; Di Penta, M.; Scanniello, G. *"Do Static Analysis Tools Affect Software Quality when Using Test-driven Development?"* ESEM 2022. doi: 10.1145/3544902.3546233

### 1. Fichamento de Conteúdo
O artigo investiga se ferramentas de análise estática (*static analysis tools*, SATs), como o *SonarLint*, afetam a qualidade do software ao utilizar *test-driven development* (TDD). Foram conduzidos **dois experimentos com 92 estudantes**, comparando a utilização de TDD com e sem a ferramenta.  

Principais achados:

- O uso de SATs melhora métricas de qualidade, incluindo **número de *code smells***, **débito técnico** e **complexidade do código**.  
- O uso de SATs aumenta a **dificuldade percebida do TDD** pelos participantes.  
- Recomenda-se combinar o ensino de TDD com SATs e incentivar o desenvolvimento de **novas ferramentas de análise estática** adaptadas a TDD.

### 2. Conceitos e Definições
- *Test-driven development (TDD)*: Técnica de desenvolvimento baseada em ciclos *Red, Green, Refactor*, onde testes são escritos antes do código de implementação.  
- *Static analysis tools (SATs)*: Ferramentas que analisam código-fonte sem executá-lo, identificando problemas como *code smells*, vulnerabilidades ou débito técnico.  
- *Code smells*: Padrões no código que indicam possíveis problemas de manutenção ou qualidade.  
- *Technical debt (débito técnico)*: Acúmulo de decisões de implementação que podem prejudicar manutenção e evolução futura do software.  
- *Complexity*: Medida de quão complicado o código é, geralmente baseada em métricas como *cyclomatic complexity* ou profundidade de aninhamento.  

### 3. Fichamento de Citações
- "*The use of a SAT helped participants to significantly improve software quality.*"  
- "*TDD is perceived as more difficult when using a SAT.*"  
- "*We foster researchers to define a new generation of SATs.*"
