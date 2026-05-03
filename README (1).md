# Non-IIDS: Intelligent Intrusion Detection System (Non-IIDS)

## Overview
Non-IIDS is a machine learning-driven intrusion detection framework designed to identify malicious activities in network environments. The system leverages advanced data preprocessing, feature engineering, and classification techniques to improve detection accuracy and reduce false positives.

This repository contains the implementation, experimental setup, and evaluation of the proposed model.

---

## Key Features
- Hybrid machine learning-based intrusion detection
- Efficient feature selection and dimensionality reduction
- High detection accuracy with reduced false alarm rate
- Modular and extensible architecture
- Supports benchmark datasets for evaluation

---

## Methodology
The proposed system follows a structured pipeline:

1. **Data Preprocessing**
   - Noise removal
   - Missing value handling
   - Normalization

2. **Feature Engineering**
   - Feature extraction
   - Feature selection using optimization techniques

3. **Model Development**
   - Training using supervised learning algorithms
   - Hyperparameter tuning

4. **Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC

---

## Project Structure
```
Non-IIDS/
│── data/                  # Dataset files
│── notebooks/            # Jupyter notebooks
│── src/                  # Source code
│── models/               # Saved models
│── results/              # Experimental results
│── README.md             # Project documentation
```

---

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/Non-IIDS.git
cd Non-IIDS
pip install -r requirements.txt
```

---

## Usage
Run the Jupyter Notebook:

```bash
jupyter notebook Non_IIDS.ipynb
```

Or execute the main script:

```bash
python main.py
```

---

## Results
The model demonstrates improved intrusion detection performance compared to baseline models, achieving:
- High classification accuracy
- Reduced false positives
- Robust performance across datasets

---

## Future Work
- Integration with deep learning architectures
- Real-time intrusion detection deployment
- Federated learning for distributed environments

---

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License.

---

## Author

Sudhakar Sengan

---

## Citation
If you use this work in your research, please cite:

```
@article{non_iids2026,
  title={Non-IIDS: Intelligent Intrusion Detection Framework},
  author={Sengan, Sudhakar},
  year={2026}
}
```
