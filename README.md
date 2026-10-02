# Ram Iyer

**Data science and AI** · BITS Pilani (M.Sc. Physics, B.E. Mechanical, Minor in Finance) · Pune, India

I work on data problems that begin with a business question and end with a number someone can act on. Each project below is tested on data it has not seen, deployed as a live app, and documented with its limitations as well as its results.

[LinkedIn](https://www.linkedin.com/in/iyer-ram/)

---

## Featured projects

### [IPL Chase Win Probability](https://github.com/iyerbrah/ipl-chase-win-probability)

Ball-by-ball win probability for every IPL run chase from 2008 to 2026, with a leverage score that identifies the moments of a match that carry the most tension.

- **82% accuracy** on two held-out seasons, against a 56% baseline.
- Logistic regression matched a neural network and outperformed LightGBM.
- The top 10% of over-breaks hold 29% of all leverage, which is where ad inventory is most valuable.

`Python` `scikit-learn` `LightGBM` `Plotly` `Streamlit` · [Live app](https://ipl-win-probability-rxgwz3kbdl6nwuk3rmyjwe.streamlit.app/)

### [Personalisation Lift](https://github.com/iyerbrah/personalisation-lift)

Measures the value of a video recommender using a randomised experiment on 1.36 million video impressions across 27,024 users (KuaiRand).

- Recommended videos earned long views **4.6 times as often** as random ones (36.3% against 7.9%).
- About three quarters of the gain comes from matching videos to the individual user, and one quarter from popularity.
- The lift holds across every user segment, between 4.1x and 4.7x.

`Python` `pandas` `NumPy` `Plotly` `Streamlit` · [Live app](https://personalisation-lift-dkvysrjbxfpijjzcnot9ju.streamlit.app/)

### [Ask The Olist Data](https://github.com/iyerbrah/ask-the-olist-data) 

A natural-language interface to a retail database, paired with a 60-question benchmark that measures how often its answers are correct.

- Accuracy rose from **83% to 98%** when the model was given written notes on what the data means.
- No other change that was tested made a measurable difference.
- Every generated query is checked to be read-only before it runs.

`Python` `SQL` `DuckDB` `sqlglot` `Altair` `Streamlit` · [Live app](https://text-to-sql-scorecard-xgu4cnfjvj5qghjrasbdkh.streamlit.app/)

---

## Skills

| Area | Tools and methods |
|---|---|
| Languages | Python, SQL |
| Data analysis | pandas, NumPy, DuckDB |
| Machine learning | scikit-learn, LightGBM, model evaluation and calibration |
| Experimentation | Randomised experiment analysis, segment analysis, benchmarking |
| Visualisation and apps | Plotly, Altair, Streamlit |
