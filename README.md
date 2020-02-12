Pneumonia is an inflammatory condition of the lung affecting primarily the small air sacs known as alveoli, Typically symptoms include some combination of productive or dry cough, chest pain, fever, and trouble breathing. Severity is variable. 

Pneumonia is usually caused by infection with viruses or bacteria and less commonly by other microorganisms, certain medications and conditions such as autoimmune diseases. Risk factors include other lung diseases such as cystic fibrosis, COPD, and asthma, diabetes, heart failure, a history of smoking, a poor ability to cough such as following a stroke, or a weak immune system. Diagnosis is often based on the symptoms and physical examination. Chest X-ray, blood tests, and culture of the sputum may help confirm the diagnosis.

In this project we aim to leverage the ability of Machine learning methods to diagnose pneumonia, based on Chest X-Ray images.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites
1) PyTorch & TorchVision
2) OpenVINO Toolkit

### Running the tests
The test can be run from command line.<br /> <br />
**Example**: python app.py -m pneumonia-detection-model.xml -i chest-x-ray.jpg <br />
where **-m** refers to the path of the model that will be making the classification (Pneumonia or not) <br />
**-i**  refers to the path of the input file i.e., chest x-ray to be diagnosed for Pneumonia

### Authors
1) Dina AbdelRahman
2) Vijaya Lakshmi Venkatraman
