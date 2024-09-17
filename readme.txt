Chat PDF Using Gemini
This project allows you to interact with PDF documents through a conversational interface using Streamlit and various machine learning tools. The application processes PDF files, splits the text into chunks, and uses embeddings to answer questions based on the content of the PDFs.

Project Structure
app.py: The main Streamlit application file.
requirement.txt: File listing all required Python libraries for this project.
Prerequisites
Ensure you have Python 3.10 or later installed. It is recommended to use a virtual environment for this project.

Setup
Follow these steps to set up and run the project:

1. Clone the Repository
If you haven't already, clone the repository to your local machine:

bash

git clone <repository-url>
cd <repository-directory>
2. Create and Activate a Virtual Environment
Create a virtual environment to manage your project dependencies:


python -m venv venv

Activate the virtual environment:

On Windows:

venv\Scripts\activate

On macOS/Linux:

source venv/bin/activate

3. Install Dependencies
Install the required Python libraries using pip and the requirement.txt file:

pip install -r requirement.txt

4. Set Up Environment Variables
Ensure you have a .env file in the root directory of the project with the necessary environment variables. For example, include your Google API key:


GOOGLE_API_KEY=your_google_api_key_here

5. Run the Streamlit Application
Start the Streamlit application with the following command:


streamlit run app.py
This command will open the Streamlit app in your default web browser, allowing you to upload PDF files and interact with them.