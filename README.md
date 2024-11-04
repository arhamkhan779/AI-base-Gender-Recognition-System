# AI-Based Gender Recognition System

## Demo Video

Watch the demo of the application here:  
[![Watch the demo](https://img.youtube.com/vi/gfjHguFRXXA/0.jpg)](https://youtu.be/gfjHguFRXXA)

## Overview

This project implements an AI-based gender recognition system using machine learning techniques. The user interface is developed with Streamlit, allowing users to easily interact with the model. The application analyzes images to predict gender, providing a practical tool for various applications.

## Project Structure

```
.
├── .gitignore
├── FaceDetection.ipynb
├── LICENSE
├── README.md
├── app.py
├── genderrecognition.mp4
├── haarcascade_frontalface_default.xml
├── main
└── util.py
```

## Getting Started

### Prerequisites

- Python 3.x
- pip
- [Anaconda](https://www.anaconda.com/products/distribution) (recommended for package management)

### Required Libraries

To run this project, you will need to install the following libraries:

- TensorFlow
- OpenCV-Python
- Pillow
- NumPy
- Streamlit

You can install these libraries using pip:

```bash
pip install tensorflow opencv-python pillow numpy streamlit
```

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ai-gender-recognition.git
   cd ai-gender-recognition
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv env_name
   source env_name/bin/activate  # On Windows use `env_name\Scripts\activate`
   ```

3. **Install Required Libraries**:  
   Use the command provided above to install the required libraries.

### Running the Application

1. **Start the Streamlit Application**:
   Run the following command to start the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Workflow

1. **Data Ingestion**:
   - The application processes input images to prepare for gender recognition.

2. **Model Training**:
   - The model is developed and trained using the notebook `FaceDetection.ipynb`, which utilizes machine learning techniques for accurate gender classification.

3. **Application Logic**:
   - `app.py` contains the main application logic, allowing users to upload images and receive predictions.

4. **User Interaction**:
   - Users can upload images through the Streamlit interface to determine the predicted gender.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors and tools that facilitated the project, including libraries for machine learning and image processing.

