# Hi, I'm Tom Ravot 👋

Bachelor's student in **Communication Systems at EPFL** (2024 to present). I'm interested in machine learning and in the computational systems that make it work: how data is represented, how algorithms are structured, and how that affects performance and reliability.

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white" alt="LaTeX">
</p>

## Projects

Three team projects and one personal project, all built during my Bachelor's at EPFL.

### [Gaming Addiction Prediction: Machine Learning from Scratch](https://github.com/travot/gaming-addiction-ml)
*CS-233 Introduction to Machine Learning · team of 3 · 2026*

Predicting gaming addiction level and score from behavioural data, with every method written in NumPy (no ML libraries): linear and logistic regression, k-NN, a multi-layer perceptron (backpropagation, Adam, dropout, L2) and K-Means. We tackled severe class imbalance with class-weighted losses, ANOVA F-score feature selection and oversampling, and reached **86.5% accuracy and 0.843 macro-F1** with the MLP.

**Tech:** Python · NumPy · Matplotlib · LaTeX

### [Optimal Trade Execution: the Almgren-Chriss Model, Tested on Market Data](https://github.com/travot/optimal-trade-execution)
*Personal project · 2026*

A Python implementation of the Almgren-Chriss framework for liquidating a large order, together with the tools to test its assumptions on real data: closed-form optimal schedule and efficient frontier, Monte Carlo verification, calibration of market impact and volatility from 1-minute bars, and a GARCH(1,1) volatility forecaster written from scratch. Run on 132,480 Binance BTCUSDT 1-minute bars (July to September 2026), it shows that **impact is concave** (exponent about 0.75, not the linear 1 the model assumes) and that **volatility varies by a factor of about 7** over the day. Out of sample, GARCH beats EWMA, and both beat a constant (QLIKE 0.29, 0.38, 0.52). With the model's schedule, the standard deviation of the shortfall drops from **21.4 to 17.3 bps** at the same mean cost. Closed-form results match 200,000-path Monte Carlo simulations (z-scores within ±1.6), and every formula is checked against independent implementations in automated tests.

**Tech:** Python · NumPy · Matplotlib · pytest

### [ReCHor: Public Transport Journey Planner](https://github.com/travot/ReCHor-journey-planner)
*CS-108 Practice of Object-Oriented Programming · team of 2 · spring 2025*

A Java/JavaFX journey planner on the real Swiss timetable (about 33,000 stations and 2.7 million connections per day). It uses a profile-based connection-scan algorithm that returns Pareto-optimal itineraries, with memory-mapped binary data access and bit-packed 64-bit criteria to limit memory use, plus calendar and map export. 130+ unit tests. Full commit history in the [original repository](https://github.com/FireII/ReCHor).

**Tech:** Java 21 · JavaFX · JUnit

### [ICoop: Two-Player Cooperative Game](https://github.com/travot/ICoop-cooperative-game)
*CS-107 Introduction to Programming · team of 2 · autumn 2024*

A top-down action-puzzle game for two players on one keyboard, with a fire hero and a water hero who must cooperate to escape. Built on the course's game engine, with interactions designed around the Visitor pattern, enemies with simple AI, and levels defined from images. Developed on EPFL's internal Git platform, which is why this account shows no activity for that semester.

**Tech:** Java 21 · Object-oriented design

## Skills

- **Languages:** Python, Java, C
- **Machine learning:** regression, classification, k-NN, neural networks, clustering, handling class imbalance, cross-validation
- **Quantitative methods:** Monte Carlo simulation, time-series volatility models (GARCH, EWMA), model calibration and validation
- **Software:** object-oriented design, algorithms and data structures, JUnit, pytest, Git
- **Tools:** NumPy, Matplotlib, Jupyter, LaTeX, Linux

## Contact

- Email: tom.ravot@epfl.ch
- Phone: +33 7 89 57 31 59
