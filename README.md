# Partial Data Clustering - PHCL-LR (Partial Data Hierarchical Clustering based on DBSCAN and Logistic Regression)

PHCL-LR (Partial Data Hierarchical Clustering based on DBSCAN and Logistic Regression) is a novel algorithm developed to address the challenge of classifying partial or incomplete data with high accuracy. This ongoing project combines three powerful techniques—DBSCAN (Density-Based Spatial Clustering of Applications with Noise), hierarchical clustering, and logistic regression—to create an improved method for data classification.

## Algorithm Overview

PHCL-LR integrates the strengths of each technique:

- **DBSCAN**: Used for identifying dense regions in data, DBSCAN helps to find core clusters while handling noise effectively.
- **Hierarchical Clustering**: This technique is employed to form a hierarchical structure of clusters, providing a flexible and interpretable framework for data analysis.
- **Logistic Regression**: Logistic regression is then applied to classify data points based on the hierarchical structure and the clusters formed.

### Key Features:
- **Classification of Partial Data**: The algorithm is specifically designed to handle incomplete datasets, which is a common challenge in real-world applications.
- **Hybrid Approach**: Combines clustering and classification techniques for better performance.
- **Ongoing Research**: This project is part of a Doctorate research and is being developed in collaboration with researchers. The algorithm is still evolving and subject to changes as the research progresses.

## Project Structure

The project is organized as follows:

- **`hierarchical_clustering.ipynb`**: Contains the Jupyter notebook that implements hierarchical clustering on the dataset. It demonstrates how the algorithm forms clusters from partial data.
- **`main_werk.ipynb`**: A notebook focused on integrating DBSCAN and logistic regression with hierarchical clustering to demonstrate the full functionality of the PHCL-LR algorithm.

## Installation

To use this project locally, follow the steps below:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Partial-Data-Clustering.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Partial-Data-Clustering
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebooks to explore the algorithm and its implementation:

    ```bash
    jupyter notebook hierarchical_clustering.ipynb
    jupyter notebook main_werk.ipynb
    ```

## Usage

Once the project is set up, you can experiment with the provided notebooks to explore how the PHCL-LR algorithm works. The steps are outlined in the notebooks to show:

- **Clustering Data**: Using DBSCAN and hierarchical clustering to create clusters.
- **Classifying Data**: Applying logistic regression to classify data points within the clusters.
- **Handling Partial Data**: Demonstrating how the algorithm handles incomplete datasets.

## Example

In the `main_werk.ipynb`, you will find examples of applying PHCL-LR to real-world datasets, including:

- Loading a dataset with missing or incomplete values.
- Applying the algorithm to form clusters and classify data.
- Visualizing the clusters and classification results.

## Research and Future Work

This project is an ongoing effort as part of a Doctorate research in collaboration with fellow researchers. The algorithm is still evolving, and improvements are being made to enhance its accuracy and scalability. Future work includes:

- **Improving the robustness** of the algorithm on more complex datasets.
- **Expanding the range** of datasets that can be classified.
- **Fine-tuning the model** for better performance on real-world partial data.

## Contributions

Contributions to this project are welcome! Please feel free to open an issue or submit a pull request if you have any suggestions for improvement or new features.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
