# Azure Custom Vision Image Classifier - Fruits 

A Python script that demonstrates image classification using Azure Custom Vision Service.

## Prerequisites

- Azure subscription with Custom Vision resource
- Python 3.7 or later
- Required Python packages:
  ```
  azure-cognitiveservices-vision-customvision
  python-dotenv
  ```

## Setup

1. Clone this repository
2. Create a `.env` file in the root directory with:
   ```
   TrainingEndpoint=<your_endpoint>
   TrainingKey=<your_key>
   ProjectID=<your_project_id>
   ```

3. Prepare your training data with this structure:
   ```
   more-training-images/
   ├── apple/
   ├── banana/
   └── orange/
   ```

4. Add training images to respective folders

## Usage

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the training script:
```bash
python train-classifier.py
```
