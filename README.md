
# Optimal Window Identification for Important Citation Classification

## Project Purpose
This project aims to identify the **optimal window size** for classifying important citations in research papers. By determining the best window size, we can enhance the accuracy and efficiency of citation importance detection, which plays a crucial role in understanding the significance of references in academic writing.

## Datasets Used
We utilized two benchmark state-of-the-art datasets for this task:

1. **SciCite**
2. **ACL-ARC**

These datasets are widely recognized for citation analysis and provide a robust basis for evaluating our models.

## Methodology
We employed various machine learning and deep learning classification models to analyze the performance at different window sizes. The models included:

- **Machine Learning Models**
- **Deep Learning Models** (e.g., CNN, LSTM, GRU)

The evaluation focused on identifying the window size that produces the most accurate and reliable results.

## Results
Our experiments revealed that:

- At a window size of **10**, the models achieved optimal performance.
- The results demonstrate the significance of selecting an appropriate window size to maximize classification accuracy.

## Conclusion
This project highlights the importance of parameter tuning in citation classification tasks. The findings can guide future research and applications in citation analysis and related areas.

---

### Repository Structure

- `data/`: Contains preprocessed datasets.
- `models/`: Includes the implemented machine learning and deep learning models.
- `results/`: Stores the results and evaluation metrics for different window sizes.
- `scripts/`: Code for training and evaluating models.

---

### How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/optimal-window-citation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run experiments:
   ```bash
   python train_model.py --window_size <window_size>
   ```
4. Check results in the `results/` folder.

---

### Acknowledgments
This project uses data from **SciCite** and **ACL-ARC** datasets. Special thanks to the research community for providing these valuable resources.
