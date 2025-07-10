# Linear and Poly model's Likelyhood

# Analisi bayesiana di modelli probabilistici - Esercizio 7

Questo repository contiene il notebook `S3E7_MML.ipynb`, che svolge un esercizio sull’uso del formalismo bayesiano per il confronto tra modelli probabilistici di complessità diversa.

## Descrizione

Il notebook affronta i seguenti punti:

1. **Definizione teorica**: 
   - Calcolo della log-verosimiglianza marginale (*log-evidenza*) sfruttando l’approssimazione di Laplace.
   - Discussione del termine di penalizzazione della complessità (principio del Rasoio di Occam).

2. **Generazione dati sintetici**: 
   - Dati generati da un modello lineare con rumore gaussiano.

3. **Confronto tra modelli**:
   - Modello lineare \( M_1 \): \( y = 	heta_0 + 	heta_1 x \)
   - Modello polinomiale di quinto grado \( M_2 \): \( y = \sum_{k=0}^5 	heta_k x^k \)

4. **Analisi evidenza**:
   - Calcolo e rappresentazione grafica dell’andamento dell’evidenza al crescere della numerosità campionaria \( N \).
   - Identificazione della *regione di Occam* \( N^* \), dove il modello più semplice \( M_1 \) risulta preferibile.

5. **Effetto delle prior**:
   - Discussione su come la scelta di una prior sparsa (es. distribuzione di Laplace) influisce sul confronto tra i modelli.

## Requisiti

- Python 3.x
- Librerie principali:
  - `numpy`
  - `matplotlib`
  - `scipy`

## Esecuzione

Per riprodurre l’analisi:

1. Clonare il repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Installare le dipendenze (opzionale):
   ```bash
   pip install numpy matplotlib scipy
   ```

3. Aprire il notebook:
   ```bash
   jupyter notebook S3E7_MML.ipynb
   ```

## Autore

- Neri Lorenzo — Matricola: 2088285
