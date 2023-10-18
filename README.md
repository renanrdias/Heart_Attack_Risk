# ADA - Projeto Machine Learning I
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=main)

- Instituição: Ada Tech
- Curso: Santander Coders
- Disciplina: Machine Learning I
- Professores: Gilberto Kaihami
- Alunos: Amanda Magalhaes, Daniel Custodio, Douglas Vieira Rocha, Marcia Freitas, Renan Dias

Este projeto é uma exploração dos datasets: [Heart Attack Risk Prediction Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data) fornecidos pelo [Kaggle](https://www.kaggle.com/). O foco é realizar uma análise nesses dados e desenvolver um modelo preditivo em relação ao risco de ataque cardiaco.

A especificação completa do projeto pode ser encontrada em: [Projeto Machine Learning](https://github.com/magalhaesaamanda/Heart_Attack_Risk/blob/main/utils/Projeto_Especificacoes.ipynb).


## Sobre os dados

### Contexto
O conjunto de dados de previsão de risco de ataque cardíaco serve como um recurso valioso para explorar as dinâmicas intricadas da saúde cardíaca e seus fatores preditivos. Os ataques cardíacos, ou infartos do miocárdio, continuam sendo um problema de saúde global significativo, exigindo uma compreensão mais profunda de seus precursores e possíveis fatores de mitigação. Este conjunto de dados engloba uma ampla variedade de atributos, incluindo idade, níveis de colesterol, pressão sanguínea, hábitos de fumo, padrões de exercício, preferências alimentares e muito mais, com o objetivo de elucidar a complexa interação dessas variáveis na determinação da probabilidade de um ataque cardíaco. Ao empregar análises preditivas e aprendizado de máquina neste conjunto de dados, pesquisadores e profissionais de saúde podem trabalhar em estratégias proativas para a prevenção e gerenciamento de doenças cardíacas. O conjunto de dados representa um testemunho dos esforços coletivos para aprimorar nossa compreensão da saúde cardiovascular e abrir caminho para um futuro mais saudável.

### Conteúdo
O conjunto de dados fornece uma ampla gama de características relevantes para a saúde cardíaca e escolhas de estilo de vida, abrangendo detalhes específicos do paciente, como idade, gênero, níveis de colesterol, pressão sanguínea, frequência cardíaca e indicadores como diabetes, histórico familiar, hábitos de fumo, obesidade e consumo de álcool. Além disso, fatores de estilo de vida, como horas de exercício, hábitos alimentares, níveis de estresse e horas sedentárias, estão incluídos. Aspectos médicos que envolvem problemas cardíacos anteriores, uso de medicamentos e níveis de triglicerídeos também são considerados. Aspectos socioeconômicos, como renda, e atributos geográficos, como país, continente e hemisfério, estão incorporados. O conjunto de dados, composto por 8763 registros de pacientes de todo o mundo, culmina em um recurso de classificação binária crucial que denota a presença ou ausência de risco de ataque cardíaco, fornecendo um recurso abrangente para análise preditiva e pesquisa em saúde cardiovascular.

### Base de dados

- Patient ID: Identificador único para cada paciente
- Age: Idade do paciente
- Sex: Gênero do paciente (Masculino/Feminino)
- Cholesterol: Níveis de colesterol do paciente
- Blood Pressure: Pressão sanguínea do paciente (sistólica/diastólica)
- Heart Rate: Frequência cardíaca do paciente
- Diabetes: Se o paciente tem diabetes (Sim/Não)
- Family History: Histórico familiar de problemas relacionados ao coração (1: Sim, 0: Não)
- Smoking: Status de fumante do paciente (1: Fumante, 0: Não fumante)
- Obesity: Status de obesidade do paciente (1: Obeso, 0: Não obeso)
- Alcohol Consumption: Nível de consumo de álcool pelo paciente (Nenhum/Leve/Moderado/Pesado)
- Exercise Hours Per Week: Número de horas de exercício por semana
- Diet: Hábitos alimentares do paciente (Saudável/Médio/Inadequado)
- Previous Heart Problems: Problemas cardíacos anteriores do paciente (1: Sim, 0: Não)
- Medication Use: Uso de medicamentos pelo paciente (1: Sim, 0: Não)
- Stress Level: Nível de estresse relatado pelo paciente (1-10)
- Sedentary Hours Per Day: Horas de atividade sedentária por dia
- Income: Nível de renda do paciente
- BMI: Índice de Massa Corporal (IMC) do paciente
- Triglycerides: Níveis de triglicerídeos do paciente
- Physical Activity Days Per Week: Dias de atividade física por semana
- Sleep Hours Per Day: Horas de sono por dia
- Country: País de origem do paciente
- Continent: Continente onde o paciente reside
- Hemisphere: Hemisfério onde o paciente reside
- Heart Attack Risk: Presença de risco de ataque cardíaco (1: Sim, 0: Não)

## Objetivo

Este projeto tem como objetivo principal o desenvolvimento de um modelo de previsão de risco de ataque cardíaco. Através da aplicação de técnicas avançadas de aprendizado de máquina e análise de dados, buscamos criar uma ferramenta de avaliação precisa que possa ser utilizada por profissionais de saúde e pacientes. O modelo utilizará uma variedade de informações, incluindo dados demográficos, histórico médico, hábitos de vida e indicadores de saúde, para determinar o risco de um paciente sofrer um ataque cardíaco. Essa previsão é crucial para permitir intervenções precoces e estratégias preventivas, contribuindo assim para a melhoria da saúde cardiovascular e a qualidade de vida dos pacientes.

## Ferramentas Usadas 
Este projeto foi concluído usando Python e suas bibliotecas associadas, como NumPy, Pandas, Matplotlib, Seaborn, Ipykernel, Scikit-learn.

## Integrantes
Projeto desenvolvido pelos Devs:

- [Amanda Magalhaes](https://github.com/magalhaesaamanda)
- [Douglas Rocha](https://github.com/dogaVrocha)
- [Marcia Freitas](https://github.com/marciafurtadodf)
- [Renan Dias](https://github.com/renanrdias)

## Recomendações
- Cada desenvolvedor terá um notebook destinado à sua própria análise exploratória.
- Em relação aos commits será utilizado um padrão:
    - Commits de novas features. Ex: git commit -m "Adicionando: Readme"
    - Commits de updates. Ex: git commit -m "Alterando: Readme - alteração"
    - Commits de remoção. Ex: git commit -m "Deletando: Readme"

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.11.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
conda env create -f environment.yml
```

- Ativar
```sh
conda activate ada_env
```

- Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

- Criar ambiente virtual
```sh
python -m venv ada_env
```

- Ativar
```sh
source ./ada_env/bin/activate
```

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
pip install -r requirements.txt
```

- Desativar
```sh
deactivate
```

## Organização do projeto
```sh
Heart_Attack_Risk
 ┣ data
 ┃ ┗ heart_attack_prediction_dataset.csv
 ┣ main
 ┃ ┣ edas
 ┃ ┃ ┗ EDA.ipynb
 ┃ ┗ model
 ┃ ┃ ┗ Heart_Attack_Risk.ipynb
 ┣ utils
 ┃ ┣ environment.yml
 ┃ ┗ Projeto_Especificacoes.ipynb
 ┗ README.md
```

## Contribuições
As contribuições são sempre bem-vindas. Se você é um desenvolvedor, cientista de dados ou analista, pode contribuir para o projeto de várias maneiras, tais como:

- Criar novos notebooks;
- Desenvolver novas análises e novos modelos;
- Encontrar e corrigir erros;
- Ajudar a documentar o código;
- Refatorar o código existente.

