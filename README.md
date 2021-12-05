
## Classificador de sentimento aplicando técnicas de PLN
Utilizando o dataset de revisões de filmes em português,
criar um classificador de sentimentos que consiga um score na métrica F1 Score superior a 70%.
Devem utilizar uma amostra de 20% e randon_state igual a 42 para testar as implementações e mensurar a métrica F1 Score (usar o parâmetro average = 'weighted') o restante dos dados devem ser utilizados para o treinamento (80%).

## Resultados

* Logistic Regression
    * Accuracy:
      * Model: 0.8781874371484801 
      * Validation: 0.9410711415978203 
* Logistic Regression with Penalty
    * Accuracy:
 	  * Model: 0.8908354096226934 
 	  * Validation: 0.9797063215075894 
* Decision Tree
    * Accuracy:
 	   * Model: 0.7227919173532654 
 	   * Validation: 0.9433875458106233 
* Multinomial
    * Accuracy:
 	  * Model: 0.8800462145834034 
 	  * Validation: 0.9649568350585455 
* SGD
   * Accuracy:
 	  * Model: 0.7644512304505361 
 	  * Validation: 0.7755798709091858 

## Modelo

* [NLP](trabalhoFinal_NLP.ipynb)

## Autores-Colaboradores

* **Nilo Jose de Andrade Neto** - *Initial work* - [njaneto](https://github.com/njaneto)
* **Davidson Mizael** - *Initial work* - [davidsonmizael](https://github.com/davidsonmizael)
* **Eduardo Nascimento** - *Initial work* - [eduzenite](https://github.com/eduzenite)
