# Factor Investing mit Python: Eine Einführung

## 📘 Überblick

Dieses Buch bietet eine praxisorientierte Einführung in das **Factor Investing** und dessen Umsetzung mit **Python**.  
Es kombiniert theoretische Grundlagen mit empirischen Fallstudien und zeigt Schritt für Schritt, wie sich Preis- und Risikofaktoren auf Basis realer Marktdaten konstruieren, analysieren und in Portfolios umsetzen lassen.

Das Buch richtet sich an:
- fortgeschrittene **Finance-Studierende im Master**,  
- **Young Professionals** im Asset Management oder Quant Research,  
- **berufstätige Quants**, die ihre Python-Kompetenzen in der quantitativen Kapitalmarktforschung erweitern möchten.

---

## 🧩 Inhalte

1. **Willkommen zu „Factor Investing mit Python: Eine Einführung“**  
   Motivation, Aufbau und Lernziele des Buches.  
2. **Grundlagen des Factor Investings**  
   Theoretische Basis, Definition von Faktorprämien (Long-Short Strategien), Faktoren als Ranking-Schema.  
3. **Preisbasierte Faktoren: Momentum und Reversal**  
   Umsetzung klassischer Trend- und Umkehrstrategien in Python.  
4. **Risikobasierte Faktoren: Total Risk**  
   Faktorkonstruktion auf Basis der Gesamtvolatilität.  
5. **Risikobasierte Faktoren: Idiosyncratic Volatility (IVOL)**  
   Faktorstrategien, die auf unternehmensspezifischem Risiko beruhen.  
6. **Risikobasierte Faktoren: Stock Beta**  
   Analyse und Nutzung des systematischen Risikos (Betas) im Factor Investing.

---

## 💡 Lernziele

Nach der Lektüre des Buches sind Leserinnen und Leser in der Lage:

- **Faktormodelle theoretisch zu verstehen** und deren Rolle im Asset Management einzuordnen,  
- **Faktorstrategien empirisch zu analysieren und in Python zu implementieren**,  
- **eigene Faktorkonstruktionen und Portfolio-Backtests** mit realen Daten durchzuführen,  

---

## 🧠 Methodik und Python-Umsetzung

Jedes Kapitel kombiniert:
- eine **theoretische Einführung** in den jeweiligen Faktor,  
- eine **praktische Umsetzung in Python**,  
- sowie eine **Fallstudie mit realen Daten**.  

Die verwendeten Python-Bibliotheken sind:
- [`pandas`](https://pandas.pydata.org/) – Datenmanagement  
- [`numpy`](https://numpy.org/) – numerische Berechnungen  
- [`matplotlib`](https://matplotlib.org/) & [`seaborn`](https://seaborn.pydata.org/) – Visualisierungen  
- [`statsmodels`](https://www.statsmodels.org/) – Regressionsanalyse (optional)  

Die Beispiele sind so gestaltet, dass sie mit **öffentlich verfügbaren Datenquellen** (z. B. Yahoo Finance) reproduzierbar sind.

---

## 💻 Verwendung

Das Buch kann in zwei Formaten genutzt werden:

1. **Interaktives Webbuch (Quarto)**  
   → Zum Lesen und Erkunden der Theorie und Python-Fallstudien direkt im Browser.  

2. **Jupyter-Notebooks (`.ipynb`)**  
   → Zum eigenständigen Ausführen, Modifizieren und Erweitern der Beispiele.  

Einfach das Repository klonen oder herunterladen und das jeweilige Kapitel-Notebook öffnen.

---

## 📦 Installation (optional)

Um alle Codebeispiele lokal auszuführen, richte dir eine Python-Umgebung ein:

```bash
conda create -n factorinvest python=3.10
conda activate factorinvest
conda install -c conda-forge pandas numpy matplotlib seaborn statsmodels yfinance


## ⚙️ Technische Voraussetzungen

Um das Webbuch lokal auszuführen oder anzupassen, benötigen Sie:

- Installiertes [Quarto](https://quarto.org/)  
- Python 3.9 oder höher  
- Empfohlene Python-Bibliotheken:

```bash
pip install pandas numpy matplotlib scipy
```

Für den PDF-Export wird ein LaTeX-System benötigt, z. B.:

```bash
quarto install tool tinytex
```

---

## 🚀 Buch rendern

Kopieren oder klonen Sie das Projektverzeichnis auf Ihren Rechner.  
Dann öffnen Sie ein Terminal im Projektordner und führen Sie aus:

```bash
quarto render
```

Das fertige Webbuch wird im Ordner `_book/` erstellt.  
Zur Live-Vorschau im Browser:

```bash
quarto preview
```

---

## 💡 Hinweise zur Nutzung

- Alle Python-Codebeispiele sind modular aufgebaut und können direkt ausgeführt oder angepasst werden.  
- Die im Buch verwendeten Datensätze sind entweder öffentlich verfügbar oder zu Demonstrationszwecken generiert.  
- Das Buch eignet sich gleichermaßen für das **Selbststudium**, **universitäre Lehrveranstaltungen** und **berufliche Weiterbildung**.

---

## 📜 Lizenz

© 2025 Univ.-Prof. Dr. Thomas Mählmann  
**Alle Rechte vorbehalten.**

Dieses Werk einschließlich aller seiner Teile ist urheberrechtlich geschützt.  
Jede Verwertung außerhalb der engen Grenzen des Urheberrechtsgesetzes ist ohne Zustimmung des Autors unzulässig.  
Dies gilt insbesondere für Vervielfältigungen, Übersetzungen, Mikroverfilmungen sowie die Speicherung und Verarbeitung in elektronischen Systemen.  

Die im Buch enthaltenen Python-Beispiele dürfen **für Lehr- und Lernzwecke** verwendet und angepasst werden, sofern keine kommerzielle Nutzung erfolgt.

---

## 📧 Kontakt

**Autor:** Univ.-Prof. Dr. Thomas Mählmann  
**E-Mail:** thomas.maehlmann@ku.de  
**Website (optional):** https://www.ku.de/wfi/lfb/mitarbeitende/prof-dr-thomas-maehlmann

---

Vielen Dank für Ihr Interesse und viel Erfolg beim Lernen und Anwenden der Methoden des quantitativen Portfoliomanagements!
