# Emotion Detection Application

This project is a simple Flask web application for detecting emotions from text using Watson NLP.

## How to run

```bash
pip install -r requirements.txt
python server.py
```

Open the application in a browser:

```text
http://127.0.0.1:5000/
```

To test blank input error handling, open:

```text
http://127.0.0.1:5000/emotionDetector?textToAnalyze=
```

Expected output:

```text
Invalid text! Please try again!
```

Save the screenshot as:

```text
7c_error_handling_interface.png
```
