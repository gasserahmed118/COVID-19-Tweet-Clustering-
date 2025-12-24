🧠 COVID-19 Tweet Clustering using KMeans & GSDMM

📌 Overview

This project performs unsupervised clustering on COVID-19 related tweets using two different approaches:
   1. KMeans (feature-based clustering)
   2. GSDMM (text-based clustering for short documents)

The goal is to compare how traditional numerical features perform against probabilistic topic modeling for short text.

🎯 Objectives
    1. Cluster tweets based on writing style and symbols
    2. Apply topic modeling for short text using GSDMM
    3. Compare clustering behavior and interpretability
    4. Visualize cluster structure and distributions

📂 Dataset
  1. Source: COVID-19 Tweets
  2. Column used: OriginalTweet
  3. Dataset is sub-sampled for efficiency

🧩 Feature Engineering (KMeans)
    1. Character count
    2. Word count
    3. Special characters frequency (! @ # $ % ^ & * ;)

🔷 Models Used
   | Model  | Description                   |
   | ------ | ----------------------------- |
   | KMeans | Distance-based clustering     |
   | GSDMM  | Topic modeling for short text |

📊 Visualizations
   1. Elbow Method (SSD)
   2. Cluster size distribution
   3. KMeans centroid analysis
   4. GSDMM topic keywords
   5. Document distribution per cluster

📈 Key Findings
  1. KMeans clusters tweets by structure and punctuation
  2. GSDMM clusters tweets by semantic themes
  3. GSDMM provides more interpretable clusters for short text
  4. Feature scaling significantly improves KMeans performance

🛠 Technologies
   1. Python
   2. Pandas / NumPy
   3. Scikit-learn
   4. SpaCy
   5. Gensim
   6. Matplotlib / Seaborn

👤 Author

Gasser Ahmed
Machine Learning & NLP Enthusiast
   

    

