# 🛒 Egyptian Grocery Market Basket Analysis (Association Rules)

This project performs **Market Basket Analysis** on Egyptian grocery transaction data using the **Apriori algorithm** and **association rule mining**. It visualizes the strongest rules using Arabic labels in both bar charts and network graphs.

## 📊 Project Overview

- Extract frequent itemsets using the Apriori algorithm.
- Generate association rules with key metrics: **support**, **confidence**, **lift**, etc.
- Filter and classify rules into **strong** and **weak** based on confidence and lift thresholds.
- Visualize the top 20 strongest rules:
  - 🟨 Bar Chart based on Lift
  - 🕸️ Directed Network Graph showing item relationships


## 🧠 Techniques Used

- **Apriori Algorithm** for discovering frequent itemsets.
- **Association Rule Mining** via `mlxtend`.
- **Arabic Text Handling**:
  - `arabic_reshaper` for reshaping Arabic words.
  - `python-bidi` for proper right-to-left display in visualizations.

## 🛠️ Libraries Used

```python
pandas, numpy, matplotlib, seaborn
mlxtend.frequent_patterns
networkx
arabic_reshaper
bidi.algorithm
```
</br>

📈 Visualizations

🔹 Network Graph

![Top20_Lift_NetworkGraph_WithLabels](https://github.com/user-attachments/assets/2047120a-6606-4872-90f2-40f7b018cb65)

🔹 Top 20 Rules by Lift (Bar Chart)

![Capture1](https://github.com/user-attachments/assets/094a2669-fb88-45d8-8296-eba9241d90f8)

