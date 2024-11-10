This project showcases the use of three algorithms—K-means clustering, Discrete Cosine Transform (DCT), and Principal Component Analysis (PCA)—for image compression, with a comparative analysis of their performance. Implemented in a Jupyter Notebook, it offers an interactive platform for both image compression and time complexity evaluation.

## Project Overview
### Algorithms Implemented
**K-means Clustering**: Used to compress images by reducing the number of colors, effectively clustering similar colors and replacing them with the cluster centroid.
**Discrete Cosine Transform (DCT)**: Transforms the image into the frequency domain, retaining significant frequencies while discarding others, leading to effective compression.
**Principal Component Analysis (PCA)**: A dimensionality reduction technique that compresses images by reducing the number of principal components.
## Time Complexity Analysis
Each algorithm's computational efficiency is analyzed by measuring the time taken to process images of different sizes. The time complexity is plotted as graphs, making it easier to compare the performance of K-means, DCT, and PCA. This analysis helps in understanding the trade-offs between compression quality and processing time for each algorithm.
### How to Run the Project
### 1) Clone the Repository:
`git clone https://github.com/itsmeani06/Image-compression-analysis-using-different-algorithms.git
cd Image-compression-analysis-using-different-algorithms`
### 2) Install Dependencies:
Make sure you have Python and Jupyter Notebook installed. Then, install the required libraries using pip:
`pip install numpy scikit-learn scipy matplotlib pillow`
### 3) Run the Jupyter Notebook:
Start Jupyter Notebook and open the analysis.ipynb file to execute the cells and view the results.
## Results
**Image Compression:** Each algorithm compresses images effectively, with a trade-off between quality and compression ratio. The compressed images are compared to the original images in terms of size and visual quality.
**Time Complexity:** The time taken by each algorithm is plotted against the input image size, revealing how each algorithm scales with data size.

