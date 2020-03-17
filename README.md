# Brief Time Series - mardi 17 mars 2020

## Restitution de veille

Au menu : compter le nombre de paramètres d'un CNN par Christophe ([et là aussi](https://www.learnopencv.com/number-of-parameters-and-tensor-sizes-in-convolutional-neural-network/)) [ou là](https://datascience.stackexchange.com/questions/55402/how-many-parameters-in-a-conv2d-layer)

## Qu'est-ce qu'une série temporelle ?

* Quelles sont les particularités des séries temporelles ?
* Chercher 3 exemples de time series (voir Kaggle, github, etc.) si possible avec des dynamiques très différentes

## Résultat de la pêche

## Caractériser une série temporelle
* Tracer les séries choisies
* Les qualifier en termes de moyenne, tendance, saisonnalité, cycle
* Qu'est-ce que la stationnarité ?
* Appliquer le test de Dickey-Fuller à une série temporelle visiblement non stationnaire
* Rendre la série stationnaire (comment ?)
* Ré-appliquer le test à la série stationnarisée
* Prendre un exemple de série avec cycle et appliquer une méthode de désaisonnalisation

## Ressources pour le matin

* Décomposition d'une série temporelle :
[ici](https://machinelearningmastery.com/decompose-time-series-data-trend-seasonality/)
et [là](https://anomaly.io/seasonal-trend-decomposition-in-r/index.html) et [ici](https://machinelearningmastery.com/time-series-trends-in-python/)

* Stationnarité et test de Dickey-Fuller augmenté :
[ici](https://fr.wikipedia.org/wiki/Stationnarit%C3%A9_d%27une_s%C3%A9rie_temporelle)
[ici](https://towardsdatascience.com/stationarity-in-time-series-analysis-90c94f27322)
et [là](https://machinelearningmastery.com/time-series-data-stationary-python/)
et [ici](https://nwfsc-timeseries.github.io/atsa-labs/sec-boxjenkins-aug-dickey-fuller.html)

* Désaisonnalisation : [ici](https://machinelearningmastery.com/time-series-seasonality-with-python/)

* FFT : [ici](https://www.ritchievink.com/blog/2017/04/23/understanding-the-fourier-transform-by-example/)

* Un bon notebook Kaggle utilisant la librairie statsmodel : [ici](https://www.kaggle.com/harryren/boston-arima-forecast-and-analysis)

* Un cours complet sur les séries temporelles avec des exemples en python : [ici](https://www.tutorialspoint.com/time_series/index.htm)

## Mise en commun et partage d'expérience

## Les techniques classiques de prédiction

* Les baselines les plus simples ?
* Modèles AR, MA, ARMA, ARIMA
	* Equations ?
	* Paramètres ?
	* Ordres ?

* Extensions de ces modèles : VAR, VARMA, MAR -> faire une petite recherche pour les situer par rapport à ARIMA	

## Auto-corrélation

* Avec les séries temporelles déjà choisies, tracer l'ACF
* Avec les séries temporelles déjà choisies, tracer la PACF
* En déduire le modèle ARIMA adapté
* Implémenter le modèle ARIMA correspondant, changer ses ordres et observer


## Evaluation de la qualité des modèles

* Qu'est-ce que le backtest ?
* Walk-forward validation


## Ressources pour l'après-midi

* Librairie statsmodels [ici](https://www.statsmodels.org/stable/index.html)

* Méthodes de prédictions classiques : [ici](https://machinelearningmastery.com/simple-time-series-forecasting-models/) et [là](https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/) et [là](https://www.kaggle.com/thebrownviking20/everything-you-can-do-with-a-time-series) et [là](https://towardsdatascience.com/time-series-in-python-exponential-smoothing-and-arima-processes-2c67f2a52788)

* ACF/PACF : [ici](https://machinelearningmastery.com/gentle-introduction-autocorrelation-partial-autocorrelation/) et [là](https://towardsdatascience.com/significance-of-acf-and-pacf-plots-in-time-series-analysis-2fa11a5d10a8)

* ARIMA : [ici](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/), [là](http://people.duke.edu/%7Ernau/Notes_on_nonseasonal_ARIMA_models--Robert_Nau.pdf) et [là](https://people.duke.edu/~rnau/411arim2.htm)

* Validation de modèles de prédiction : [ici](https://machinelearningmastery.com/backtest-machine-learning-models-time-series-forecasting/) et [là](https://blog.insightdatascience.com/whats-wrong-with-my-time-series-model-validation-without-a-hold-out-set-94151d38cf5b)

* Des modèles plus exotiques : ARCH, GARCH [voir](https://en.wikipedia.org/wiki/Autoregressive_conditional_heteroskedasticity)

* Un exemple d'analyse de série temporelle : [ici](https://towardsdatascience.com/almost-everything-you-need-to-know-about-time-series-860241bdc578)

* Vidéo d'ouverture sur d'autres méthodes, l'exemple d'Uber : [ici](https://youtu.be/VYpAodcdFfA)

* Un livre entier sur les méthodes de prédiction : [ici](https://otexts.com/fpp2/)

## Retour et partage d'expérience



## A SUIVRE Filtre de Kalman, FFT, RNN, LSTM/GRU, seq2seq...
