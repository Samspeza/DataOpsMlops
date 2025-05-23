📚 Projeto Acadêmico – MLOps e DataOps

Este repositório contém os artefatos, notebooks, scripts e configurações utilizados nas atividades da disciplina de MLOps e DataOps do curso de Pós-Graduação. O objetivo principal é aplicar práticas modernas de engenharia de Machine Learning e Operações de Dados, integrando componentes como:

    Monitoramento de Data Drift

    Treinamento automatizado de modelos

    Versionamento de artefatos

    Containerização com Docker

    Orquestração de pipelines

    Testes de performance com Locust

    Gerenciamento de ambientes e dependências

🗂 Estrutura Geral do Projeto

📦 mlops-dataops/
│
├── 📁 notebooks/              # Notebooks para exploração e experimentos
│   ├── DataOps - Data Drift.ipynb
│   ├── AutoML_com_AutoKeras.ipynb
│   └── train_notebook.ipynb
│
├── 📁 src/                    # Scripts centrais da aplicação
│   ├── main.py
│   ├── train.py
│   ├── test_train.py
│   ├── model_registry.py
│   └── pipeline.yaml
│
├── 📁 config/                 # Configurações e ambientes
│   ├── environment.yaml
│   ├── locustfile.py
│
├── 📁 docker/                 # Container Docker para execução padronizada
│   └── Dockerfile
│
├── requirements.txt          # Lista de dependências Python
├── README.md                 # Documentação geral do projeto
└── .gitignore                # Exclusões de versionamento

🎯 Objetivos Acadêmicos

    Entender e aplicar os conceitos de CI/CD para ML

    Realizar automação e rastreabilidade de experimentos

    Implementar práticas de DataOps para garantia de qualidade de dados

    Desenvolver pipelines reprodutíveis com foco em produção

