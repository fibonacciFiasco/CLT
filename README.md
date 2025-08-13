# Central Limit Theorem Visualization - Binomial Distribution

This project demonstrates the **Central Limit Theorem (CLT)** using a **Binomial distribution** and animated histograms.  
It shows how the distribution of sample means approaches a normal distribution as the sample size increases.

---

## 📌 Features
- Interactive **Matplotlib animation** showing the CLT in action.
- Multiple sample sizes compared in real-time.
- Overlay of the theoretical normal distribution for comparison.
- Clean and modular code using NumPy, SciPy, and Matplotlib.

---

## 🖼 Preview
![CLT Animation](clt_binomial.gif)  
*(Generated using the script — save as GIF with `ani.save("clt_binomial.gif", writer='imagemagick')`.)*

---
📚 Theory: Central Limit Theorem
The Central Limit Theorem states that, for a large enough sample size, the distribution of sample means will approximate a normal distribution — regardless of the population's original distribution — as long as samples are independent and identically distributed.

In this project:
Population: Binomial distribution (n_trials = 10, p = 0.5)
Sample sizes tested: 5, 10, 30, 100, 500
Comparison: Theoretical normal curve is plotted alongside histograms.
