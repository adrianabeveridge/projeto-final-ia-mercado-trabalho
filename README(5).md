# A Importância da IA em Nossas Vidas e no Trabalho

### Uma Análise Exploratória do Impacto da Inteligência Artificial no Mercado de Trabalho Global (2020–2026)

**Projeto S14 Final — Análise de Dados**
**Autora:** Adriana Beveridge · adriana.beveridge@gmail.com

---

## 📋 Sobre o Projeto

A Inteligência Artificial deixou de ser promessa futurista e passou a fazer parte do dia a dia profissional. Mas o impacto real varia muito — dependendo da profissão, do setor e do país. Este projeto usa dados reais(ish) para investigar, com evidências, como essa transformação está acontecendo.

## ❓ Perguntas de Pesquisa

1. Quais profissões e indústrias correm mais risco de substituição pela IA?
2. A adoção de IA está relacionada com aumento ou queda de salário?
3. Como o risco de automação evoluiu de 2020 a 2026?
4. Existe diferença entre países no nível de adoção de IA e no impacto salarial?
5. Quais profissões têm maior urgência de requalificação (reskilling)?

Como bônus, o projeto também constrói um **Índice de Vulnerabilidade à IA (IVIA)** — uma métrica própria criada a partir da combinação ponderada de risco de automação, urgência de requalificação e intensidade de disrupção.

## 🔑 Principais Achados

- 🚚 **Motorista de Caminhão (60,7%)** e **Atendimento ao Cliente (59,9%)** têm o maior risco de automação; **Engenheiro de Software (34,9%)** e **Analista de Dados (35,5%)** têm o menor.
- 💰 A correlação entre adoção de IA e variação salarial é **praticamente nula (r ≈ 0,000)** — adotar mais IA não significou ganhar mais nem menos, neste dataset.
- 📈 O risco de automação ficou **estável no geral (2020–2026)**, mas com trajetórias opostas por setor: Tecnologia caiu (-2,5 p.p.), Retail e Energy subiram (+3,0 e +2,0 p.p.).
- 🌎 O **Brasil está na média do grupo de países**, tanto em adoção de IA quanto em variação salarial (-0,06%, estável).
- 🎯 O **Índice de Vulnerabilidade à IA** confirma: Motorista de Caminhão (100/100) é a profissão mais vulnerável; Engenheiro de Software (0,3/100) é a mais segura.

## 📊 Dataset

[**Future of Work in the Age of AI (2020–2026)**](https://www.kaggle.com/datasets/algozee/future-of-work-in-the-age-of-ai-20202026) — Kaggle

Dataset sintético com 15.000 registros, cobrindo 8 indústrias, 9 países e 10 profissões, com métricas de risco de automação, adoção de IA, variação salarial, urgência de requalificação e intensidade de disrupção.

## 🗂️ Estrutura do Repositório

```
├── Projeto_Final_Impacto_IA_Trabalho.ipynb   # Notebook com toda a análise (Python)
├── ai_job_replacement_2020_2026_v2.csv       # Dataset utilizado
├── Projeto_Final_Apresentacao.pdf            # Apresentação em slides
└── README.md                                 # Este arquivo
```

## 🛠️ Ferramentas Utilizadas

- **Python** — pandas, numpy, scikit-learn
- **Visualização** — matplotlib, seaborn, plotly
- **Jupyter Notebook**

## 🚀 Como Rodar o Notebook

1. Clone este repositório ou baixe os arquivos
2. Certifique-se de que o arquivo `ai_job_replacement_2020_2026_v2.csv` está na mesma pasta do notebook
3. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
   ```
4. Abra o notebook no Jupyter e rode todas as células (`Kernel → Restart & Run All`)

## 📌 Limitações

- O dataset é sintético (gerado para fins educacionais); os valores absolutos não representam estatísticas oficiais de mercado.
- A análise é correlacional, não causal.
- O Índice de Vulnerabilidade à IA é uma construção autoral deste projeto, com pesos definidos por julgamento razoável.

---

*Projeto desenvolvido como parte do Nanodegree de Analista de Dados.*
