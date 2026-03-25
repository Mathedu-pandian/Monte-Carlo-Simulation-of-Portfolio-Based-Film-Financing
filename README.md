# Monte-Carlo-Simulation-of-Portfolio-Based-Film-Financing
This project models film investments using Monte Carlo simulation to compare single-film investments with diversified portfolios. It demonstrates how portfolio diversification reduces risk and how improved selection mechanisms significantly enhance expected returns and minimize downside probability.

# 🎬 Film Portfolio Simulation (Monte Carlo)

This project applies Monte Carlo simulation to analyze risk and return in film investment strategies.

## 📊 Objective
To compare:
- Single film investment
- Portfolio of films
- Portfolio with improved selection (filtered)

## ⚙️ Methodology
- Each film has a probability of success (p)
- Success returns 8x, failure returns 0.5x
- Simulated 10,000 scenarios

## 📈 Key Results
- Single film: ~90% chance of loss
- Portfolio (random): ~35–40% loss probability
- Portfolio (filtered): ~2–5% loss probability

## 🧠 Key Insight
Diversification reduces risk, while improved selection increases returns.
Combining both transforms film investment into a structured asset class.

## 🛠️ Technologies Used
- Python
- NumPy
- Matplotlib

## 🚀 How to Run

```bash
pip install numpy matplotlib
python simulation.py
