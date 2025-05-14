# Bart-Large-CNN_CoreML_12Token

A macOS SwiftUI app that converts HuggingFace's `facebook/bart-large-cnn` to a Core ML `.mlpackage` model using `coremltools`.

## ✅ Features

- Uses `transformers` to load BART model
- Traces and converts using PyTorch and `coremltools`
- Saves `.mlpackage` to your Desktop
- Run conversion with a single button

## 💻 Requirements

- macOS 13+ (for Core ML `mlprogram`)
- Xcode 15+
- Python 3.9+
- `torch`, `transformers`, `coremltools`

## 🛠 Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/BartToCoreML.git
