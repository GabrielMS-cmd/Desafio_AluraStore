# Desafio_AluraStore

## Descrição
O Desafio Alura Store é um projeto de análise de dados desenvolvido para auxiliar o Senhor João, proprietário da rede fictícia Alura Store, a decidir qual das quatro lojas da rede deve ser vendida para financiar um novo empreendimento. A análise é baseada em dados de vendas, desempenho e avaliações de quatro lojas fictícias, com o objetivo de identificar a loja com menor eficiência e apresentar uma recomendação final fundamentada. O projeto utiliza Pandas para manipulação de dados, Matplotlib para visualizações e Folium para mapas de calor.

## Funcionalidades


Carregamento de dados: Importação de arquivos CSV hospedados em URLs públicas, contendo informações de vendas das lojas.

Análise de métricas:

Faturamento total por loja.

Vendas por categoria de produtos (ex.: móveis, eletrônicos, brinquedos).

Avaliação média dos clientes por loja

Produtos mais e menos vendidos por loja.

Frete médio por loja.

## Visualizações:




Mapa de calor com Folium para densidade de vendas por região.

Pelo menos três gráficos diferentes (ex.: barras, pizza, dispersão) gerados com Matplotlib para visualização de métricas como faturamento e categorias.

## Tecnologias Utilizadas

Python 3.8+

Pandas: Para manipulação e análise de dados

Matplotlib: Para criação de gráficos (barras, pizza, dispersão, etc.).

Folium: Para visualização de mapas de calor.

Jupyter Notebook: Ambiente para desenvolvimento e apresentação da análise.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:
Python 3.8 ou superior
Bibliotecas Python:
pandas
matplotlib
folium
jupyter


## Instalação

Siga os passos abaixo para configurar e executar o projeto localmente:

Clone o repositório:

git clone https://github.com/GabrielMS-cmd/Desafio_AluraStore.git

Acesse o diretório do projeto:

cd Desafio_AluraStore

Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate


Instale as dependências:

pip install pandas matplotlib folium jupyter



Inicie o Jupyter Notebook:

jupyter notebook


Abra o arquivo Desafio_LojasAlura_byGabriel.ipynb no Jupyter Notebook.

Como Usar

Os dados das lojas são carregados automaticamente de URLs públicas no notebook. Não é necessário baixar arquivos CSV manualmente.

Execute as células do notebook Desafio_LojasAlura_byGabriel.ipynb em sequência para:

Carregar os dados com Pandas.

Analisar métricas (faturamento, categorias, avaliações, produtos, frete).

Gerar visualizações, incluindo:



Mapa de calor com Folium (densidade de vendas por região).

Gráficos de barras



Para exibir o mapa de calor, marque o notebook como confiável no Jupyter (File -> Trust Notebook).
Para salvar gráficos como arquivos PNG, verifique as células com plt.savefig() ou consulte a seção "Visualizações".

Visualizações

O projeto inclui as seguintes visualizações:





Mapa de calor (Folium): Mostra a densidade de vendas por região, com base nas coordenadas (lat, lon) dos dados.



Gráficos com Matplotlib:





Gráfico de barras: Exemplo - Faturamento total por loja.



Gráfico de pizza: Exemplo - Distribuição de vendas por categoria.



Gráfico de dispersão: Exemplo - Avaliações vs. frete médio.

Para visualizar os gráficos:





Execute o notebook para ver o mapa de calor (interativo) e os gráficos Matplotlib nas células correspondentes.



Para salvar gráficos como arquivos PNG (para exibição no README ou relatórios):





Adicione plt.savefig('graficos/nome_do_grafico.png') após cada gráfico no notebook.



Crie uma pasta graficos/ no repositório e faça upload dos arquivos PNG.



Exemplo de gráficos salvos (adicionar ao repositório, se disponível):















Resultados da Análise





Faturamento total:





Loja 1: R$1.534.509,12



Loja 2: R$1.488.459,06



Loja 3: R$1.464.025,03



Loja 4: R$1.384.497,58



Vendas por categoria: Todas as lojas têm distribuição semelhante, com destaque para móveis e eletrônicos.



Avaliação média: Todas as lojas têm média de 3,98.



Produtos mais/menos vendidos:





Loja 1: Mais vendido - Micro-ondas (60); Menos vendido - Headset (33).



Loja 2: Mais vendido - Iniciando em programação (65); Menos vendido - Jogo de tabuleiro (32).



Loja 3: Mais vendido - Kit banquetas (57); Menos vendido - Blocos de montar (35).



Loja 4: Mais vendido - Cama box (62); Menos vendido - Guitarra (33).



Frete médio:





Loja 1: R$34,69



Loja 2: R$33,62



Loja 3: R$33,07



Loja 4: R$31,28

Recomendação

Com base na análise, recomenda-se vender a Loja 4, que apresenta o menor faturamento (R$1.384.497,58) e o menor frete médio (R$31,28), sugerindo menor eficiência operacional. Apesar de todas as lojas terem a mesma avaliação média (3,98), a Loja 4 também tem uma distribuição de vendas por categoria semelhante às demais, mas seu desempenho financeiro inferior a torna a candidata ideal para venda.

Estrutura do Repositório





Desafio_LojasAlura_byGabriel.ipynb: Notebook principal com análise, gráficos e recomendação.



graficos/ (opcional): Pasta para armazenar imagens dos gráficos salvos como PNG.



Dados CSV: Carregados diretamente de URLs públicas no notebook.

Contribuição

Contribuições são bem-vindas! Para contribuir:





Faça um fork do projeto.



Crie uma branch para sua feature ou correção (git checkout -b feature/nova-analise).



Faça commit das suas alterações (git commit -m 'Adiciona nova análise').



Envie para o repositório remoto (git push origin feature/nova-analise).



Abra um Pull Request no GitHub.

Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.

Contato

Para dúvidas ou sugestões, entre em contato:





GitHub: GabrielMS-cmd
