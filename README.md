# Portfolio: Scientific Data Science & Reliability Engineering
**Auteur:** [A. Schrijvers] | **Expertise:** MSc. Fysische Biologie (drs.) (STEM) & MSc. Wiskunde (ULO 1e graad)

Dit portfolio focust op **Hazard Modelling** en **Anomaliedetectie** in complexe dynamische systemen. Middels stochastische modellen en spectrale analyse breng ik de betrouwbaarheid en faalkansen van systemen in kaart.

---

## Project 1: Predictieve Analyse van Kritieke Systeemuitval (Hazard Modelling)
*Focus: Reliability Engineering & Multivariate Risico-analyse*
*   **Methodiek:** Pearson-correlatie ($\rho$), Verdelingsanalyses (KDE) en Hazard-rate identificatie.
*   **Case Study:** Modellering van de 'Mean Time To Failure' (MTTF) op basis van fysiologische systeemparameters.
*   **Wiskundig Inzicht:** Kwantificering van de invloed van procesvariabelen op de systeemintegriteit.
*   [Bekijk Notebook](./Predictieve_Analyse_Kritieke_Systeemuitval.ipynb)

## Project 2: Spectrale Anomaliedetectie in Dynamische Systemen
*Focus: Fraudedetectie & Systeembewaking*
*   **Methodiek:** Log-Returns, Fourier-transformatie (FFT) en Z-score analyse ($|z| > 3\sigma$).
*   **Case Study:** Detectie van statistische afwijkingen en marktcycli. Dit model is direct toepasbaar op anomaliedetectie binnen het betalingsverkeer of fraudebestrijding.
*   [Bekijk Notebook](./Markt_Anomalie_Fourier_Analyse.ipynb)

---

## Theoretisch Kader: Spectrale Analyse
In beide projecten vormt de Fourier-integraal de basis voor de spectrale validatie:

```math
\hat{f}(\xi) = \int_{-\infty}^{\infty} f(t) e^{-2\pi i t \xi} \,dt




