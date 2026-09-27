# Contexto e objetivos

Repositório criado com a finalidade de testar funcionalidades do notebooklm PRO com materiais de estudo de Data Engineering (DE). Os conteúdos envolvem fundamentos da área.

# Fontes de dados

https://www.youtube.com/watch?v=1nVGaNbvuXg
https://www.youtube.com/watch?v=b2QkhmQ0sT0
https://www.youtube.com/watch?v=hf2go3E2m8g
https://www.youtube.com/watch?v=qWru-b6m030

# Modelos de perguntas

Qual o melhor modo de estudar engenharia de dados utilizando IA?
Como funciona o ciclo de vida completo da engenharia de dados?

# Miniguia de estudos



## Prompt de revisão:

Com base nas estratégias de aprendizado discutidas nas fontes, a melhor maneira de revisar termos técnicos é utilizar a IA como um **"Agente de Revisão Adversária"**. Em vez de apenas pedir definições, o prompt deve desafiar você a explicar os conceitos, garantindo que você compreenda a lógica ("trunk") e não apenas decore a sintaxe.

Aqui está um modelo de prompt estruturado para sua revisão:

---

### Prompt de Revisão de Engenharia de Dados

**"Atue como um Engenheiro de Dados Sênior e meu mentor de estudos. Eu quero revisar os fundamentos técnicos do ciclo de vida de dados para garantir que domino os conceitos 'tronco' (essenciais).**

**Siga estas instruções:**
1. **Escolha um termo ou conceito da lista abaixo e me peça para explicá-lo com minhas próprias palavras, focando no 'porquê' e nos 'trade-offs' envolvidos.**
2. **Após minha resposta, atue como um 'Revisor Adversário': critique minha explicação, aponte lacunas de segurança ou performance e corrija qualquer erro conceitual.**
3. **Se eu acertar, me desafie com um cenário prático (ex: 'Como você aplicaria isso em um sistema de e-commerce?').**
4. **Siga o ciclo: Pergunta -> Minha Resposta -> Sua Crítica -> Próximo Termo.**

**Lista de Termos para Revisão:**
*   **Ciclo de Vida:** Ingestão (Batch vs Streaming), Transformação (ETL vs ELT) e Serving.
*   **Sistemas:** OLTP vs OLAP (Row-based vs Column-based).
*   **Modelagem:** Tabela Fato vs Dimensão, Star Schema vs Snowflake Schema.
*   **SCD:** Slowly Changing Dimensions (Tipos 1, 2, 3 e 6).
*   **Armazenamento:** Data Lake vs Data Warehouse vs Data Lakehouse.
*   **Undercurrents:** Orquestração, Data Governance, Observabilidade e Segurança.
*   **Big Data:** Pub/Sub (Kafka), Processamento Distribuído (Spark) e Teorema CAP."

---

### Dicas para potencializar sua revisão:

*   **Regra 80/20:** Use este prompt para focar nos 20% de teoria que sustentam 80% da prática. Priorize entender a arquitetura e os fundamentos antes de se preocupar com ferramentas específicas.
*   **Foco no "Trunk" (Tronco):** Ao responder ao prompt, foque em conceitos como infraestrutura de rede, lógica de processamento e segurança. Esses são os componentes que, se falharem, têm um grande "raio de explosão" no sistema.
*   **Evite a decoreba:** Se você não souber um termo, peça para a IA explicá-lo usando uma analogia (como a do "encanador" para o engenheiro de dados) antes de tentar explicá-lo novamente.
*   **Evidência de Execução:** Para termos complexos (como transformações no Spark), peça para a IA mostrar um exemplo de como o dado entra "sujo" (raw) e sai "limpo" (transformed) após a aplicação da lógica de negócio.
