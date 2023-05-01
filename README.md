# ChatCSV: Chat with any CSV
This is a simple streamlit app where you can upload any csv file and get insights out of it.

## Setup 
1. You need Python installed. If you don't have Python installed, install if from this [link](https://www.python.org/downloads/)

2. Clone the repository. 
```
git clone https://github.com/sudarshan-koirala/chat-with-csv.git
```

3. Once cloned, go inside the repository or folder.
```
cd chat-with-csv
```

4. Create a virtual environment and activate it.
```
python3 -m venv .venv && source .venv/bin/activate
```

5. Install the packages from the requirements.txt file.
```
pip install -r requirements.txt
```
6. Add you openai api key inside `.streamlit/secrets.toml` file.
7. Run the streamlit app.
```
streamlit run app.py
```

After running the streamlit command, you should now be able to access the app at http://localhost:8501/. Upload the csv file and happy chatting.