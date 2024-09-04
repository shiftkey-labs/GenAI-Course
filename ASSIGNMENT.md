# Final Assignment: Training and Deploying FLAN-T5

**Due Date:** The assignment is due **one week** after the course has been completed.

## Assignment Overview:

In this assignment, you will train the FLAN-T5 model and deploy it on Hugging Face. The following steps outline the tasks you need to complete to demonstrate your understanding of generative AI, model training, and deployment.

### Assignment Steps:

1. **Setup Colab with GPU:**
   - Open a new Colab notebook.
   - Enable GPU under "Runtime" > "Change runtime type" > Select GPU.
2. **Install Necessary Libraries:**

   - Install libraries such as `transformers`, `torch`, and `datasets` required for training the model.

3. **Load and Move the FLAN-T5 Model to the GPU:**

   - Load the **FLAN-T5** model from Hugging Face's Model Hub.
   - Ensure the model is moved to the GPU to accelerate training.

4. **Load the Dataset for Training:**
   - Choose a dataset relevant to your task (e.g., text summarization). You can select a dataset like CNN/DailyMail or another dataset from Hugging Face's datasets library.
5. **Preprocess the Data and Move It to the GPU:**

   - Preprocess the dataset by tokenizing it and preparing it for the FLAN-T5 model.
   - Move the preprocessed data to the GPU.

6. **Set Training Parameters:**

   - Define training parameters such as batch size, learning rate, and number of epochs.

7. **Train the FLAN-T5 Model:**

   - Initialize the training loop with the specified dataset and parameters.
   - Train the model on the dataset.

8. **Evaluate and Save the Model:**

   - After the training is complete, evaluate the model's performance using appropriate metrics.
   - Save the trained model for deployment.

9. **Use the Trained Model for Inference:**

   - Use the trained FLAN-T5 model to generate summaries (or perform another task based on the dataset you used).
   - Test the model's outputs to ensure the quality and relevance of the generated content.

10. **Deploy the Model on Hugging Face:**
    - Upload and deploy the trained model on Hugging Face Model Hub.
    - Follow Hugging Face's guidelines to make the model publicly accessible.
    - Ensure that the model is functional and ready for others to use.

### Submission Requirements:

1. **Python Notebook Submission:**

   - Submit a link to your **Google Colab notebook** or **GitHub repository** containing your Python code for the entire process, from model setup to deployment.

2. **Hugging Face Deployment:**
   - Deploy the model on Hugging Face.
   - Provide a **link to your Hugging Face model repository**.

### Guidelines:

- **Comment your code** to explain each step of the process.
- Make sure the code is clear, well-structured, and easy to follow.
- Ensure your deployed model is functional and can generate appropriate outputs.
