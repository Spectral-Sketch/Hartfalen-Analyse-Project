# Portfolio: Data Science & Reliability Engineering
**Auteur:** [A. Schrijvers] | **Expertise:** MSc. Fysische Biologie (drs.) (STEM) & MSc. Wiskunde (1e graad)

Dit portfolio focust op **Hazard Modelling** en **Anomaliedetectie** in complexe dynamische systemen. Middels stochastische modellen en spectrale analyse breng ik de betrouwbaarheid en faalkansen van systemen in kaart.

---

## Project 1: Predictieve Analyse van Kritieke Systeemuitval (Hazard Modelling)
*Focus: Reliability Engineering & Multivariate Risico-analyse*
*   **Methodiek:** Pearson-correlatie ($\rho$), Verdelingsanalyses (KDE) en Hazard-rate identificatie.
*   **Case Study:** Modellering van de 'Mean Time To Failure' (MTTF) op basis van fysiologische systeemparameters.
*   **Wiskundig Inzicht:** Kwantificering van de invloed van procesvariabelen op de systeemintegriteit.
*   [Bekijk Notebook](./Predictieve_Analyse_Kritieke_Systeemuitval.ipynb)



## Project 2: Spectrale Anomaliedetectie & Interactieve Business Intelligence
*Focus: Fraudedetectie, Systeembewaking & Marktmonitoring*
* **Methodiek:** Log-Returns, Fourier-transformatie (FFT), Z-score modellering en **Power BI / DAX integratie**.
* **Case Study:** Detectie van statistische marktafwijkingen vertaald naar een interactief dashboard. Gebruikers kunnen via een dynamische gevoeligheidsslicer zelf de drempelwaarden ($|z| > \sigma$) bepalen, waarbij uitschieters visueel worden gemarkeerd en de KPI-status live verspringt.
* [Bekijk Notebook](./Markt_Anomalie_Fourier_Analyse.ipynb) | **Dashboard-preview hieronder:**
*  
<img width="878" height="496" alt="PowerBI Spectra" src="https://github.com/user-attachments/assets/ca6e2fe7-6361-4714-bf45-07e9fda63135" />

---

## Theoretisch Kader: Spectrale Analyse
In beide projecten vormt de Fourier-integraal de basis voor de spectrale validatie:

```math
\hat{f}(\xi) = \int_{-\infty}^{\infty} f(t) e^{-2\pi i t \xi} \,dt




