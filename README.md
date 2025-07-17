# 🩺 Medical Data Visualizer

This project is part of the **Data Analysis with Python** certification from [FreeCodeCamp](https://www.freecodecamp.org/learn).

It visualizes and analyzes a dataset of medical examination records to explore the relationship between lifestyle choices and cardiovascular disease.

---

## 📊 Features

1. **Categorical Plot**  
   Visualizes counts of good/bad cholesterol, glucose, smoking, alcohol use, activity, and overweight status split by heart disease presence.

2. **Heatmap**  
   Displays the correlation matrix for medical and physical features after cleaning outliers.

---

## 📂 Files

| File                        | Description                                 |
|-----------------------------|---------------------------------------------|
| `medical_data_visualizer.py` | Contains all logic for plotting and data prep |
| `main.py`                  | Runs and saves both visualizations as PNG   |
| `test_module.py`           | Unit tests provided by FreeCodeCamp         |
| `medical_examination.csv`  | Dataset of patient medical records          |

---

## 🧪 Running Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/medical-data-visualizer.git
   cd medical-data-visualizer
   ```

2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn numpy
   ```

3. Run the main script:

   ```bash
   python main.py
   ```

4. Run the tests:

   ```bash
   python test_module.py
   ```

---

## ✅ Example Output

### Categorical Plot
![Catplot Example](catplot.png)

### Heatmap
![Heatmap Example](heatmap.png)

---

## 🔗 FreeCodeCamp Submission

Project Link: [Submit this GitHub repo URL on FreeCodeCamp](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer)

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
