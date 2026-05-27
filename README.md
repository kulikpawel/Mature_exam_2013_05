# Matura Exam 2013 – Exercise 4 / Matura 2013 – Zadanie 4

---

## 🇬🇧 English

### Description

This project contains a solution to **Exercise 4** from the Polish **Matura Exam 2013**, implemented in Python using a Jupyter Notebook (`Matura_2013_exercise_4.ipynb`).

The exercise simulates a feeding schedule for a herd of **90 European bison** in a nature reserve from **December 1, 2012 to February 28, 2013**. It consists of five parts (a–e).

### Feeding Rules

- On **December 1, 2012**, the warehouse contained **100 tons of hay** and **5 tons of acorns**.
- If hay supply ≥ 50 tons → bison are fed **hay** (40 kg per bison per day).
- If hay supply < 50 tons → bison are fed **acorns** (20 kg per bison per day) until hay is replenished to ≥ 50 tons.
- Every **Friday evening** (after feeding): **15 tons of hay** are delivered.
- Every **Tuesday evening** (after feeding): **4 tons of acorns** are delivered.

### Files

| File | Description |
|------|-------------|
| `Matura_2013_exercise_4.ipynb` | Jupyter Notebook with the full solution |

### Exercise Summary

**Part a – Number of deliveries**

How many hay and acorn deliveries occurred between December 1, 2012 and February 28, 2013?

**Result:**
- Hay deliveries: **12**
- Acorn deliveries: **13**

---

**Part b – First acorn feeding**

On which day will the bison first receive only acorns?

**Result:** **December 28, 2012**

---

**Part c – Total hay and acorn feedings**

How many times were the bison fed only hay, and how many times only acorns?

**Result:**
- Hay feedings: **64**
- Acorn feedings: **26**

---

**Part d – Morning food supply levels**

Morning food supply (tons) on selected dates:

| Date | Hay (tons) | Acorns (tons) |
|------|------------|---------------|
| 2012-12-31 | 55.6 | 19.2 |
| 2013-01-31 | 47.2 | 17.6 |
| 2013-02-28 | 49.6 | 12.0 |

A bar chart illustrates these supply levels.

---

**Part e – Maximum herd size**

What is the maximum number of bison that can be added to the herd while still being able to feed it throughout the entire period?

**Result:** **5 additional bison**

### Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries: `numpy`, `pandas`, `matplotlib`

### How to Run

```bash
# Clone the repository
git clone git@github.com:kulikpawel/your-repo-name.git
cd your-repo-name

# Open the notebook
jupyter notebook Matura_2013_exercise_4.ipynb
```

Or open directly in **Google Colab** and mount your Google Drive.

---

## 🇵🇱 Polski

### Opis

Projekt zawiera rozwiązanie **Zadania 4** z polskiej **Matury 2013**, zaimplementowane w języku Python w notatniku Jupyter (`Matura_2013_exercise_4.ipynb`).

Zadanie symuluje harmonogram karmienia stada **90 żubrów** w rezerwacie przyrody od **1 grudnia 2012 do 28 lutego 2013**. Składa się z pięciu części (a–e).

### Zasady karmienia

- **1 grudnia 2012** w magazynie znajdowało się **100 ton siana** i **5 ton żołędzi**.
- Jeśli zapas siana ≥ 50 ton → żubry karmione są **sianem** (40 kg na żubra dziennie).
- Jeśli zapas siana < 50 ton → żubry karmione są **żołędziami** (20 kg na żubra dziennie) do czasu uzupełnienia siana do ≥ 50 ton.
- Każdego **piątkowego wieczoru** (po karmieniu): dostawa **15 ton siana**.
- Każdego **wtorkowego wieczoru** (po karmieniu): dostawa **4 ton żołędzi**.

### Pliki

| Plik | Opis |
|------|------|
| `Matura_2013_exercise_4.ipynb` | Notatnik Jupyter z pełnym rozwiązaniem |

### Streszczenie zadania

**Punkt a – Liczba dostaw**

Ile dostaw siana i żołędzi odbyło się między 1 grudnia 2012 a 28 lutego 2013?

**Wynik:**
- Dostawy siana: **12**
- Dostawy żołędzi: **13**

---

**Punkt b – Pierwsze karmienie żołędziami**

Którego dnia żubry po raz pierwszy otrzymają wyłącznie żołędzie?

**Wynik:** **28 grudnia 2012**

---

**Punkt c – Łączna liczba karmień**

Ile razy żubry były karmione wyłącznie sianem, a ile razy wyłącznie żołędziami?

**Wynik:**
- Karmienia sianem: **64**
- Karmienia żołędziami: **26**

---

**Punkt d – Poranne stany magazynowe**

Poranne stany magazynowe (w tonach) w wybranych datach:

| Data | Siano (tony) | Żołędzie (tony) |
|------|--------------|-----------------|
| 2012-12-31 | 55,6 | 19,2 |
| 2013-01-31 | 47,2 | 17,6 |
| 2013-02-28 | 49,6 | 12,0 |

Wykresy słupkowe ilustrują te stany magazynowe.

---

**Punkt e – Maksymalna liczebność stada**

O ile żubrów można powiększyć stado, aby nadal móc je wyżywić w całym podanym okresie?

**Wynik:** **5 żubrów**

### Wymagania

- Python 3.x
- Jupyter Notebook lub Google Colab
- Biblioteki: `numpy`, `pandas`, `matplotlib`

### Jak uruchomić

```bash
# Sklonuj repozytorium
git clone git@github.com:kulikpawel/nazwa-repo.git
cd nazwa-repo

# Otwórz notatnik
jupyter notebook Matura_2013_exercise_4.ipynb
```

Lub otwórz bezpośrednio w **Google Colab** i podłącz swój Dysk Google.

---

*Rozwiązanie przygotowane w celach edukacyjnych / Solution prepared for educational purposes.*
