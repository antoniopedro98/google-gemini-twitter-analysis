# Google Developers Group - Análise de Tweets com o Gemini

Este repositório contém os Notebooks usados no encontro do Google Developers Group Vassouras/Três Rios no dia 04 de Maio de 2024. Neste encontro, trabalhamos com a [API do Gemini](https://ai.google.dev/gemini-api/docs/get-started/python) para realizar uma Análise de Sentimentos sobre um conjunto de tweets. Na pasta [Tweets](https://github.com/antoniopedro98/google-gemini-twitter-analysis/tree/main/Tweets) foi disponibilizado um conjunto de dados testados para que seja um pontapé inicial. O contextxo foi a vitória de um time grande contra um time de menor expressão, após a goleada sofrida no jogo anterior para um rival.

# Requisitos

- [Python 3.10](https://www.python.org/downloads/release/python-3100/)
- [Pipenv](https://pypi.org/project/pipenv/)

# Como começar

Nós usamos um ambiente virual oferecido pelo *pipenv*. Para ativá-lo e o configurar, você precisa

- *git clone* neste repositório
- Abrir o terminal na raiz deste repositório e digitar:
  - pipenv install (*vai instalar todas as bibliotecas necessárias*)
  - pipenv shell  (*vai ativar o ambiente virtual*)

# Execução

Uma vez que você ativou o ambiente virtual, você só precisa digitar no terminal aberto na raiz deste projeto:

- jupyter notebook

# Novas Bibliotecas

Se você deseja instalar novas bibliotecas, para outras análises, por exemplo, você precisa instalá-las no seu ambiente virtual, e não no seu sistema. Em outras palavras, para instalar novas bibliotecas neste projeto, basta digitar:

- pipenv install lib-name
