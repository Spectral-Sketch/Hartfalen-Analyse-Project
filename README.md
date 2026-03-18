# Scientific Data Science Portfolio: Wiskundige Modellering & Signaalverwerking
**Auteur:** [A. Schrijvers] | **Expertise:** drs. Fysische Biologie (STEM)& 1e graads Wiskunde 

Dit portfolio demonstreert de toepassing van **Complexe Analyse** en **Stochastiek** op diverse domeinen. De focus ligt op het scheiden van signaal en ruis in complexe systemen.

---

## Project 1: Klinische Statistiek & Hartfalen (Medische Sector)
*Focus: Medische Biometrie & Risicopredictie*
*   **Methodiek:** Pearson-correlatie ($\rho$), Verdelingsanalyses (KDE) en IIR Notch Filtering.
*   **Resultaat:** Identificatie van kritieke fysiologische parameters en spectrale zuivering van ECG-data (50Hz ruis-eliminatie).
*   [Bekijk Notebook](./Hartfalen_Analyse_Spectraal_Model.ipynb)

## Project 2: Anomaliedetectie in Financiële Tijdreeksen (Bancair/Overheid)
*Focus: Fraudedetectie & Risicomanagement*
*   **Methodiek:** Log-Returns, Fourier-transformatie (FFT) en Z-score analyse ($|z| > 3\sigma$).
*   **Resultaat:** Detectie van statistische anomalieën en marktcycli in de S&P 500 index. Dit model is direct schaalbaar naar fraudedetectie-systemen.
*   [Bekijk Notebook](./Markt_Anomalie_Fourier_Analyse.ipynb)

---

## Wiskundig Fundament

In beide projecten vormt de Fourier-integraal de basis voor de spectrale analyse:

```math
\hat{f}(\xi) = \int_{-\infty}^{\infty} f(t) e^{-2\pi i t \xi} \,dt



