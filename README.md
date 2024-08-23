# llm_usecases
A simple template to play around with open source llm tools


## Installation

1. Create and activate a virtual environment
```
# Create venv
$ python3 -m venv venv

# Activate venv
$ source venv/bin/activate
```

2. Install python packages
```
$ pip install -r requirements.txt
```

3. Install Ollama
    3.1. Open https://ollama.com/download in any browser.
    3.2. Select OS of the current system being used.
    3.3. Navigate to the directory of download
    3.4. Unzip Ollama-*.zip (depends on OS)
    3.5. Open Ollama by double-clicking on the application
    3.6. Follow the instruction to further set it up

4. Download Ollama models:
```
$ ollama pull phi
```