### Project Title
Identifying Age Through Image Classification

### Project Description
This project involves developing an image classification model to identify the age category of individuals based on their facial images. The solution utilizes a Support Vector Machine (SVM) with a linear kernel to classify the images. The model extracts features from the images, trains on labeled data, and provides predictions for new images. It aims to automate the age identification process, offering a quick and efficient method for applications such as age verification and demographic analysis.

### Quick Steps to Run the Project:
1. Save the training images in the project directory as organized subfolders named after their respective categories.
2. Save the Python file (`age_classifier.py`) in a directory.
3. Ensure that the required packages are installed (see Requirements).
4. Run the script to preprocess the images, train the model, and make predictions.
5. Use the script to capture the classification results and log them.

### Requirements
- Python 3.x
- scikit-learn
- NumPy
- pandas
- Pillow

### Installation
To set up the environment and install the required packages, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankur28121982/08-Age-Classification-of-Pics
   cd age-classification
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

### Running the Script
To run the script, use the following command:
```bash
python age_classifier.py
```

### Script Overview
`age_classifier.py`
- **Functions:**
  - `extract_features(image_path)`: Extracts features from an image by converting it to grayscale, resizing, and flattening the array.
  - `load_data_and_labels(image_directory)`: Loads images and labels from a directory, extracting features and creating a label map.
  - `main()`: The main function that handles data loading, model training/loading, predictions, and logging results.

### Author
**Dr. Ankur Chaturvedi**  
[ankur1122@gmail.com](mailto:ankur1122@gmail.com)  
Dr. Ankur Chaturvedi is a seasoned Transformation Specialist with expertise in Consulting, Data Science, and Quality Management. He has a profound background in LEAN and Agile Transformation, managing and optimizing processes for large teams. Currently a Senior Manager at Infosys BPM, he leads process excellence and organizational improvements, leveraging data analytics and robotics to drive efficiency.

