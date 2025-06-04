Optimizing Scene Classification: A Robust Approach with Transfer Learning and AutoML
📌 Overview
This repository contains the implementation of the research titled "Optimizing scene classification: A robust approach with transfer learning and automated machine learning integration". The project presents a hybrid approach that combines deep transfer learning using MobileNetV2 with automated machine learning (AutoML) using TPOT for scene classification across diverse remote sensing datasets.

The main goal is to improve the accuracy, scalability, and generalization of scene classification models while minimizing manual effort in hyperparameter tuning.

🧠 Key Features

    ✅ Transfer Learning using MobileNetV2 with removed top layers for lightweight and efficient feature extraction.

    ⚙️ AutoML Integration using TPOT for automated pipeline generation and hyperparameter tuning.

    🔍 Data Preprocessing with class distribution analysis and normalization.

    🌍 Multi-Dataset Evaluation on:

        AID (30 classes)

        RESISC45 (45 classes)

        Scene Recognition Dataset (6 classes)

    📊 Achieved 100% test accuracy in controlled settings across all datasets.

🧪 Usage

Step 1: Prepare Datasets
Download and place AID, RESISC45, and Scene Recognition datasets under the data/ directory.

Step 2: Run Transfer Learning

Step 3: Run AutoML with TPOT

📈 Results
Dataset	Accuracy
AID	100%
RESISC45	100%
Scene Recog.	100%

    Achieved under ideal lab conditions using curated high-quality imagery.

📚 Citation

If you use this code or dataset in your research, please cite the original paper:
Hammad, M., Chelloug, S. A., AlShathri, S., & Abd El-Latif, A. A. (2025). Optimizing Scene Classification: A Robust Approach with Transfer Learning and Automated Machine Learning Integration. Journal of Engineering Research.
