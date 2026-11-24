# Quishing-scanner-software-POC-
An early quishing software POC which decodes a QR and displays the destination and estimates whether its hostname resembles phishing.

The QR Risk Detector helps users assess potentially harmful links by allowing them to enter a URL or upload a QR code image through the Gradio interface.
When a QR image is uploaded, the system decodes it and extracts the URL. It then analyses features such as the link’s length, character patterns and hostname structure using a trained machine learning model to produce a prediction and phishing score. This gives users an indication of potential risk before opening the link, although the prediction does not guarantee that a website is safe.

The reproduced quick experiment selected a character and numeric Logistic Regression model. It detected 73.9% of phishing validation URLs at a 4.9% false-positive rate. This improves on the numeric baseline at a similar operating point, but it does not deet the 95% recall target or establish that a website is safe.

