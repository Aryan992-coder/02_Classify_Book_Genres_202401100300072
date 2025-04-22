# 02_Classify_Book_Genres_202401100300072
Book Genre Classification Using Metadata
📘 Project Overview

This project aims to classify books into genres based on metadata features such as:

    Author popularity

    Book length

    Number of associated keywords

We use a Random Forest Classifier to perform multi-class classification and evaluate the model using standard metrics.
📁 Dataset

The dataset book_genres.csv contains the following columns:

    author_popularity: A numeric score representing the author's popularity

    book_length: The number of pages or total word count

    num_keywords: Number of descriptive keywords associated with the book

    genre: The target label (e.g., mystery, fiction, fantasy, non-fiction)

🧠 Methodology

    Load and explore the dataset

    Split the data into training and test sets (80/20)

    Train a Random Forest Classifier

    Evaluate using:

        Accuracy

        Precision

        Recall

        Confusion Matrix

    Visualize results using heatmaps

🧾 Results

    Accuracy: 50%

    Precision (weighted): 57.9%

    Recall (weighted): 50%

    Best performance: Fiction (100% accuracy on test set)

📌 Requirements

    Python 3.x

    pandas

    scikit-learn

    matplotlib

    seaborn

Install dependencies:
pip install pandas scikit-learn matplotlib seaborn
🚀 How to Run
python genre_classification.py

Make sure book_genres.csv is in the same directory.
📸 Output

    Text-based classification report

    Confusion matrix heatmap for visual evaluation

📚 Credits

    Dataset provided as part of assignment work

    Developed using open-source Python libraries

✍️ Author

Name: Aryan Tomar
Roll No: 202401100300072
Course: B.Tech-CSE(AI)
