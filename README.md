# Análise de Salários - Data Science

![Python](https://img.shields.io/badge/Python-3.11-333333?style=flat&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.42-333333?style=flat&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.18-333333?style=flat&logo=plotly&logoColor=white)

## Visão Geral
Dashboard analítico desenvolvido para exploração de dados salariais no mercado global de Data Science. A aplicação processa dados brutos e fornece visualizações interativas para identificar tendências de remuneração baseadas em senioridade, localização geográfica e modelos de trabalho.

## Stack Tecnológico
* **Linguagem:** Python 3.11+
* **Framework Web:** Streamlit
* **Processamento de Dados:** Pandas
* **Visualização:** Plotly Express

## Funcionalidades
* **Filtragem Dinâmica:** Segmentação de dados por ano, nível de senioridade, tipo de contrato e porte da empresa.
* **KPIs:** Monitoramento de métricas essenciais (Média Salarial, Teto Salarial, Volumetria).
* **Análise Geográfica:** Mapa coroplético indicando densidade salarial por país (ISO3).
* **Análise Comparativa:** Gráficos de distribuição de cargos e modelos de trabalho (Remoto/Híbrido/Presencial).

## Instalação e Execução

Pré-requisitos: Python 3.10 ou superior.

### 1. Clonar o repositório
```bash
git clone [https://github.com/Davi-Silva-Developer/Dashboard-Mercado-Dados.git](https://github.com/Davi-Silva-Developer/Dashboard-Mercado-Dados.git)
cd Dashboard-Mercado-Dados
2. Configurar o ambiente virtual
Bash
# Criação do ambiente
python -m venv .venv

# Ativação (Windows)
.\.venv\Scripts\activate

# Ativação (Linux/Mac)
source .venv/bin/activate
3. Instalar dependências
Bash
pip install -r requirements.txt
4. Executar a aplicação
Bash
python -m streamlit run app.py
Estrutura do Projeto
app.py: Script principal da aplicação.

requirements.txt: Lista de bibliotecas e versões.

.venv/: Ambiente virtual isolado.

www.linkedin.com/in/davi-silva-dev/ | github.com/Davi-Silva-Developer/
