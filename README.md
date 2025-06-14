# BudgetWiseJennifer - Gestion de budget personnel

## Présentation

**BudgetWise** est une application web de gestion de budget personnel. Elle permet aux utilisateurs de suivre leurs revenus et leurs dépenses, d’analyser leurs finances, et de mieux contrôler leur solde mensuel. Ce projet a été développé dans le cadre d'un exercice DevOps, intégrant des outils modernes d'intégration continue (CI) et de déploiement continu (CD).

### Fonctionnalités principales

- **Ajout, modification et suppression** de revenus/dépenses
- **Suivi du solde disponible en temps réel**
- **Visualisation des dépenses par catégorie**
- **Filtrage personnalisé** (par période, type, mois, etc.)
- **Tags personnalisés** pour les transactions (ex : "Urgent", "Récurrent")
- **Définition d’un budget mensuel**
- **Graphiques d’analyse** (via Chart.js)
- **Export PDF** d’un bilan mensuel *(bonus)*


## Technologies utilisées

| Composant       | Technologie              |
|-----------------|--------------------------|
| Backend         | Python + Flask           |
| Frontend        | HTML, CSS, JavaScript    |
| Base de données | Stockage en mémoire (démo) |
| Charting        | Chart.js                 |
| CI/CD           | GitHub Actions + Render  |
| Tests           | Pytest                   |
| Linting         | Flake8                   |

## Lien vers la démo en ligne

[Lien Render](https://budgetwisejennifer.onrender.com)

## Lien GitHub

[Lien GitHub](https://github.com/JenniferKenmoe/Budgetwisejennifer.git)

## Déploiement local

### Prérequis

- Python 3.13
- `pip` installé

### Étapes d'installation

```bash
# Cloner le dépôt
git clone https://github.com/JenniferKenmoe/Budgetwisejennifer.git
cd Budgetwisejennifer/backend

# Installer les dépendances
pip install -r requirements.txt

# Lancer le serveur Flask
python app.py
