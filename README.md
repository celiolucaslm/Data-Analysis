# Data Analysis of users Amazon Prime

Esse projeto visa descrever uma base de dados de usuários Amazon Prime fornecida pelo site [Kaggle](https://www.kaggle.com/datasets/arnavsmayan/amazon-prime-userbase-dataset). Nela foi realizada a verificação dos dados para limpeza e, posteriormente, a análise exploratória dos dados no [notebook](https://github.com/celiolucaslm/Data-Analysis/blob/main/amazon_prime.ipynb).

Para exibir os principais insights coletados durante a análise, foi construído um dashboard a partir da biblioteca [Dash](https://dash.plotly.com), com uma comunicação clara e simples além de que também fosse possível que o usuário interagisse com as informações mostradas.

Abaixo está uma descrição de como as informações foram dispostas.

## Informações numéricas do dataset
![first part](https://github.com/user-attachments/assets/47e39a87-a80a-4c4c-b41f-9972ddbf72f7)

- Nessa parte foi exibido as principais informações numéricas do dataset, incluindo o título e um botão para alterar a exibição de todos os gráficos de acordo com a escolha do gênero pelo usuário.

## Informações demográficas do dataset
![second part](https://github.com/user-attachments/assets/82db9e8f-f09d-4eec-9ddb-c6034e77efa3)

- Aqui foram colocados dois gráficos para representar as principais informações demográficos dos usuários, além de que ambos são interativos, dando a possibilidade de que o usuário arraste pelo mapa e obter as informações específicas do gráfico apenas passando o mouse.

## Informações sobre o uso do produto pelos usuários
![third part](https://github.com/user-attachments/assets/f6865390-bb65-47c2-84ee-483151dd82bf)
![third part](https://github.com/user-attachments/assets/d58608b5-7286-4fe6-b1b5-da3737f7cc4e)
![third part](https://github.com/user-attachments/assets/f7107a15-6d97-472d-995c-71a7fbb152ed)

- Nessa parte foram exibidos os principais dados sobre interações entre os clientes e a plataforma, dando informações sobre os tipos de planos mais assinados, como é feita a renovação pelos usuários a partir do seu engajamento na plataforma, frequência de uso, histórico de compra, gêneros favoritos e os principais dispositivos que são utilizados pelos usuários ao acessarem a plataforma.

## Informações de negócio sobre os clientes
![final part](https://github.com/user-attachments/assets/12a546f0-7961-4357-aa0c-bb3395a9c0e7)

- Aqui foi exibido o gráfico da quantidade de usuários com alta tendência a largar a plataforma a partir de uma métrica de negócio definida como:

<p align="center">
  <img src="https://github.com/user-attachments/assets/5cb2607a-2fb8-4472-8d6a-a750ab251245" alt="venn" width="350">
</p>

- Dessa forma, apenas os clientes nessa condição foram contabilizados e exibidos para que outros departamentos como de produto, marketing, vendas e etc possam tomar medidas para reter esse usuários.

- Além de também exibir a distruibuição da interação dos clientes com o suporte, o que é importante do ponto de vista de negócio para entender como tem sido o funcionamento da plataforma.

