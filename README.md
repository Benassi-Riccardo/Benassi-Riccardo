# Hi, I'm Riccardo 👋

Data scientist in training, based in Milan. I work on the full path from raw data to a model people can use:
cleaning and validating data, building and evaluating models honestly, and shipping them.

- 🎓 MSc in **Data Analytics for Business**, Università Cattolica, Milan (2025 – 2028)
- 🎓 BSc in **Economics, Management and Computer Science** (BEMACS), Bocconi University (2020 – 2025)
- 🎯 Looking for **data analyst, data scientist and ML** roles

## Featured projects

### [Reddit sentiment analysis](https://github.com/Benassi-Riccardo/ML-Sentiment-Analysis-on-Reddit-user-s-Data) · end-to-end ML pipeline

3-class NLP classifier (TF-IDF + logistic regression, VADER weak labels) with MLflow tracking, served through FastAPI
in Docker and deployed to Render with GitHub Actions. Found train/test leakage from 96% duplicate rows that inflated
accuracy to 99.9%: after deduplication the model reaches 62% against a 48% baseline, and a 195-post human-labelled
audit showed that label quality, not the model, was the bottleneck.

### [Quadra](https://github.com/Benassi-Riccardo/quadra-showcase) · personal finance analytics app · [live](https://quadra-conti.vercel.app)

Budgeting and net-worth app for the Italian market: monthly KPIs and savings rate, year-over-year analysis, category
heatmaps and a cash-flow forecast, on a PostgreSQL data model. Bank statements (PDF, CSV, Excel) are parsed in the
browser and personal identifiers removed before any data is stored. I owned the product and the data model and
directed AI coding agents for the implementation.

### Image classification with CNNs · MSc project, in progress

Training and comparing image classifiers, with VGG as the baseline and ResNet as the challenger.

## Skills

- **Data and ML:** Python (scikit-learn, NLTK), R, SQL · classification, regression, NLP, time series, statistical
  modelling, deep learning (VGG, ResNet)
- **MLOps:** MLflow, FastAPI, Docker, GitHub Actions, Git
- **Also:** PostgreSQL, TypeScript, React, Excel and Google Sheets, AI coding agents (Claude Code)

## Contact

[LinkedIn](https://www.linkedin.com/in/riccardo-benassi-5a444a446) · Italian (native) · English (C1, IELTS 8.0) ·
Spanish (B1)
