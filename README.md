# 🛒 Análise RFM de Clientes - E-commerce

Este projeto foi desenvolvido como parte de um desafio da DNC para calcular os indicadores de Recência, Frequência e Ticket Médio (RFM) de clientes de um e-commerce. O objetivo é fornecer insights valiosos sobre o comportamento dos clientes.

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------|-----------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | Linguagem de programação utilizada para análise de dados e automação. |
| ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) | Biblioteca para manipulação e análise de dados em Python. |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) | Biblioteca para computação numérica, especialmente com arrays multidimensionais. |
| ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white) | Biblioteca para criação de gráficos interativos e visualizações de dados. |
| ![Dash](https://img.shields.io/badge/Dash-008DE4?style=for-the-badge&logo=dash&logoColor=white) | Framework para criar painéis interativos e aplicações web com Python. |

---

## 📊 Métricas RFM

As métricas RFM são calculadas da seguinte forma:

- **R (Recência)**: Tempo desde a última compra (em dias).
- **F (Frequência)**: Número de compras realizadas.
- **M (Ticket Médio)**: Valor médio gasto por compra.

---

## 📂 Estrutura do Projeto

```
projeto-rfm/
├── dados_ecommerce.csv       # Base de dados original
├── rfm_resultados.csv        # Resultados RFM
├── app.py                    # Aplicação Dash interativa
├── README.md                 # Documentação do projeto
└── requirements.txt          # Dependências do projeto
```

---

## 📈 Gráficos e Visualizações

### Distribuição de Recência (R)
![Recência](https://via.placeholder.com/600x400.png?text=Gráfico+de+Recência)

### Distribuição de Frequência (F)
![Frequência](https://via.placeholder.com/600x400.png?text=Gráfico+de+Frequência)

### Distribuição de Ticket Médio (M)
![Ticket Médio](https://via.placeholder.com/600x400.png?text=Gráfico+de+Ticket+Médio)

---

## 📋 Tabela RFM (Exemplo)

| CustomerID | R (Recência) | F (Frequência) | M (Ticket Médio) |
|------------|--------------|----------------|------------------|
| 12347      | 1            | 7              | 4310.00          |
| 12348      | 74           | 4              | 1797.24          |
| 12349      | 18           | 1              | 1757.55          |
| 12350      | 309          | 1              | 334.40           |
| 12352      | 35           | 8              | 2506.04          |

---
