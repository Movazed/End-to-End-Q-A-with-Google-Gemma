
## Tech Stack

faiss-cpu 

groq

langchain-groq

PyPDF2

langchain-google-genai

langchain

streamlit

langchain-community

python-dotenv

pypdf

google-cloud-aiplatform>=1.38

# End to End Q&A with Google Gemma

## Project Description
This project aims to build an end-to-end Question & Answer system using Google Gemma. It leverages multiple libraries and tools to extract, process, and answer questions from a given set of documents.

## Requirements
To set up the project, ensure you have Python installed and create a virtual environment. Then, install the required packages using:

```bash
pip install -r requirements.txt

Setup and Usage
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <repository-directory>
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the project root and add necessary environment variables. For example:

dotenv
Copy code
GOOGLE_APPLICATION_CREDENTIALS=path/to/your/google-credentials.json
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Project Structure
The project directory is organized as follows:

bash
Copy code
project-directory/
│
├── .env                    # Environment variables file
├── app.py                  # Main application script
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
├── data/                   # Directory to store data files
├── models/                 # Directory to store trained models
└── utils/                  # Utility functions and scripts
Contributing
Feel free to fork the repository, make changes, and submit pull requests. Any improvements or bug fixes are welcome!



