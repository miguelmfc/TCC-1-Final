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
