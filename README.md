# Personal Portfolio

My personal portfolio site — built from scratch with pure HTML, CSS, and inline SVG. No frameworks, no build tools, just code.

🔗 **[coachellaaaas.github.io/portfolio](https://coachellaaaas.github.io/portfolio/)**

---

## About

I'm Piyathida Suwannakat (Coach), an MSc Financial Mathematics student at Queen Mary University of London (Sep 2026 – Sep 2027) and a Computer Science & Artificial Intelligence graduate from the University of Sussex (BSc, 2:1). This portfolio showcases my work in machine learning, data science, quantitative finance, and scientific software — from spiking neural networks on GPU to financial sentiment signals and interactive data dashboards.

I'm targeting roles in **financial markets** across data science, machine learning, and quantitative finance in the UK, and I'm open to both internships and full-time positions. Visa sponsorship not required.

---

## Projects

### Transfer Learning with Spiking Neural Networks *(BSc Thesis)*
SNN-based recognition system on the Omniglot dataset (1,623 characters, 50 alphabets), outperforming a CNN baseline by 35% accuracy while using 40% less training data. Built with GeNN and EventProp for spike-timing-based gradient computation.

### Shock to a Company's Equities & Derivatives *(MSc Group Project, QMUL · Team Leader · in progress)*
**Research question:** How did Exxon Mobil's stock returns and implied volatility respond to escalation and de-escalation events in the 2026 Strait of Hormuz crisis?

- As a multinational oil and gas producer, Exxon's revenue is closely tied to the oil price, which surged when the conflict closed the Strait.
- Using Bloomberg data, we measure Exxon's abnormal returns and changes in its implied volatility surface around each event, and test whether markets reacted differently to escalation than to de-escalation.
- We also build a C++ program that prices European calls under Black–Scholes and computes implied volatility by bisection.

Peer Assessment Learning (PAL) project combining all four first-semester modules, worth 40% of each module.

### FinSignal — Financial Sentiment & Market Signal
End-to-end NLP pipeline classifying financial news sentiment with TF-IDF and FinBERT, tested against next-day returns for 5 large-cap stocks with a market-neutral long-short backtest and forward-shifted returns to avoid look-ahead bias. 75.4% accuracy · 68.3% macro-F1 · Sharpe ~0.3–0.6.

→ [Go to Repository](https://github.com/coachellaaaas/FinSignal)

### UNESCO Heritage Atlas *(Personal Project)*
Exploratory analysis of 1,248 UNESCO World Heritage Sites across 171 countries, with an interactive dashboard featuring a world map, Plotly charts, and a searchable site browser.

→ [View Dashboard](https://coachellaaaas.github.io/unesco_heritage_analysis/)

### Facial Recognition Pipeline *(Data Science Intern, OESON)*
CNN classifier in TensorFlow reaching 82% accuracy on 50,000+ labelled images, with end-to-end preprocessing and augmentation pipelines, validated with t-tests and ANOVA.

### pocketTHERM *(Research Software, University of Sussex · RAEng-funded)*
Browser-based thermal energy system design tool used by UK engineers. Translated from MATLAB to Python and shipped 10,000+ lines via PyScript; acknowledged in a peer-reviewed publication.

---

## Leadership & Activities

- **Team Captain** — Bloomberg Global Trading Challenge 2026
- **Team Leader** — Peer Assessment Learning project, QMUL: Exxon Mobil's equity and implied-volatility response to the 2026 Strait of Hormuz crisis 
- **Staff Member** — QMUL Quant Society
- **Member** — Queen Mary Banking & Finance Society

---

## Stack

**Languages:** Python · SQL · C++ · JavaScript · HTML/CSS 

**ML / Data:** TensorFlow · PyTorch · scikit-learn · NumPy · Pandas · SciPy

**Viz & Tools:** Matplotlib · Seaborn · Tableau · Power BI · Jupyter · Git/GitHub · Excel

**Specialised:** GeNN (pygenn & mlgenn) · EventProp · Spiking Neural Networks

---

## How it's built

The site is a single `index.html` file — no React, no build step, no dependencies. It's deployed on GitHub Pages straight from the `main` branch.

The design is themed as an **engineering blueprint**: each section is a drawing "sheet" ([A] Projects, [B] Experience, [C] Skills, [D] Education, [E] Contact), projects are presented as technical drawings with specification tables, and a title block summarises status and location.

- **Colour scheme:** Graphite — charcoal background, light grey line work, and an orange accent, on a CSS grid-paper background
- **Typography:** `Chakra Petch` for headings and body, `Share Tech Mono` for labels, tables, and annotations
- **Graphics:** hand-built inline SVG — an isometric hero drawing, an event-study chart, a return-curve plot, a wireframe globe, a face-landmark detection sketch, and a temperature–entropy cycle diagram
- **Animation:** the thesis figure is an animated spiking neural network built with SVG `<animate>` (pulsing neurons and travelling spikes); a few lines of vanilla JS pause it for visitors who prefer reduced motion
- **Responsive:** flexible grid and flex layouts that stack cleanly on mobile

---

## Structure

```
portfolio/
├── index.html                      ← the whole site
└── README.md
```

---

## Contact

[psuwannakat.work@gmail.com](mailto:psuwannakat.work@gmail.com) · [LinkedIn](https://www.linkedin.com/in/piyathida-suwannakat) · [GitHub](https://github.com/coachellaaaas)
