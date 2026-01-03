# Tema 3 – Analiza regulilor de asociere (FP-Growth vs Apriori)

Acest repository conține codul sursă utilizat pentru preprocesarea datelor
FAO/WHO GIFT și pentru extragerea regulilor de asociere folosind algoritmii
FP-Growth și Apriori.

## Structura proiectului
- analysis.py / Tema3_IA.ipynb – implementarea completă a analizei
- data/consumption_user.csv – setul de date utilizat
- requirements.txt – dependențe Python

## Pașii realizați
1. Preprocesarea datelor de consum alimentar
2. Construirea bazei tranzacționale (individ + zi)
3. Compararea FP-Growth și Apriori din punct de vedere al performanței
4. Extragerea și evaluarea regulilor de asociere (support, confidence, lift)

## Rulare
Instalați dependențele:
pip install -r requirements.txt

Rulați scriptul:
python analysis.py
