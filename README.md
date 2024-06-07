# Food Calorie Calculator

- This project is a calorie calculating application that identifies food items from images and provides their caloric and nutritional information. Leveraging advanced machine learning models and APIs, it aims to facilitate dietary tracking and promote informed nutritional choices.

## Features

- Image-Based Food Identification: Utilizes Hugging Face's Vision Transformer (ViT) model to accurately identify food items from uploaded images.
- Nutritional Information Retrieval: Integrates API Ninjas' nutrition API to fetch detailed caloric and nutritional data for the identified food items.
- User-Friendly Interface: Designed with Gradio to enable easy image uploads and real-time display of nutritional information.
- Seamless Integration: Combines the power of pre-trained models and APIs to provide a comprehensive solution for dietary tracking.
- 
## Installation
- To run this application locally, follow these steps:

## Clone the repository:

bash
Copy code
git clone https://github.com/b-akshay-k/Calorie-Calculator-Using-HuggingFace.git
cd food-calorie-calculator

## Install the required packages:

pip install torch transformers gradio requests

## Run the application:

python app.py

## Usage
Upload an Image: Launch the application and upload an image of the food item you want to analyze.
Get Nutritional Information: The application will identify the food item and display its caloric and nutritional details in real-time.

## Example
Here's a brief example of how the application works:

"C:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-06-07 150816.png"

Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

License
This project is licensed under the Apache 2.0 License. See the LICENSE file for details.
