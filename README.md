# home_assignment2

Question 2:
CNN Feature Extraction with Filters and Pooling
This project demonstrates two fundamental operations in Convolutional Neural Networks (CNNs):
Edge Detection Using Sobel Filters (OpenCV & NumPy)
Applies Sobel filters (Sobel-X and Sobel-Y) to detect edges in a grayscale image.
Uses a built-in sample image from scikit-image (no external file required).
Displays the original image alongside the edge-detected results.
Max Pooling & Average Pooling (TensorFlow/Keras)
Generates a random 4×4 matrix as input.
Applies 2×2 Max Pooling and 2×2 Average Pooling with a stride of 2.
Prints the original matrix, max-pooled output, and average-pooled output.
Key Concepts Demonstrated:
✔ Sobel Filtering (Horizontal & Vertical Edge Detection)
✔ Convolution Operations
✔ Pooling Layers (Dimensionality Reduction)
✔ TensorFlow/Keras for Deep Learning Operations

Qestion3:
Data Preprocessing: Standardization vs. Normalization
This task demonstrates the impact of data scaling on machine learning models by comparing:
Min-Max Normalization – Scales features to a fixed range (e.g., [0, 1])
Z-score Standardization – Centers data around 0 with unit variance (mean=0, std=1)

Key Steps:
✔ Load the Iris dataset and split into train/test sets
✔ Apply MinMaxScaler and StandardScaler
✔ Visualize distributions before/after scaling using histograms
✔ Train a Logistic Regression model and compare accuracy

Results & Insights:
Standardization often performs better for algorithms assuming Gaussian-like data (e.g., SVM, PCA).
Normalization is useful for bounded data (e.g., images) or neural networks with sigmoid/tanh activations.
Scaled data generally improves model performance over raw features.
When to Use:
Standardization: Distance-based algorithms (k-NN, k-means), models sensitive to feature scales.
Normalization: Neural networks, pixel data, or when preserving exact value ranges matters.
