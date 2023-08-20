br# This is my Year 10 IT schoolwork 📖

> I upload all my work in this repo for a safe place to keep my work. All the work I do in this repo is for school purposes and assignments for IT. This folder contains all my work on the Machine Learning Unit in IT, which is based on Python coding and how it can help us as humans to perform tasks more efficiently.

## The Grade Predictor: 📊

> This Python code demonstrates the use of Scikit-Learn for linear regression in machine learning. The aim is to predict a student's final grade ("G3") based on attributes like past grades ("G1" and "G2"), study time, failures, and absences.
>
> After importing libraries like Pandas, NumPy, and Scikit-Learn, the script loads a dataset from a CSV file and selects relevant attributes. It then follows these key steps:
>
> - Attributes and Labels: Explains the concept of attributes (input features) and labels (target values). Attributes here include "G1," "G2," study time, failures, and absences, with "G3" as the label.
> - Data Splitting: Divides the dataset into training and testing sets using Scikit-Learn's `train_test_split`.
> - Linear Regression: Describes linear regression as finding a "line of best fit" through data points, particularly effective when strong correlations exist.
> - Model Saving and Loading: Demonstrates saving and loading the trained model using pickle.
> - Data Visualization: Concludes by visualizing the relationship between "G1" and "G3" through a scatter plot.
>
> In summary, this concise code covers data loading, attribute selection, model training, evaluation, model persistence, and visualization using Scikit-Learn, Pandas, NumPy, and Matplotlib.

## Diabetes Predictor: 💉

> This code uses Scikit-Learn to predict diabetes occurrence using the K-Nearest Neighbors (KNN) algorithm on a dataset of 768 diagnosed individuals. It covers:
>
> - Data Prep: Handling missing or zero values in columns, like "Glucose" and "Blood Pressure," by replacing them with column means.
> - Data Split and Scaling: Dividing data into training and testing sets, then scaling attributes using StandardScaler.
> - K-NN Explanation: Briefly explains K-NN's concept of grouping similar items based on neighbours, using a defined 'K' value.
> - Model Training and Prediction: Training K-NN on training data and predicting outcomes on test data.
> - Confusion Matrix Analysis: Introducing the confusion matrix to assess model performance. Describing True Positives, False Positives, True Negatives, and False Negatives.
> - Confusion Matrix Interpretation: Visualizing the matrix and computing F1-Score, a combined precision and recall metric, for overall model evaluation.
>
> In essence, this code demonstrates the process of preparing data, training, evaluating, and interpreting a KNN model using Scikit-Learn, focusing on predicting diabetes occurrence based on attributes.

## KMeans Data: 🧩

> This code demonstrates the application of the K-Means clustering algorithm for unsupervised learning using the Scikit-Learn library. K-Means aims to group data points into clusters by minimizing the squared distances between points and their assigned cluster centroids. Key points of the code include:
>
> - Unsupervised Learning: Explains unsupervised learning, where the algorithm learns patterns from unlabeled data.
> - Explanation of K-Means: Describes K-Means' objective to create compact clusters of data points by iteratively refining centroids.
> - Step-by-Step: Outlines the K-Means process, including choosing the number of clusters, initializing centroids, assigning data points, updating centroids, and repeating for convergence.
> - Libraries: Imports necessary libraries like NumPy, Pandas, matplotlib, and Scikit-Learn.
> - Data Setup: Loads the Iris dataset, scales features, and prepares data for clustering.
> - Model Building: Applies K-Means clustering with three clusters to the dataset.
> - Plotting the Model Outputs: Displays scatter plots of data points with both ground truth and K-Means classifications.
> - Evaluation: Prints the classification report to evaluate clustering results.
> - Interpreting Results: Presents a diagram illustrating how K-Means clusters align with actual classifications.
>
> Overall, this code provides a comprehensive illustration of K-Means clustering, covering data preparation, model building, visualization, and evaluation using Scikit-Learn, while explaining the unsupervised learning concept.

## Reinforcement-Learning: 🎮

> Please go to Reinforcement-Learning/CartPole folder as the other folders are being worked on and are separate work from the main assessment.
>
> The provided code focuses on implementing reinforcement learning using the OpenAI Gym library. It uses the example of the CartPole environment, where a pole is attached to a cart, and the goal is to keep the pole balanced on top of the cart.
>
> Key points of the code include:
>
> - Introduction: A title and an image are displayed to introduce the topic of reinforcement learning with OpenAI Gym.
> - RL Basics: Explains the components of reinforcement learning: Action, Reward, Environment, and Agent. It also includes a simple illustration of these components.
> - Libraries and Installations: The necessary libraries (e.g., gym, numpy, time, pygame) are imported, and installation commands for the required libraries are provided in the comments.
> - Creating the Environment: An environment for the CartPole task is created using the `gym.make()` function. The environment is set to render in "human" mode.
> - States: The different states in the CartPole environment are explained, including the position and velocity of the cart and the angle and angular velocity of the pole.
> - Simulation: The simulation is run using a loop. For each episode, the environment is reset, and random actions are taken for a certain number of time steps. The observations at each time step are collected.
> - Observation and Limits: The observation space limits (both upper and lower) and action space of the environment are printed.
> - Simulating the Environment: The environment is simulated for a specified number of episodes and time steps. Random actions are taken, and observations are collected. The loop includes termination conditions to break if the pole falls.
> - Closing the Environment: Finally, the environment is closed after the simulation.
>
> This code demonstrates a basic implementation of reinforcement learning in the context of the CartPole environment using OpenAI Gym. It provides insights into the components of reinforcement learning and how to interact with the Gym environment to simulate agent-environment interactions.

## Essay on The privacy of AI and the ethics of it: 🔐

>**Summary:**
>
> With the rapid advancement of technology and AI, concerns about privacy are growing. AI's widespread use in surveillance, data collection, and healthcare raises ethical questions. Surveillance AI's efficiency in facial recognition for security is beneficial but invasive. Consent and data storage limits are necessary for ethical surveillance. In data collection, AI's sorting of sensitive information without consent breaches privacy. Healthcare AI aids diagnosis but must balance benefits with privacy breaches. To implement AI ethically, secure mechanisms, informed consent, reliability, and patient understanding are crucial. Balancing AI's benefits and risks is vital for an ethical AI future that respects privacy while harnessing its potential.               