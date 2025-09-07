# LH_CD_CamillySilva

Este projeto realiza uma análise exploratória de dados (EDA) de um banco cinematográfico e constrói um modelo preditivo para estimar a nota do IMDB dos filmes. O objetivo é fornecer orientações sobre que tipo de filme deve ser produzido.

### Intalação

Primeiramente instale os pacotes necessários:

```
pip install -r requirements.txt

```

Clone este repositório:
```
git clone https://github.com/CamillySR/LH_CD_CamillySilva.git
cd LH_CD_CamillySilva
```

### Como Executar
Abra o Jupyter Notebook:

```
jupyter notebook
```

Abra os notebooks:
- eda_modelagem.ipynb
- teste_modelo.ipynb

Para usar o modelo no Jupyter:
```
import pickle

with open("modelo.pkl", "rb") as arquivo:
    modelo = pickle.load(arquivo)
```
