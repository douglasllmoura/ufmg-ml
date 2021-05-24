# Machine Learning 2020.1

Repositório as atividades da disciplina de machine learning (DCC - UFMG)

## Instalação

Primeiramente, clone o repositório do projeto em um diretório de sua preferência:

```
$ mkdir ufmg-ml && cd ufmg-ml
$ git clone https://github.com/douglasllmoura/ufmg-ml.git
```

Os seguintes pré-requisitos são necessários:
- **Python** v3.6 ou similar.
- Instalar as bibliotecas jupyter, matplotlib, numpy, pandas, scipy e scikit-learn.

Configurando um ambiente virtual:
```
$ virtualenv -p python3 .env
$ source .env/bin/activate
$ pip install requirements.txt
```

Por fim, execute o comando **jupyter notebook** para iniciar o servidor Jupyter.
