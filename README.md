
## 📌 Objetivo
Este projeto visa consolidar, limpar e analisar dados de vendas de veículos para extrair métricas financeiras relevantes, identificar padrões de mercado e fornecer recomendações estratégicas baseadas em dados.

## 📂 Fontes de Dados
- `projeto-monks.desempenhovendas.broken_database_1`
- `projeto-monks.desempenhovendas.broken_database_2`

**Período:** Dados históricos completos  
**Escopo:** Todas as marcas e modelos disponíveis

## 🛠 Estrutura do Projeto
📂 projeto-vendas-veiculos/  
│  
├── 📂 data/  
│   ├── 📂 raw/          # Dados brutos originais  
│   └── 📂 processed/    # Dados tratados  
│  
├── 📂 notebooks/        # Análises em Jupyter Notebook  
│   └── 📄 analise_vendas.ipynb  
│  
├── 📂 queries/          # Consultas SQL  
│   ├── 📄 consolidacao.sql  
│   └── 📄 analises.sql  
│  
├── 📄 README.md         # Documentação do projeto  
└── 📄 requirements.txt  # Dependências (se usar Python)

## 🔍 Principais Análises
1. **Marca com maior volume de vendas**
2. **Veículos com maior e menor receita**
3. **Distribuição por faixa de preço**
4. **Marcas com menor ticket médio**
5. **Top 5 veículos mais vendidos**

## 📊 Resultados Chave
- 58% das vendas concentradas no 1º semestre
- 72% do volume em veículos populares (até R$40k)
- 28% da receita proveniente de modelos premium

## 🚀 Como Executar
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/projeto-vendas-veiculos.git
