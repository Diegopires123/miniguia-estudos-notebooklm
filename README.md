
# 📚 Miniguia de Estudos: Nutrição Avançada e Suplementação Eficiente com NotebookLM

## 🎯 Contexto e Objetivos

Este repositório foi desenvolvido como parte de um desafio prático na plataforma DIO, com o objetivo de explorar o uso da Inteligência Artificial (IA) como ferramenta de aprendizagem ativa. 

O assunto escolhido para este caderno temático foi a **Nutrição, Cálculo de Macronutrientes e Suplementação Alimentar (foco em Whey Protein e Albumina)**. O objetivo principal é consolidar um material de consulta rápida para otimização de dietas voltadas à hipertrofia e performance, utilizando o Google NotebookLM como assistente de estudo para garantir respostas baseadas 100 em evidências científicas fornecidas.

---

## 🔍 Curadoria de Fontes

Para alimentar o NotebookLM e garantir a precisão técnica das respostas, foram selecionadas as seguintes fontes abertas e artigos de referência:

1. **Diretrizes da Sociedade Brasileira de Medicina do Esporte (SBME)** - Nutrição e suplementação no esporte.
2. **ISSN Exercise & Sports Nutrition Review Update** - Revisão da Sociedade Internacional de Nutrição Esportiva sobre a eficácia de suplementos (Whey Protein e Albumina).
3. **Tabela TACO (Tabela Brasileira de Composição de Alimentos)** - Utilizada como base para os dados de composição de alimentos e pesagens.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Documentação dos testes de prompts realizados no NotebookLM para extrair o melhor conhecimento das fontes anexadas, incluindo as dificuldades encontradas e como foram superadas.

### Teste 1: Prompt de Instrução Direta (Abordagem Simples)
*   **Prompt enviado:** *"Me diga a diferença entre Whey Protein e Albumina."*
*   **Resultado:** O modelo trouxe uma resposta correta, porém muito genérica e em formato de texto corrido, o que dificultava a comparação rápida.
*   **Ajuste (Cicatriz):** Percebi que precisava de uma estrutura visual melhor para comparar velocidade de absorção e custo-benefício.

### Teste 2: Prompt Few-Shot + Role Play (Abordagem Avançada)
*   **Prompt enviado:** 
    > "Atue como um nutricionista esportivo focado em clareza didática. Com base nas fontes, compare a Albumina e o Whey Protein. Use o formato do exemplo abaixo para estruturar sua resposta:
    >
    > **Exemplo de Estrutura:**
    > *   **Suplemento X:** [Origem] | [Velocidade de absorção] | [Melhor horário de consumo].
    > 
    > Faça isso para ambos os suplementos e adicione uma conclusão sobre qual escolher dependendo do orçamento."
*   **Resultado:** O NotebookLM seguiu o padrão perfeitamente, gerando uma tabela comparativa mental limpa e direta, destacando o Whey (absorção rápida/pós-treino) e a Albumina (absorção lenta/antes de dormir, excelente custo-benefício).

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados

*   **Divisão de Macronutrientes:** A base de uma evolução consistente depende do alinhamento entre proteínas, carboidratos e gorduras. Para indivíduos ativos, o consumo proteico ideal costuma girar entre 1.6g a 2.2g por quilo de peso corporal.
*   **Pesagem e Precisão:** A consistência nos resultados de uma dieta está diretamente ligada à precisão. Pequenas variações no peso dos alimentos (como estimar "no olho" uma porção de frango ou macarrão) podem quebrar o déficit ou superávit calórico planejado.
*   **Suplementação Estratégica:** Whey Protein e Albumina são excelentes fontes de proteínas de alto valor biológico. Enquanto o Whey possui rápida digestibilidade, a Albumina (derivada da clara do ovo) é uma proteína de digestão lenta, ideal para períodos de jejum prolongado.

### 📕 Glossário de Conceitos Chave

*   **Proteína de Alto Valor Biológico (AVB):** Alimentos ou suplementos que contêm todos os aminoácidos essenciais em proporções adequadas (ex: ovos, carnes, leite, whey).
*   **Macronutrientes:** Nutrientes que o corpo precisa em grandes quantidades para fornecer energia e construir tecidos (Carboidratos, Proteínas e Gorduras).
*   **Hipertrofia:** Processo de aumento do tamanho das células musculares, estimulado pelo treino de força e suportado pelo aporte correto de proteínas e calorias.
*   **Janela de Absorção:** Período otimizado onde o corpo absorve nutrientes de forma mais eficiente, potencializado após o estímulo do treino.

### 🔄 Prompts Reutilizáveis para Revisões Futuras

Guarde estes prompts para usar no NotebookLM sempre que precisar revisar ou atualizar sua dieta:

1.  **Prompt para Ajuste de Meta:** 
    > "Com base nos documentos anexados, calcule a distribuição ideal de macronutrientes em gramas para um indivíduo de [Inserir Peso] kg que busca o objetivo de [Hipertrofia/Definição], utilizando a proporção de Xg de proteína por kg."
2.  **Prompt para Substituição de Alimentos:** 
    > "Considando a tabela de composição de alimentos das fontes, se eu precisar substituir [Exemplo: 300g de frango grelhado], quais seriam as quantidades equivalentes em [Exemplo: Albumina ou Carne Moída] para manter o mesmo teor de proteínas?"

---
🎨 Desenvolvido por Diego Assi Pires durante o Desafio de Projeto na DIO.
