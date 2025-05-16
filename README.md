
# 📊 Challenge - Alura Store

O desafio proposto consiste basicamente em ajudar o Senhor João a decidir qual loja da sua rede Alura Store vender para iniciar um novo empreendimento. Para isso, utilizei dados de vendas, desempenho e avaliações das 4 lojas fictícias da Alura Store. O objetivo é identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados.

Utilizando bibliotecas como **Pandas**, **Matplotlib** e **Folium**, extrai insights importantes sobre faturamento, categorias de produtos, avaliações, fretes e distribuição geográfica.

## 🧰 Tecnologias Utilizadas

- Python 3.11
- pandas
- matplotlib
- folium
- Jupyter Notebook


## 📌 Objetivos da Análise

1. **Faturamento Total por Loja**
2. **Quantidade de Produtos Vendidos**
3. **Média de Avaliação por Loja**
4. **Análise por Categoria de Produto**
5. **Produtos Mais e Menos Vendidos**
6. **Frete Médio por Loja**

## 🔍 Principais Insights

📊 1. Faturamento
- Loja 1 teve o maior faturamento (R$ 1.534.509).
- Loja 4 teve o menor faturamento (R$ 1.384.497).

💸 2. Ticket médio
- Loja 1 também teve o maior ticket médio (~R$ 499,74).
- Loja 4 apresentou o menor ticket médio (~R$ 454,75), sinalizando menor valor médio por venda.

⭐ 3. Avaliação dos clientes
- Loja 3 teve a melhor avaliação média (4.05).
- Loja 1 teve a pior avaliação média (3.98), apesar do bom faturamento.

📦 4. Vendas por categoria
- Loja 3 se destacou em 3 categorias diferentes, mostrando boa diversidade e equilíbrio.
- Loja 1 liderou em 2 categorias, com volume alto em móveis e eletrônicos.
- Loja 4 teve desempenho mediano em todas as categorias, sem se destacar em nenhuma.

🚚 5. Frete médio
- Loja 4 teve o frete mais barato (R$ 31,28).
Porém, isso não resultou em maior faturamento ou avaliação, sugerindo que o frete baixo não compensou a performance geral.

🛒 6. Produtos mais e menos vendidos
- Loja 2 teve o produto mais vendido com 65 unidades (“Iniciando em programação”).
- Loja 4 teve um produto com apenas 33 unidades vendidas no pior desempenho (“Guitarra”).


## 🤔 Como Executar o Projeto

### 🧪 No Google Colab

1. Acesse o repositório no GitHub: [https://github.com/GabrielMS-cmd/Desafio_AluraStore](https://github.com/GabrielMS-cmd/Desafio_AluraStore)
2. Abra o arquivo `Desafio_LojasAlura_byGabriel.ipynb`.
3. Clique em **"Abrir no Google Colab"** ou acesse diretamente: [https://colab.research.google.com/github/GabrielMS-cmd/Desafio_AluraStore/blob/main/Desafio_LojasAlura_byGabriel.ipynb](https://colab.research.google.com/github/GabrielMS-cmd/Desafio_AluraStore/blob/main/Desafio_LojasAlura_byGabriel.ipynb)
4. Execute as células do notebook clicando no ícone de play ao lado de cada célula ou pressionando `Shift + Enter`.

### 💻 Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/GabrielMS-cmd/Desafio_AluraStore.git
   cd Desafio_AluraStore
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook:
   ```bash
   jupyter notebook Desafio_LojasAlura_byGabriel.ipynb
   ```

## 💡 Recomendação Final

Com base na análise dos dados de vendas, avaliações, faturamento, frete e distribuição geográfica das quatro lojas, a recomendação é que:

**O Senhor João deve vender a Loja 4.**

**Justificativa:**

1. Pior faturamento.
2. Pior ticket médio. **(faturamento / quantidade de vendas)**
3. Nenhum destaque em avaliação.
4. Só lidera em frete, mas isso não compensa os baixos resultados financeiros.
5. Vendas totais menores que Loja 2 e 1.
6. Empate ou abaixo em quase todos os critérios.



Dessa forma, manter as outras lojas pode ser mais estratégico para o crescimento e lucratividade do negócio.

## 📌 Caminho dos Arquivos

- **Notebook de Análise:** `Desafio_LojasAlura_byGabriel`
- **Dados das Lojas:**
  - Loja 1: `dados/loja1.csv`
  - Loja 2: `dados/loja2.csv`
  - Loja 3: `dados/loja3.csv`
  - Loja 4: `dados/loja4.csv`
- **Imagens Geradas:**
  - Gráfico de Faturamento: Faturamento - Total.png
  - Gráfico de Vendas por Categoria: Vendas - Categoria.png
  - Gráfico de Vendas ao longo dos Meses : Vendas - Meses.png
  - Gráfico de Ticket Médio por Loja - Ticket - Loja.png
  - Gráfico de Vendas por Produto: Vendas - Produtos.png
  - Gráfico de Densidade de Vendas por Região: Vendas - Região.jpg

