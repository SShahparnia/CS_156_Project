# Human Activity Recognition (HARTH Dataset)

This project analyzes human activity using the HARTH dataset, which contains motion data from wearable accelerometers. The dataset includes labeled activity data from 22 subjects performing daily actions such as walking, sitting, cycling, and more. Our goal was to preprocess the data, extract features, and train machine learning models to predict the type of activity being performed.

## Repository Structure

```
demo1/                  # Dataset overview and background
  └── AI demo 1.pdf

demo2/                  # Preprocessing, segmentation, and feature extraction
  ├── demo2.ipynb
  └── Copy of AI demo 2.pdf

demo3/                  # Model training and evaluation
  ├── demo3.ipynb
  ├── demo3presentation.pdf
  ├── overall_feature_averages.csv
  └── subject_feature_statistics.csv
```

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Run the notebooks:**

   - Open `demo2/demo2.ipynb` to perform preprocessing, segmentation, and feature extraction.
   - Open `demo3/demo3.ipynb` to train models and evaluate performance (10-fold CV and LOSO).

## Dataset Information

The HARTH dataset was created and annotated by NTNU and includes motion sensor recordings for various human activities. Two 3-axial accelerometers were placed on the lower back and right thigh of each subject.

**Reference:**

> Logacjov, A., Bach, K., Kongsvold, A., Bårdstu, H., & Mork, P. (2021).  
> *HARTH: A Human Activity Recognition Dataset for Machine Learning*. Italian National Conference on Sensors

---
