# Fashion MNIST – Klassificering av klädesplagg

## Krav
- Python 3.13.7

## Om projektet
Vi har byggt en modell som klassificerar klädesplagg från Fashion MNIST-datasetet.
Fokusområde: optimering och learning rate.

## Installation
1. Skapa en virtuell miljö: `python -m venv .venv`
2. Aktivera den: `.venv\Scripts\activate`
3. Installera paket: `pip install -r requirements.txt`

## Kör projektet
Öppna `optimization_and_learning rate.ipynb` i VS Code eller Jupyter.

## Resultat
Adam: 88.14%, AdamW: 87.58%, SGD+Momentum: 87.42%, SGD: 85.08%, SGD (låg lr): 79.39%
Bästa optimerare: Adam. CNN-modellen uppnådde 89.9% accuracy.