# Análise Exploratória da Arrecadação Tributária no Brasil

Este repositório contém uma análise detalhada dos dados de arrecadação tributária no Brasil, explorando padrões, tendências e relações entre diferentes tipos de impostos ao longo do tempo e entre os diversos estados brasileiros.

## 📊 Objetivo

O objetivo principal desta análise é compreender melhor os fatores que influenciam a arrecadação tributária no Brasil e identificar diferenças regionais e temporais significativas, oferecendo insights que podem ser úteis para políticas públicas e planejamento fiscal.

## 🔍 Metodologia

A análise está dividida em várias etapas:

1. **Pré-processamento dos dados**: Tratamento de valores ausentes e normalização das variáveis.
2. **Análise descritiva**: Exploração de tendências temporais, padrões sazonais e eventos econômicos significativos.
3. **Análise de correlação**: Identificação de relações entre diferentes tipos de impostos.
4. **Clusterização**: Agrupamento dos estados brasileiros com base em perfis de arrecadação.
5. **Redução de dimensionalidade (PCA)**: Visualização dos clusters em componentes principais.
6. **Visualizações**: Gráficos detalhados para facilitar a interpretação dos resultados.

## 📈 Principais Descobertas

Entre os insights mais relevantes desta análise:

- **Crescimento consistente**: Todos os indicadores mostram uma tendência de crescimento na arrecadação ao longo do período 2000-2024.
- **Aceleração recente**: Entre 2020-2024, observa-se uma aceleração significativa em todos os indicadores, com o crescimento se tornando mais acentuado.
- **Sazonalidade**: Dezembro geralmente apresenta valores mais altos que a média anual, enquanto fevereiro costuma mostrar uma queda significativa.
- **Concentração regional**: São Paulo sozinho responde por aproximadamente 38% de toda a arrecadação nacional, com os 3 maiores estados concentrando 63,1% do total.
- **Perfis distintos**: A análise de clusters identificou diferentes perfis de arrecadação entre os estados brasileiros.

## 🔧 Técnicas Utilizadas

- Análise estatística descritiva
- Visualização de dados com Matplotlib e Seaborn
- Clusterização com K-means
- Análise de Componentes Principais (PCA)
- Análise de correlação entre variáveis

## 📂 Estrutura do Projeto

- `analise.ipynb`: Notebook principal contendo toda a análise exploratória e visualizações
- `Base dos Dados - Resultado da Arrecadacao.csv`: Conjunto de dados utilizado (fonte: Base dos Dados)

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📝 Como Usar

1. Clone este repositório
2. Certifique-se de ter todas as dependências instaladas: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Abra o notebook `analise.ipynb` em um ambiente Jupyter
4. Execute as células sequencialmente para reproduzir a análise

## 🔗 Fonte dos Dados

Os dados utilizados nesta análise são provenientes da "Base dos Dados", uma iniciativa que disponibiliza conjuntos de dados públicos do Brasil em formato acessível.

## 📜 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.

---

Este projeto é parte de um estudo pessoal sobre finanças públicas e economia brasileira. Contribuições e sugestões são bem-vindas!
