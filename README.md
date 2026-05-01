# 📊 Análise do Desmatamento na Amazônia Legal

Projeto de análise de dados utilizando Python para explorar o desmatamento na Amazônia Legal ao longo do tempo.

---
## 🌐 Visualização Interativa

Acesse o gráfico:

👉 https://joaopedro-001.github.io/Analise-do-Desmatamento-na-Amazonia-Legal/

---
## 🔍 Funcionalidades

* Análise temporal do desmatamento
* Ranking de estados com maior desmatamento
* Visualização interativa com Plotly

---

## 🛠️ Tecnologias

* Python
* Pandas
* Plotly

---

## ▶️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/analise-desmatamento-amazonia.git
cd analise-desmatamento-amazonia
```

### 2. Instalar as dependências

```bash
pip install pandas plotly
```

### 3. Estrutura esperada

```bash
analise-desmatamento-amazonia/
│
├── dados/
│   └── Desmatamento.csv
│
├── src/
│   ├── analise_temporal_desmatamento.py
│   ├── analise_por_estado.py
│   ├── visualizacao_top5_estados.py
│
└── README.md
```

### 4. Executar os scripts

#### 📊 Análise temporal

```bash
python src/analise_temporal_desmatamento.py
```

#### 🌍 Análise por estado

```bash
python src/analise_por_estado.py
```

#### 📈 Visualização interativa (recomendado)

```bash
python src/visualizacao_top5_estados.py
```

---

### 5. Visualizar o gráfico

* O gráfico interativo abrirá automaticamente no navegador
* Você pode:

  * passar o mouse para ver valores
  * clicar na legenda para esconder estados
  * usar zoom para explorar os dados

---

## 📌 Observações

* Os dados utilizados são públicos e podem ser obtidos via INPE (PRODES)

---

## 🎯 Objetivo do projeto

Explorar a evolução do desmatamento na Amazônia Legal e identificar padrões ao longo do tempo e entre estados.
