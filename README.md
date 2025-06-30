# 📊 Mean-Variance-Standard Deviation Calculator

This is a simple Python project built as part of the **freeCodeCamp Data Analysis with Python Certification**.

The program takes a list of 9 numbers, converts it into a 3x3 matrix using **NumPy**, and returns a dictionary containing the:

- Mean
- Variance
- Standard Deviation
- Max
- Min
- Sum

for each **row**, **column**, and the **flattened matrix**.

---

## 🧠 Example

```python
calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  'standard deviation': [[2.449..., 2.449..., 2.449...], [0.816..., 0.816..., 0.816...], 2.581...],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```
🛠️ Technologies Used
Python 3

NumPy

Gitpod (Cloud IDE)

Git & GitHub

🧪 Testing
The project includes test cases in test_module.py, and they are automatically run via main.py.


📬 Author

*Likitha Bhaskar*

This project is part of the freeCodeCamp curriculum.

