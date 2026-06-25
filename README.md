# Trabalho Final: Detecção de Fraude em Transações de Varejo
## Detalhes do Trabalho:
* O presente trabalho analisa o dataset `retail_fraud_detection_100k.csv` usando as bibliotecas python presentes no `requirements.txt`. Além disso, faz o treinamento e a previsão utilizando 3 modelos de IA:
    1. Regressão Logistica
    2. KNN
    3. RandomForest
    4. Isolation Forest(Unico modelo Não-Supervisionado)
---
## Consideração importante:
* O presente projeto foi feito no Google Colab em um Notebook(.ipynb). Portanto, pra ter uma plena visualização, só executar o main.py não será muito bom pra visualização.
---
## Como executar o código?
* Para executar o código, recomendo a criação de um env local(.env). Pra isso, siga os seguintes passos(caso esteja no Linux):
````bash
# Dentro da raíz do projeto:

python -m venv .env
# Criação do .env

source .env/bin/activate
# Ativacao da env local
# Essa parte é a que mais varia de acordo com o seu SO. Verifique como é o comando de ativação caso você esteja no Windows ou MacOS

pip install -r requirements.txt
# instala as libs do projeto no env local
````

Após esse passo a passo, você pode executar o comando `python main.py` no terminal(desde que esteja na raiz deste projeto) ou ir pelo caminho mais interessante: `Visualizar o Notebook`

- Para isso, abra seu terminal e dê os seguintes comandos:

````bash
jupyter lab
# Esse comando abrirá um servidor local na raiz deste projeto e abrirá uma página com uma interface no seu navegador. Lá você deve ir até `Trabalho Final.ipynb` e dar dois cliques para abrir o notebook. Após isso, comece a clicar no [botão de play] na aba abaixo do "indicador de pagina" do TrabalhoFinal.ipynb. Ele executará cada celula e assim você conseguirá acompanhar o processo sem mais problemas.
````

Ou simplesmente visualize o `TrabalhoFinal.ipynb`, mas você não conseguirá executar o código caso queira testar mudar o valor de alguma variavel ou parametro.

