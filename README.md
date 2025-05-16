
# 📊 Análise de Vendas - Quatro Lojas

Este projeto tem como objetivo realizar uma análise exploratória de dados de vendas de quatro lojas distintas. Utilizando bibliotecas como **Pandas**, **Matplotlib** e **Folium**, extraímos insights importantes sobre faturamento, categorias de produtos, avaliações, fretes e distribuição geográfica.

## 🧰 Tecnologias Utilizadas

- Python 3.11
- pandas
- matplotlib
- folium
- Jupyter Notebook

## 📁 Estrutura do Projeto

```
├── analise_vendas.ipynb
├── README.md
├── dados/
│   ├── loja1.csv
│   ├── loja2.csv
│   ├── loja3.csv
│   └── loja4.csv
└── imagens/
    ├── faturamento_lojas.png
    └── mapa_vendas.html
```

## 📌 Objetivos da Análise

1. **Faturamento Total por Loja**
2. **Quantidade de Produtos Vendidos**
3. **Média de Avaliação por Loja**
4. **Análise por Categoria de Produto**
5. **Produtos Mais e Menos Vendidos**
6. **Frete Médio por Loja**

## 🔍 Principais Insights

- A **Loja 1** apresentou o maior faturamento.
- A **categoria "informática"** teve destaque em todas as lojas.
- A **Loja 3** obteve a melhor avaliação média dos clientes.
- O **produto 577** foi o mais vendido no geral.
- Os fretes variam significativamente entre as lojas, afetando o custo final.
- As vendas possuem padrão sazonal mensal, conforme o gráfico de linha por mês.
- A visualização com **Folium** evidenciou concentração de vendas em regiões específicas do Brasil.

## 🤔 Como Executar o Projeto

### 🧪 No Google Colab

1. Acesse o repositório no GitHub: [https://github.com/GabrielMS-cmd/Desafio_AluraStore](https://github.com/GabrielMS-cmd/Desafio_AluraStore)
2. Abra o arquivo `analise_vendas.ipynb`.
3. Clique em **"Abrir no Google Colab"** ou acesse diretamente: [https://colab.research.google.com/github/GabrielMS-cmd/Desafio_AluraStore/blob/main/analise_vendas.ipynb](https://colab.research.google.com/github/GabrielMS-cmd/Desafio_AluraStore/blob/main/analise_vendas.ipynb)
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
   jupyter notebook analise_vendas.ipynb
   ```

## 💡 Recomendação Final

Com base na análise dos dados de vendas, avaliações, faturamento, frete e distribuição geográfica das quatro lojas, a recomendação é que:

**O Senhor João deve vender a Loja 4.**

**Justificativa:**

1. Apresenta o menor faturamento total.
2. É a loja com menor número de produtos vendidos.
3. Possui a pior média de avaliação dos clientes.
4. Tem o frete médio mais alto, o que pode afetar negativamente as vendas.
5. Exibe a menor densidade geográfica de clientes, limitando o alcance do negócio.

Dessa forma, manter as outras lojas pode ser mais estratégico para o crescimento e lucratividade do negócio.

## 📌 Caminho dos Arquivos

- **Notebook de Análise:** `analise_vendas.ipynb`
- **Dados das Lojas:**
  - Loja 1: `dados/loja1.csv`
  - Loja 2: `dados/loja2.csv`
  - Loja 3: `dados/loja3.csv`
  - Loja 4: `dados/loja4.csv`
- **Imagens Geradas:**
  - Gráfico de Faturamento: `imagens/faturamento_lojas.png`
  - Mapa de Densidade de Vendas: `imagens/mapa_vendas.html`

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
