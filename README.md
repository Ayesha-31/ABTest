# A/B Testing for Website Conversion Optimization

This project simulates and analyzes an A/B test comparing the conversion rates between two website variants (Group A and Group B) to determine if the new variant leads to a statistically significant improvement.

---

## Problem Statement

We aim to test whether changing a web element (e.g., button color, layout) results in a higher conversion rate. Group A is the control group with a 10% conversion rate, and Group B is the variant with a 13% conversion rate.

---

## 🛠️ Tools & Technologies

- Python
- Pandas & NumPy
- Statsmodels (for Z-test)
- Matplotlib (for visualization)

---

## Dataset

We simulate 1,000 user conversions for each group using a binomial distribution:

```python
group_A = np.random.binomial(1, p=0.10, size=1000)
group_B = np.random.binomial(1, p=0.13, size=1000)
```

---

## 📈 Results

### Conversion Rates

- Group A: **10.0%**
- Group B: **13.1%**

### Statistical Test

- **Z-statistic:** -2.17
- **P-value:** 0.0301

✔️ The difference is statistically significant (p < 0.05), suggesting that Variant B performs better than the control group.

---

## Visualization

<img width="647" height="432" alt="image" src="https://github.com/user-attachments/assets/7616e7a5-3d44-4349-9809-0e4e125fb05d" />


---

## Conclusion

Switching to Variant B could yield a ~30% lift in conversions. This test demonstrates the importance of data-driven decision-making in optimizing user experience and business metrics.

---

## Author

**Ayesha Tabassum Shaik**  
📧 ayesha31tabassum@gmail.com  
[GitHub](https://github.com/ayesha-31) | [LinkedIn](https://www.linkedin.com/in/shaik-ayesha/)
