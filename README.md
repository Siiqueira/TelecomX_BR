# 📞 TelecomX_BR – Análise de Cancelamento de Clientes (Churn)

📊 Projeto de análise de churn (evasão de clientes) da **TelecomX_BR**, com foco em:
- Identificação dos motivos de cancelamento
- Análise de perfil dos clientes que cancelam
- Avaliação do impacto financeiro causado pelo churn
- Análise temporal e comportamental
- Geração de insights para retenção e melhoria de serviços

---

## 🎯 Desafio e Objetivo

A empresa **TelecomX_BR** sofre com **elevadas taxas de cancelamento** de clientes, o que impacta diretamente seu faturamento e previsibilidade de receita.

O objetivo deste projeto é **analisar os dados de clientes e cancelamentos** para:
- Identificar os principais fatores que levam ao churn
- Entender o perfil dos clientes que cancelam
- Estimar o prejuízo financeiro associado
- Gerar recomendações práticas para reduzir a evasão

---


## 🛠️ Tecnologias Utilizadas

- Google Colab
- Python
- Pandas as pd
- Numpy as np
- Matplotlib.pyplot as plt
- Seaborn as sns
- Plotly.express as px
- Warnings
  warnings.filterwarnings('ignore')

---

## 📁 Estrutura do Projeto

📦 TelecomX_BR/  
│  
├── 📊 data_base/  
│ └── Arquivo .json (API)  
| └── TelecomX_dicionario.md  
|  
│── 📈 Img/  
| └── Imagens e gráficos    
|  
├── 📓 TelecomX_BR.ipynb    
├── 📜 README.md  
|── .gitignore  
|── LICENSE  


---


- 📌 Distribuição do Churn (%)
- 📌 Correlação entre Permanência, Conta Diária e Cancelamento
- 📌 Churn por categoria (Idoso, Gênero, Parceiro, Dependente)
- 📌 Churn por tipo de contrato e método de pagamento
- 📌 Análise dos serviços com maior churn (Telefone, Internet, Serviços Online)
- 📌 Séries temporais do churn vs. tempo de permanência
- 📌 Distribuição dos gastos e seu impacto no churn

---

### 4. ✅ Conclusões e Insights

- A maior parte dos cancelamentos ocorre nos **primeiros 8 meses**, sendo **20% no 1º mês**
- **90,1%** dos clientes que cancelam utilizam **serviços telefônicos**
- **Contratos mensais** representam **88,6%** dos cancelamentos
- **Pagamento por boleto** (digital ou físico) representa **73,8%** dos churns
- A **Fibra Óptica** é o serviço de internet mais cancelado: **69,4%**
- Clientes com **múltiplas linhas telefônicas** + **serviços online** têm alta taxa de evasão

---

### 5. 💡 Sugestões e Recomendações

- **Melhorar o serviço telefônico** com foco em suporte técnico e atendimento
- **Criar incentivos de fidelização**:
  - Descontos para múltiplas linhas
  - Bônus temporários (ex: backup online, canais extra)
- **Atuar nos primeiros meses do cliente** com ações proativas de retenção
- **Incentivar pagamento por cartão ou débito automático** com descontos
- **Revisar a oferta de serviços de Fibra Óptica**, que apresenta alta evasão

---
> Gráficos e análises relevantes incluídos no notebook:

![Grafico](https://github.com/Siiqueira/TelecomX_BR/blob/main/Img/histograma.png)
---

## 📥 Como Executar

Clone o repositório:

```
git clone git@github.com:Siiqueira/TelecomX_BR.git
cd TelecomX_BR
```
Abra o Jupyter Notebook:  
```
jupyter notebook TelecomX_BR.ipynb
```
---

📄 Licença
MIT License – Livre para uso, estudo e modificação.

✉️ Contato  
Desenvolvido por Ellan Alves  
- ynvestellan@gmail.com
-  [LinkedIn](https://www.linkedin.com/in/ellan-alves-dados/)
