# JSON, API et géocodage

Quête S09 — lecture de JSON imbriqué, interrogation d'API REST,
géocodage d'adresses et affichage sur une carte.

## Contenu

- `notebooks/quete_json_api.ipynb` : l'intégralité du travail
- `data/` : les fichiers JSON de départ et le CSV géocodé produit

## Installation

python -m venv .venv
pip install -r requirements.txt

## Ce que fait le projet

Les trois challenges : aplatissement d'un JSON à deux niveaux,
géocodage d'une série d'adresses via l'API Adresse,
et cartographie de quatre restaurants de Catane via Nominatim.