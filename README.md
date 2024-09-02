# Generative AI Course - Getting Started

Welcome to the Generative AI Course! This README will guide you through the steps required to set up your environment, clone the course repository, and run the code. Follow the instructions carefully to get started.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Option 1: Local Setup](#option-1-local-setup)
   - [Cloning the Repository](#cloning-the-repository)
   - [Setting Up Your Environment](#setting-up-your-environment)
   - [Running the Notebooks](#running-the-notebooks)
3. [Option 2: Google Colab](#option-2-google-colab)
   - [Cloning the Repository](#cloning-the-repository-on-colab)
   - [Running the Notebooks on Colab](#running-the-notebooks-on-colab)
4. [Sessions Overview](#sessions-overview)

## Prerequisites

Before you start, ensure you have the following:

- **GitHub Account**: You will need a GitHub account to fork the repository.
- **Knowledge of Python**: Basic knowledge of Python programming is required.

## Option 1: Local Setup

### Cloning the Repository

Follow these steps to clone the course repository:

1. **Fork the Repository**

   - Go to the [course repository on GitHub](https://github.com/your-course-repo).
   - Click on the "Fork" button at the top-right corner of the page.

2. **Clone the Forked Repository**
   - Open a terminal or command prompt.
   - Run the following command to clone the repository to your local machine:
     ```bash
     git clone https://github.com/your-github-username/your-course-repo.git
     ```
   - Navigate into the cloned repository:
     ```bash
     cd your-course-repo
     ```

### Setting Up Your Environment

To set up your environment, you need to install the required dependencies. You can do this using `pip`.

1. **Create a Virtual Environment (Optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

````

2. **Install Dependencies**
   - Run the following command to install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

### Running the Notebooks

Now you are ready to run the Jupyter notebooks.

1. **Start Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

   This will open the Jupyter Notebook interface in your default web browser.

2. **Navigate to the Session Notebook**

   - In the Jupyter Notebook interface, navigate to the folder of the session you are currently working on.
   - Open the notebook for the session (e.g., `Session1_Notebook.ipynb`).

3. **Follow the Instructions in the Notebook**
   - Each session notebook will contain specific instructions and code cells that you need to complete.
   - Follow the instructions, run the code cells, and complete the assignments.

## Option 2: Google Colab

### Cloning the Repository on Colab

1. **Fork the Repository**

   - Go to the [course repository on GitHub](https://github.com/your-course-repo).
   - Click on the "Fork" button at the top-right corner of the page.

2. **Open Google Colab**

   - Go to [Google Colab](https://colab.research.google.com/).

3. **Open the Notebook from GitHub**

   - In Google Colab, click on `File > Open notebook`.
   - Select the `GitHub` tab.
   - Enter your GitHub repository URL or search for the repository name.
   - Select the notebook you want to open (e.g., `Session1_Notebook.ipynb`).

4. **Save a Copy in Drive (Optional)**
   - To save your work, you can save a copy of the notebook to your Google Drive by clicking `File > Save a copy in Drive`.

### Running the Notebooks on Colab

1. **Follow the Instructions in the Notebook**
   - Each session notebook will contain specific instructions and code cells that you need to complete.
   - Follow the instructions, run the code cells, and complete the assignments.
````
