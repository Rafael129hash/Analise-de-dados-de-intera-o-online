# Análise de Dados - Uso de Mídias Sociais

Este projeto utiliza **Python** e **Jupyter Notebook** para realizar uma análise exploratória de um conjunto de dados que descreve o uso de mídias sociais por diferentes usuários. A análise abrange fatores como tempo de uso, idade, país de origem e número total de "likes".

Os dados utilizados nesta análise estão disponíveis no [Kaggle](https://www.kaggle.com).

## Visão Geral do Conjunto de Dados

O conjunto de dados contém as seguintes colunas:

- `UserId`: Identificador único de cada usuário.
- `UsageDuration`: Duração de uso das redes sociais (em horas).
- `Age`: Idade dos usuários.
- `Country`: País de origem dos usuários.
- `TotalLikes`: Total de "likes" recebidos nas redes sociais.

### Exemplo de dados:

| UserId | UsageDuration | Age | Country      | TotalLikes |
|--------|---------------|-----|--------------|------------|
| 1      | 2             | 55  | Turkey       | 5          |
| 2      | 6             | 45  | Canada       | 10         |
| 3      | 3             | 50  | Ireland      | 7          |
| 4      | 4             | 35  | South Africa | 5          |
| 5      | 1             | 58  | Turkey       | 2          |

## Ferramentas Utilizadas

- **Linguagem**: Python
- **Ambiente de Desenvolvimento**: Jupyter Notebook
- **Bibliotecas**:
  - `pandas`: Para manipulação e análise de dados.
  - `matplotlib` e `seaborn`: Para visualização dos dados.
  

## Objetivos da Análise

1. Entender o comportamento dos usuários em relação ao tempo de uso das redes sociais.
2. Explorar a relação entre a idade dos usuários e o total de "likes" recebidos.
3. Identificar tendências de uso de acordo com a localização geográfica.

## Resultados

### Análise da Duração do Uso

Foi analisada a média de tempo de uso por diferentes grupos etários e regiões. A tendência observada mostra que usuários mais jovens tendem a passar mais tempo nas redes sociais em comparação aos mais velhos.

### Distribuição de "Likes"

A distribuição de "likes" também foi estudada para verificar se há uma correlação entre a idade e o engajamento social.
