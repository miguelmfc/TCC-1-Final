**Referência:**  
Tufano, R.; Pascarella, L.; Tufano, M.; Poshyvanyk, D.; Bavota, G. *"Towards Automating Code Review Activities."* ICSE 2021. doi: 10.1109/ICSE43902.2021.00027

### 1. Fichamento de Conteúdo
O artigo propõe o uso de redes neurais profundas (*deep neural networks*), especificamente *transformers*, para automatizar parcialmente o processo de revisão de código. Foram desenvolvidos dois modelos:

1. Modelo voltado para o desenvolvedor (*contributor*), que sugere alterações antes da submissão do código.  
2. Modelo voltado para o revisor, que gera automaticamente código modificado a partir de comentários em *natural language*.  

Os modelos foram treinados com **17.194 exemplos de revisões de código reais**. O primeiro modelo obteve sucesso em **16% dos casos**, enquanto o segundo atingiu até **31%**. Embora os modelos ainda tenham limitações, o estudo evidencia seu potencial para apoiar o processo de revisão de código.

### 2. Conceitos e Definições
- *Transformers*: Arquitetura de redes neurais profundas baseada em mecanismos de atenção, utilizada para tradução, geração e modificação de sequências.  
- *Code review*: Processo de inspeção de código-fonte com o objetivo de detectar erros, melhorar qualidade e compartilhar conhecimento.  
- *Contributor model*: Modelo que sugere alterações no código antes de sua submissão, apoiando o desenvolvedor.  
- *Reviewer model*: Modelo que gera modificações no código a partir de comentários em *natural language*, apoiando o revisor.  
- *Triplets dataset*: Base de dados composta por conjuntos de três elementos: código original, comentário de revisão e código modificado.

### 3. Fichamento de Citações
- "*The goal is not to replace developers... but to work with them in tandem.*"  
- "*We train a transformer model to translate the code submitted for review.*"  
- "*These preliminary results can pave the way to novel research in the area of automating code review.*"  
- "*The model has been trained with 17,194 triplets.*"
