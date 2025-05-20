# Smart-city-assistant
Smart City Sustainability Assistant is a AI-powered tool built using IBM Granite LLM via Hugging Face. It helps citizens and city officials by answering sustainability-related queries, summarizing lengthy government documents into simple bullet points, and predicting resource usage based on user-provided data. 

# Features
1. Conversational assistant powered by IBM Granite LLM

2. PDF upload and text input for document summarization

3. Resource consumption prediction with user-provided data

4. Simple and intuitive Streamlit UI accessible via Google Colab

# How to Run
1. Download all the files from this repository to your local machine.

2. Open the smart_city_assistant.ipynb notebook file in Google Colab:
   Go to https://colab.research.google.com/

3. Click Upload and select smart_city_assistant.ipynb from your downloaded files.

4. Upload the smart_city.py file to the Colab environment:
   In the Colab left sidebar, go to the Files tab
   Click Upload and select smart_city.py from your local files

5. Set your Hugging Face API token securely in the notebook:
   In the appropriate notebook cell, replace "your_token_here" with your own Hugging Face token. Run the cell to set the environment variable

6. Run all remaining notebook cells in order to:
   Install dependencies
   Load the IBM Granite LLM model from Hugging Face
   Start the Streamlit app using a public URL tunnel

When the notebook finishes running, copy the provided public URL and open it in your browser to access the Streamlit app UI.



