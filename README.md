# fusionAI
FaceFusion is a powerful AI application designed to seamlessly merge two faces using cutting-edge computer vision and deep learning techniques. Whether you're creating fun face swaps or performing artistic style transfers, FaceFusion provides smooth, realistic, and high-resolution outputs via a simple interface.

## 📁 Project Structure

```
facefusion/
├── assets/                 # Sample inputs and output images
├── facefusion/             # Core logic: detection, alignment, fusion algorithms
├── web/                    # Web interface: Flask/React components
├── models/                 # Pre-trained models and weight files
├── utils/                  # Helper functions
├── main.py                 # Main script to run the app
├── requirements.txt        # Python package dependencies
└── README.md               # Project documentation
```

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.8+
- pip
- Git
- (Optional) CUDA GPU for better performance

### 📦 Installation

```bash
git clone https://github.com/yourusername/facefusion.git
cd facefusion
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## ▶️ Run the Application

### 🖥️ CLI Mode

```bash
python main.py --source path_to_image1.jpg --target path_to_image2.jpg --output result.jpg
```

### 🌐 Web Mode

```bash
cd web
python app.py
# Visit http://localhost:5000 in your browser
```

## ✨ Features

- ✅ Face Alignment
- ✅ High-Resolution Outputs
- ✅ Multiple Blend Modes
- ✅ Web & CLI Support
- ✅ Privacy-Friendly
- ✅ Cross-Platform

## 📄 License

This project is licensed under the MIT License.
