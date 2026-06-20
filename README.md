<!--
  README de profil. Place ce fichier dans le repo public nommé geheres-dotcom.
  Les liens pointent vers tes repos existants.
-->

## Compétences / Skills

- Langages : Python, C++, C#, TypeScript, SQL, VBA
- Quant & data : NumPy, pandas, scikit-learn, Gurobi, Streamlit
- Outils : Git, Linux, React Native / Expo, Supabase
- Domaines : pricing d'options, calcul stochastique, risque de marché (VaR, ES, EVT), risque de contrepartie, arbitrage statistique

## Projets / Projects

### Finance quantitative

**Arbitrage statistique — marché du blé**
Stratégie market-neutral exploitant les relations de cointégration entre le future sur le blé et un panier d'actions agricoles : signaux Z-score et optimisation quadratique sous contraintes via Gurobi. Sharpe de 1,14 et Calmar de 1,46 sur la version pairs trading.
A market-neutral strategy built on cointegration between the wheat futures contract and a basket of agricultural equities, using Z-score signals and constrained quadratic optimization with Gurobi. Sharpe of 1.14 and Calmar of 1.46 on the pairs-trading variant.
Technologies : Python, Gurobi, statsmodels
[Repository](https://github.com/geheres-dotcom/wheat-stat-arb)

**Market Risk — VaR, Expected Shortfall et théorie des valeurs extrêmes**
Mesures de risque sur l'action Natixis, implémentées sans aucune librairie : VaR historique non-paramétrique (noyau biweight), backtesting hors-échantillon, Expected Shortfall, estimation de la queue de distribution par l'estimateur de Pickands et modèle d'impact prix de Bouchaud.
Risk measures on the Natixis stock, implemented from scratch with no libraries: non-parametric historical VaR (biweight kernel), out-of-sample backtesting, Expected Shortfall, tail estimation via the Pickands estimator, and the Bouchaud price-impact model.
Technologies : Python, Excel
[Repository](https://github.com/geheres-dotcom/market-risk-var-evt)

**Bibliothèque de pricing d'options en C++**
Valorisation d'options européennes, digitales, américaines et asiatiques via trois moteurs : formule fermée de Black-Scholes (avec le delta), arbre binomial de Cox-Ross-Rubinstein gérant l'exercice anticipé, et simulation Monte-Carlo avec intervalle de confiance. Architecture orientée objet par héritage.
Pricing of European, digital, American and Asian options through three engines: the Black-Scholes closed-form solution (with delta), a Cox-Ross-Rubinstein binomial tree handling early exercise, and Monte-Carlo simulation with a confidence interval. Object-oriented design based on inheritance.
Technologies : C++
[Repository](https://github.com/geheres-dotcom/cpp-option-pricer)

**Dashboard finance temps réel**
Tableau de bord Streamlit récupérant des données de marché en temps réel, avec backtesting de stratégies, analyse de portefeuille et un rapport quotidien automatisé par cron, déployé sur un serveur Linux.
A Streamlit dashboard that pulls market data in near real time, with strategy backtesting, portfolio analysis and an automated daily report via cron, deployed on a Linux server.
Technologies : Python, Streamlit, Linux
[Repository](https://github.com/geheres-dotcom/Dashboard-finance-temps-r-el)

### Machine learning

**Machine Learning for Asset Management**
Comparaison entre régression linéaire (OLS) et arbres de régression pour prédire le spot EUR/USD à partir d'indicateurs techniques (MACD, RSI), puis construction de portefeuille par Hierarchical Risk Parity.
Comparison of linear regression (OLS) and regression trees to forecast the EUR/USD spot from technical indicators (MACD, RSI), followed by portfolio construction using Hierarchical Risk Parity.
Technologies : Python, scikit-learn
[Repository](https://github.com/geheres-dotcom/ml-asset-management)

**Prédiction de direction — action Apple**
Prédiction de la direction journalière du cours d'Apple par arbres de décision, random forest et modèle de Markov, avec une validation temporelle sans biais de look-ahead.
Predicting Apple's next-day price direction with decision trees, a random forest and a Markov model, using leakage-free time-series validation.
Technologies : Python, scikit-learn
[Repository](https://github.com/geheres-dotcom/aapl-direction-ml)

**Prédiction de prix — Airbnb**
Prédiction du prix de location d'un logement Airbnb à partir de ses caractéristiques (régression linéaire puis SVR optimisé), avec un pipeline complet de nettoyage et de préparation des données.
Predicting the rental price of an Airbnb listing from its features (linear regression then a tuned SVR), with a full data cleaning and preparation pipeline.
Technologies : Python, scikit-learn
[Repository](https://github.com/geheres-dotcom/airbnb-price-prediction)
