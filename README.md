# iFood Business Case — Data Analysis (Cupons / Retenção)

Este repositório contém:
- **Notebook principal** com validações, definição de métricas, análise do teste A/B, segmentação e viabilidade.
- **Relatório final (PDF)** com conclusões e recomendações para público de negócio tecnicamente leigo.

> **Contexto:** avaliar o impacto de uma campanha de cupons (grupo *target* vs *control*) usando dados de pedidos no período **dez/2018–jan/2019**, com foco em **retenção/recompra** e viabilidade financeira.

---

## Conteúdo do repositório

. <br/>
├─ notebooks/ <br/>
│ └─ iFood_Business_Case_Revisado.ipynb <br/>
├─ reports/ <br/>
│ └─ Relatorio_Final_iFood_Cupons_FINAL.pdf <br/>
└─ README.md


## **O notebook faz download automático dos dados do case**, então não é necessário subir datasets para o GitHub.

---

## Como executar (Google Colab — recomendado)

### 1) Abrir o notebook
1. Vá em `notebooks/`
2. Abra o `.ipynb` no Colab (File → Open notebook → GitHub / Upload)

### 2) Rodar o notebook
- Runtime → **Run all**
- Ou execute célula a célula, mantendo a ordem.

O notebook:
- baixa os dados automaticamente,
- faz checagens de integridade (incluindo cobertura A/B ↔ pedidos),
- calcula retenção (D7/D14/D30) com tratamento de censura,
- produz visualizações e tabelas executivas,
- e avalia viabilidade financeira em cenários.
