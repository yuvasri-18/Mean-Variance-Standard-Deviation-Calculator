# 📊 Mean-Variance-Standard Deviation Calculator
It involves creating a function that calculates statistical values (mean, variance, standard deviation, min, max, and sum) of a 3x3 matrix using NumPy.
## 🧠 Project Objective
To build a function `calculate()` that:
- Accepts a list of 9 numerical values
- Converts the list into a 3x3 NumPy array
- Calculates the mean, variance, standard deviation, max, min, and sum across:
  - Columns (axis 0)
  - Rows (axis 1)
  - Flattened matrix
## 🛠️ Technologies Used
- Python 3
- NumPy library
## 📥 Input & 📤 Output
### ✅ Valid Input
calculate([0,1,2,3,4,5,6,7,8])
🔄 Output
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  'standard deviation': [[2.449..., 2.449..., 2.449...], [0.816..., 0.816..., 0.816...], 2.581...],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}
❌ Invalid Input
calculate([1, 2, 3])
ValueError: List must contain nine numbers.
📂 Project Structure
├── mean_var_std.py   # Main Python function
└── README.md         # Project documentation
🙋‍♂️ Acknowledgments
Thanks to freeCodeCamp for the project idea and learning path.
