# iFood Case
Este repositório contém a solução para o case do iFood, que abrange desde o processamento inicial dos dados até a modelagem. A estrutura do repositório foi projetada para facilitar a organização e a colaboração.

## Estrutura do Repositório
ifood-case/
├── data/                # Diretório para os datasets do projeto
│   ├── raw/             # Dados originais e não tratados
│   └── processed/       # Dados processados e preparados para análise
├── notebooks/           # Notebooks do Jupyter utilizados para o desenvolvimento
│   ├── 1_data_processing.ipynb     # Notebook para processamento de dados
│   └── 2_modeling.ipynb            # Notebook para modelagem e análise
├── presentation/        # Slides e materiais de apresentação para stakeholders
├── src/                 # Código fonte (opcional, usado caso seja necessário implementar funções específicas)
├── README.md            # Explicação e documentação do repositório
└── requirements.txt     # Bibliotecas e dependências necessárias para executar o projeto

## Descrição dos Notebooks
- 1_data_processing.ipynb: Este notebook é responsável por carregar, limpar, tratar e transformar os dados originais para que possam ser utilizados no processo de modelagem.
- 2_modeling.ipynb: Este notebook contém a análise e construção do modelo para predizer ou classificar os dados baseados no case fornecido.

## Como Utilizar
1. Pré-requisitos:
   - Certifique-se de ter Python instalado.
   - Instale as dependências listadas no arquivo requirements.txt:
     
bash
     pip install -r requirements.txt
     
2. Execução:
   - Comece pelo notebook de processamento de dados (1_data_processing.ipynb) para gerar os dados tratados no diretório data/processed/.
   - Em seguida, execute o notebook de modelagem (2_modeling.ipynb), que utiliza os dados processados para realizar as análises e predições.

## Contribuição
Caso queira contribuir para este projeto:
- Realize um fork do repositório.
- Crie uma nova branch para sua funcionalidade (git checkout -b minha-nova-feature).
- Realize um commit das alterações (git commit -m 'Adiciona minha nova feature').
- Faça um push para a branch criada (git push origin minha-nova-feature).
- Crie um Pull Request.
---
