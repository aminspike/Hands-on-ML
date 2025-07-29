📘 Chapter 1: The Machine Learning Landscape
🔍 What is Machine Learning?
Machine Learning (ML) is a subfield of Artificial Intelligence that focuses on building systems that can learn from data, identify patterns, and make decisions with minimal human intervention.

Formal definition (Tom Mitchell):
"A computer program is said to learn from experience E with respect to some task T and performance measure P, if its performance at task T, as measured by P, improves with experience E."

🤖 Why Use Machine Learning?
ML is used when:

Explicit programming is hard or impossible (e.g., face recognition).

Rules are hidden in massive, complex datasets.

Systems need to adapt or learn from new data continuously.

Example Applications:

Spam filtering

Product recommendations

Voice assistants

Medical diagnosis

Stock price forecasting

🧭 Categories of Machine Learning Systems
ML systems can be categorized in several ways based on how they learn, operate, or generalize from data:

1. By Learning Type
🔹 Supervised Learning
Learns from labeled data (input + correct output).

Goal: Make predictions on unseen inputs.

Examples:

Classification: Predict categories (e.g., spam or not spam).

Regression: Predict continuous values (e.g., housing prices).

🔹 Unsupervised Learning
Learns from unlabeled data.

Goal: Discover hidden structure in data.

Common techniques:

Clustering (e.g., customer segmentation using K-Means)

Dimensionality Reduction (e.g., PCA for visualization)

🔹 Semi-Supervised Learning
Mix of a small amount of labeled data + a large amount of unlabeled data.

Example: Google Photos might label only some images and still learn to recognize faces.

🔹 Reinforcement Learning
An agent learns by interacting with an environment.

It receives rewards or penalties based on actions.

Used in:

Game-playing agents (like AlphaGo)

Robotics

Autonomous driving

2. By Training Approach
🔹 Batch Learning
The model is trained using the full dataset at once.

Not suitable for real-time updates.

Must retrain from scratch if data changes.

🔹 Online Learning
Learns incrementally from data streams.

Can adapt to new data on the fly.

Suitable for systems that handle continuous input (e.g., financial trading bots).

3. By Generalization Strategy
🔹 Instance-Based Learning
Learns by memorizing training examples.

Makes decisions by comparing new data to known instances.

Example: k-Nearest Neighbors (k-NN)

🔹 Model-Based Learning
Builds a general model from training data.

Learns parameters (like weights) that best fit the data.

Examples: Linear Regression, Decision Trees, Neural Networks

⚠️ Challenges in Machine Learning
Poor-quality data: Garbage in, garbage out.

Overfitting: The model memorizes training data instead of generalizing → bad performance on new data.

Underfitting: The model is too simple to learn patterns in the data.

Data leakage: Model accidentally uses future information.

🛠️ Tools & Libraries Previewed
Scikit-Learn: Ideal for traditional ML tasks like classification and regression.

TensorFlow & Keras: Powerful frameworks for building deep neural networks.

✅ Key Takeaways
ML is about building systems that learn from data to make decisions.

Understanding the types of ML helps you choose the right tool for the job.

Tools like Scikit-Learn, TensorFlow, and Keras make it easier to build intelligent systems.
