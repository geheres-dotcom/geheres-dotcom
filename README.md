<!--
  ┌─────────────────────────────────────────────────────────────┐
  │  PROFIL GITHUB / GITHUB PROFILE                               │
  │  → Crée un repo PUBLIC nommé EXACTEMENT comme ton pseudo,     │
  │    puis place ce fichier dedans sous le nom README.md         │
  │  → Create a PUBLIC repo named EXACTLY like your username,     │
  │    then put this file inside as README.md                     │
  │                                                               │
  │  Profil : github.com/geheres-dotcom                          │
  └─────────────────────────────────────────────────────────────┘
-->

# Gregor Romani — Financial Engineering & Quant Dev

> **FR** · Étudiant MSc Financial Engineering (ESILV), en stage en risque de contrepartie (CCR / xVA). Je code à la croisée de la finance quantitative, du machine learning et du développement applicatif.
>
> **EN** · MSc Financial Engineering student (ESILV), interning in counterparty credit risk (CCR / xVA). I build at the intersection of quantitative finance, machine learning and app development.

---

## 🛠️ Stack technique · Tech Stack

**Langages · Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**Quant & Data**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Gurobi](https://img.shields.io/badge/Gurobi-EE3524?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Frameworks & outils · Frameworks & Tools**

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Domaines · Domains**

`Pricing d'options` · `Calcul stochastique` · `Risque de marché (VaR / ES / EVT)` · `Risque de contrepartie (CCR / xVA)` · `Arbitrage statistique`

---

## 🚀 Projets phares · Featured Projects

### 💹 Finance quantitative · Quantitative Finance

**Arbitrage statistique multivarié — Marché du blé · Multivariate Stat-Arb — Wheat Market**
**FR** · Stratégie market-neutral (Σβ = 0) sur le blé : cointégration (ADF / Engle-Granger), signaux Z-score et optimisation quadratique sous contraintes via Gurobi. Le pairs trading optimisé atteint un Sharpe de 1.14 et un Calmar de 1.46 (net de 10 bps de frais).
**EN** · Market-neutral wheat strategy (Σβ = 0): cointegration (ADF / Engle-Granger), Z-score signals and constrained quadratic optimization with Gurobi. The optimized pairs-trading reaches a 1.14 Sharpe and 1.46 Calmar (net of 10 bps fees).
`Python` · `Gurobi` · `yfinance` · `statsmodels`
🔗 [Voir le projet · View project](https://github.com/geheres-dotcom/wheat-stat-arb)

**Market Risk — VaR, Expected Shortfall & EVT · Market Risk — VaR, ES & EVT**
**FR** · Mesures de risque sur l'action Natixis, entièrement codées sans librairie : VaR historique non-paramétrique (noyau biweight), backtesting hors-échantillon, Expected Shortfall, théorie des valeurs extrêmes (estimateur de Pickands, VaR-EVT) et modèle d'impact prix de Bouchaud.
**EN** · Risk measures on the Natixis stock, fully coded from scratch (no libraries): non-parametric historical VaR (biweight kernel), out-of-sample backtesting, Expected Shortfall, Extreme Value Theory (Pickands estimator, EVT-VaR) and the Bouchaud price-impact model.
`Python` · `Excel` · `EVT` · `Risk Management`
🔗 [Voir le projet · View project](https://github.com/geheres-dotcom/market-risk-var-evt)

**Pricer d'options en C++ · C++ Options Pricing Library**
**FR** · Bibliothèque orientée objet de valorisation d'options (vanilles européennes, digitales, américaines, asiatiques) avec trois moteurs : formule fermée Black-Scholes (+ delta), arbre binomial Cox-Ross-Rubinstein avec exercice anticipé pour les américaines, et Monte-Carlo avec intervalle de confiance. Architecture par héritage et arbre binomial générique (template).
**EN** · Object-oriented option pricing library (European vanilla, digital, American, Asian) with three engines: Black-Scholes closed-form (+ delta), Cox-Ross-Rubinstein binomial tree with early exercise for American options, and Monte-Carlo with confidence interval. Inheritance-based design with a generic binary-tree template.
`C++` · `OOP` · `Monte Carlo` · `Binomial Trees`
🔗 [Voir le projet · View project](https://github.com/geheres-dotcom/cpp-option-pricer)

### 🤖 Machine Learning

**ML for Asset Management — HRP & EUR/USD**
**FR** · Comparaison de régression linéaire (OLS) et d'arbres de régression pour prédire le spot EUR/USD à partir d'indicateurs techniques (MACD, RSI), puis construction de portefeuille par Hierarchical Risk Parity (clustering + risk parity).
**EN** · Comparing OLS and regression trees to forecast the EUR/USD spot from technical indicators (MACD, RSI), then portfolio construction via Hierarchical Risk Parity (clustering + risk parity).
`Python` · `scikit-learn` · `Portfolio Theory`
🔗 [Voir le projet · View project](https://github.com/geheres-dotcom/ml-asset-management)

### 🐍 Data Engineering & Cybersécurité · Data Engineering & Cybersecurity

**Analyse des avis & alertes ANSSI · ANSSI Advisories & Alerts Analysis**
**FR** · Pipeline Python complet : extraction des flux RSS de l'ANSSI, identification des CVE, enrichissement via les API MITRE (CVSS, CWE) et EPSS, consolidation dans un DataFrame pandas, visualisations et génération d'alertes email personnalisées.
**EN** · End-to-end Python pipeline: scraping ANSSI RSS feeds, CVE identification, enrichment through the MITRE (CVSS, CWE) and EPSS APIs, consolidation into a pandas DataFrame, visualizations and custom email alerts.
`Python` · `pandas` · `REST APIs` · `Matplotlib / Plotly`
🔗 [Voir le projet · View project](https://github.com/geheres-dotcom/anssi-cve-analysis)

### 📱 Développement applicatif · App Development

**🎬 my-movie**
**FR** · Application de notation de films et séries (React Native / Expo + Supabase). Recherche avec filtres genre/décennie, deck de suggestions en swipe « à la Tinder », disponibilité par plateforme en France, profil avec statistiques et badges.
**EN** · Movie & TV rating app (React Native / Expo + Supabase). Search with genre/decade filters, a Tinder-style swipe deck, French streaming availability, and a profile with stats and badges.
`React Native` · `Expo SDK 54` · `TypeScript` · `Supabase` · `TMDB API`
🔗 [Voir le projet · View project](https://github.com/geheres-dotcom/my-movie)

---

<!--
  EN COURS / IN PROGRESS — décommente quand les projets seront prêts :
  Uncomment when these are ready to showcase.

### 🚧 En cours · In progress
- **TransConnect** — Application C# de gestion d'une société de transport : POO (héritage,
  classes abstraites, interfaces, délégation), organigramme en arbre n-aire, plus court chemin
  (Dijkstra, Bellman-Ford, Floyd-Warshall) et visualisation du graphe.
- **Real-time Finance Dashboard** — Dashboard Streamlit déployé sur VM Linux : données de marché
  en temps réel, backtesting de stratégies, rapport quotidien automatisé via cron.
-->

<!--
  ASTUCE / TIP : pour ajouter les stats GitHub ou tes réseaux, dis-le moi.
  Want GitHub stats or social links? Just ask.
-->
