# 📊 Desafio Cientista de Dados - Indicium

Projeto desenvolvido por **Vinícius Franklin Pedrosa Mansur de Azevedo** para o Desafio de Ciência de Dados da Indicium.  
Objetivo: Análise exploratória, engenharia de features e modelos para prever nota IMDb de filmes.

---

## 📂 Estrutura do repositório
- `data_eng.ipynb` — pré-processamento e engenharia de dados  
- `analise.ipynb` — EDA, modelagem e previsões (fluxo principal)  
- `data/` — CSVs usados pelo projeto (já incluídos no repositório)  
- `xgb_model.pkl` — modelo XGBoost salvo para reuso  
- `LH_CD_VINICIUS_FRANKLIN_PEDROSO_MANSUR_DE_AZEVEDO.pdf` — relatório final  
- `requirements.txt` — dependências do projeto  
- `README.md` — este arquivo

---

## 🚀 Execução (resumo rápido)
- Se preferir **Colab**: monte o Google Drive e rode os notebooks (veja seção Google Drive), e altere os caminhos.  
- Se preferir **local**: clone o repositório, crie um venv e instale `pip install -r requirements.txt`.  
- **Observação importante**: os CSVs já estão em `data/`; portanto **não é obrigatório** usar a API do TMDb para executar e reproduzir os resultados. A API é usada apenas se você quiser enriquecer/atualizar os dados.

---

## ☁️ Google Drive (Colab) — detalhes práticos
1. Abra o notebook no Colab.  
2. Monte o Drive:
```python
from google.colab import drive
drive.mount('/content/drive')
BASE_PATH = '/content/drive/MyDrive/indicium_desafio'  # ajuste conforme desejar

## Observação sobre uso de IA

Durante a elaboração deste projeto, utilizei ferramentas de Inteligência Artificial (IA), como o ChatGPT, **apenas para auxílio na escrita do relatório, organização do texto e pesquisas pontuais**.  

Todo o raciocínio analítico, pré-processamento dos dados, modelagem, código-fonte e conclusões foram desenvolvidos exclusivamente por mim. **Nenhuma parte do desafio foi resolvida utilizando IA**.
