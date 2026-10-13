# Quantitative Methods for Multivariate Analysis

Atividades da disciplina **ACH2036 — Métodos Quantitativos para Análise Multivariada**, EACH-USP.

## 📓 Atividade 1 — Regressão linear

➡️ **[Abrir o notebook](First-Activity/Analysis.ipynb)**

Análise dos conjuntos **Treadwear**, **Alligators** e **ConcPatog**, realizada em Python com regressão linear simples por mínimos quadrados.

| Etapa | Conteúdo |
|---|---|
| **3.1** | Análise na escala original, ajuste da regressão, R² ajustado e intervalos de confiança e predição |
| **3.2** | Exploração de raiz quadrada, quadrado e logaritmo decimal em X, Y ou ambas |
| **3.3** | Análise dos modelos escolhidos e diagnóstico das premissas LINE pelos resíduos |

O notebook reúne **códigos, tabelas, gráficos e interpretações**, incluindo limitações dos modelos.

## 📂 Organização

```text
First-Activity/
├── Analysis.ipynb       # Resolução comentada
├── Datasets/           # Dados utilizados
├── Statement/          # Enunciado
└── requirements.txt    # Dependências
```

## ▶️ Executar

Com um ambiente Python ativado, execute na raiz do repositório:

```powershell
python -m pip install -r First-Activity/requirements.txt
cd First-Activity
jupyter lab Analysis.ipynb
```

No notebook, selecione o kernel do ambiente e execute todas as células em ordem.