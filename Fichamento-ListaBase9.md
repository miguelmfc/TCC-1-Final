**Referência:**  
Trübenbach, D.; Müller, S.; Grunske, L. *"A Comparative Evaluation on the Quality of Manual and Automatic Test Case Generation Techniques for Scientific Software."* SBST'22, May 2022. doi: 10.1145/3526072.3527523

### 1. Fichamento de Conteúdo
O artigo compara a eficácia entre testes criados manualmente e testes gerados automaticamente para o projeto científico *ASE* (*Atomic Simulation Environment*) em Python. A ferramenta *Pynguin* foi utilizada com algoritmos como *DynaMOSA*, *MIO* e *Whole Suite*.  

A avaliação foi realizada utilizando métricas de **branch coverage** e **mutation coverage**. Os resultados mostram que os testes manuais superam significativamente os testes automáticos, especialmente devido à dificuldade dos algoritmos automáticos em lidar com entradas complexas e estruturas de dados científicas. O estudo conclui que é necessária a evolução das ferramentas de geração automática para atingir níveis aceitáveis de cobertura e eficácia em sistemas científicos.

### 2. Conceitos e Definições
- *Manual test cases*: Testes elaborados por desenvolvedores ou testadores humanos, com base em conhecimento do domínio e cenários de uso.  
- *Automated test case generation*: Processo de criação de testes utilizando algoritmos e ferramentas automáticas, sem intervenção humana direta.  
- *Pynguin*: Ferramenta de geração automática de testes para programas Python.  
- *DynaMOSA*: Algoritmo de otimização multiobjetivo usado para gerar casos de teste.  
- *MIO (Many Independent Objectives)*: Algoritmo de otimização para maximizar cobertura de teste.  
- *Whole Test Suite*: Estratégia de geração automática que visa maximizar a cobertura de todos os testes de uma suíte.  
- *Branch coverage*: Métrica que mede a porcentagem de ramificações de código (como *if/else*) executadas pelos testes.  
- *Mutation coverage*: Métrica que verifica se os testes conseguem detectar alterações (*mutations*) introduzidas artificialmente no código.

### 3. Fichamento de Citações
- "*None of the automated test case generation algorithms manage to come close to the coverages reached by the manually created test suite.*"  
- "*Testing techniques need to be integrated into the development workflows.*"  
- "*System states that are difficult to reach... appear to be a general problem.*"
