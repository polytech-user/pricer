# Pricing d'Option Asiatique – Simulation Monte Carlo

Ce projet implémente le pricing d'une **option asiatique à moyenne arithmétique** sous le modèle de **Black-Scholes**, en utilisant la **méthode de Monte Carlo**.

Le notebook contient :
- La modélisation mathématique du prix de l’option asiatique (Call européen).
- La simulation de trajectoires de prix.
- L’analyse de convergence selon le nombre de simulations.
- Des techniques de **réduction de variance** pour améliorer la précision.

## 📈 Objectif

Estimer numériquement le prix d’une option asiatique dans un marché sans arbitrage, et comparer différentes méthodes d’optimisation numérique.

## ⚙️ Méthodologie

- Hypothèses du modèle de Black-Scholes
- Génération de trajectoires via un mouvement brownien géométrique
- Calcul du payoff moyen et actualisé
- Réduction de la variance : 
  - Variables antithétiques
  - Control variates (option européenne fermée)

## 🔧 Technologies utilisées

- Python 3
- NumPy / Pandas
- Matplotlib
- Jupyter Notebook

## 📁 Structure

- `README.md` : Ce fichier
- `option_asian_pricing.ipynb` : Notebook principal avec le code et les résultats

# Equations
- **Mouvement Brownien** : $S_t= S_0 e^{(r - \frac{\sigma^2}{2})t + \sigma W(t)}$


