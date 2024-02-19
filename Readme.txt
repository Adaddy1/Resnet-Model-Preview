Vehicle Damage Insurance Claims Fraud Detection
Overview
This repository contains code for a vehicle damage insurance claims fraud detection system. The system utilizes computer vision techniques to classify images as either fraudulent or non-fraudulent within the context of insurance claims.

Prerequisites
Before running the code, make sure you have the following prerequisites installed:

1.Python 3.x
2.Streamlit (pip install streamlit)
3.Pandas (pip install pandas)
4.TensorFlow (pip install tensorflow)
5.Hugging Face Hub (pip install huggingface-hub)


Steps to Run the Code
1.Obtain OpenAI API Key:

Create a free OpenAI account and obtain an API key.
Open vehicle_fraud_detection.py and replace the placeholder at line 89 with your OpenAI API key.
Additionally, provide your API key when prompted while running the app.

2.Navigate to the Web Directory:

Open a terminal or command prompt.
Navigate to the web directory using the following command:

cd web

3.Run Streamlit App:

Execute the following command to run the Streamlit app:

streamlit run vehicle_fraud_detection.py

This will launch the web application on your local machine.

4.Browse CSV File:

Once the app is running, a user interface will be presented.
Use the provided file uploader to select a CSV file containing information about images.
View Predictions:

The app will automatically process each image in the CSV file.
Predictions (fraudulent or non-fraudulent) along with confidence scores will be displayed.
At the end of the process, a new CSV file named predictions_output.csv will be created, capturing the model's evaluations for each input image.


Important Notes
Make sure you give the correct path for your images folder or your image csv location
Ensure that the CSV file provided adheres to the expected format.
Follow the instructions in the console or Streamlit app interface for any additional inputs or interactions.

Additional Information
For more details on the model architecture, experiments conducted, and challenges faced, refer to the detailed documentation and research report provided in the repository.