# VizLearn: Interactive Machine Learning Visualizations

<div align="center">
  *Bringing machine learning concepts to life, one visualization at a time.*
</div>

---

## 📖 About The Project

VizLearn is a collection of interactive, web-based tools designed to make complex machine learning algorithms and data processing concepts intuitive and easy to understand. Each module provides a hands-on visualization that allows you to see the inner workings of an algorithm, manipulate its parameters, and build a stronger mental model of how it operates.

## ✨ Features

Explore a growing library of interactive visualizations:

*   **Core Concepts:**
    *   **Perceptron:** The fundamental building block of neural networks.
    *   **Activation Functions:** Compare Sigmoid, Tanh, ReLU, and more, interactively.
    *   **Gradient Descent:** Understand how models learn with an interactive playground and a data flow comparison.
    *   **Cosine Similarity:** Visualize vector similarity in a 3D space.
    *   **Tokenization:** See how text is broken down into Words, Characters, or Sentences.
*   **Supervised Learning:**
    *   **K-Nearest Neighbors (KNN):** Classify new data points based on their neighbors.
    *   **Support Vector Machine (SVM):** See how SVMs find the optimal hyperplane to separate data.
    *   **Naive Bayes:** A step-by-step explainer for the classic probabilistic classifier.
*   **Unsupervised Learning:**
    *   **K-Means Clustering:** Watch how clusters are formed and centroids are updated.
*   **Data Processing:**
    *   **Image Data Augmentation:** Apply transformations like rotation, zoom, and noise to see their effect.
    *   **Image Processing:** Visualize Grayscale and RGB images as numerical matrices and apply filters.
*   **Algorithms:**
    *   **Backtracking:** A visualization of the backtracking algorithm solving a maze.

## 🛠️ Built With

*   **Backend:** [Node.js](https://nodejs.org/) with [Express.js](https://expressjs.com/) for serving the applications.
*   **Frontend:** Vanilla HTML, CSS, and JavaScript.
*   **Styling:** [TailwindCSS](https://tailwindcss.com/) for rapid and clean UI development.
*   **Visualization Libraries:**
    *   [Chart.js](https://www.chartjs.org/) for 2D plotting.
    *   [Three.js](https://threejs.org/) for 3D visualizations.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js and npm installed on your machine.
*   [Node.js](https://nodejs.org/en/download/)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your_username/vizlearn.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd vizlearn
    ```
3.  **Install NPM packages:**
    *(While this project currently has no external npm dependencies, this is good practice for Node.js projects.)*
    ```sh
    npm install
    ```

### Running the Application

1.  **Start the server:**
    ```sh
    node index.js
    ```
2.  **Open your browser:**
    Navigate to `http://localhost:3000` to see the main page (currently a placeholder).

## Usage

To view a specific visualization, navigate directly to its HTML file in your browser while the server is running. For example:

*   `http://localhost:3000/perceptron.html`
*   `http://localhost:3000/svm.html`
*   `http://localhost:3000/k-means.html`

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Ashish Jangra - [@ashish_zangra](https://www.instagram.com/ashish_zangra/)

Project Link: [https://github.com/AshishJangra27/vizlearn](https://github.com/AshishJangra27/vizlearn)

