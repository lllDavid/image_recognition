# This model recognizes if a image is a cat or a dog

## Prerequisites
- Python 3.12+
- Git

## Using the Pre-Trained CNN Model
This repository includes a pre-trained CNN model that is stored using Git Large File Storage (LFS). 

To use the model, please follow these steps:

### 1. Install Git LFS
Before cloning the repository, you must install Git LFS.
```bash
git lfs install
```

### 2. Clone the Repository
```bash
git clone https://github.com/lllDavid/image_recognition
```
### 3. Download Model
```bash
git lfs pull
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Create a /images folder ind the main directory, where you will put the images to be recognized
```bash
mkdir images
```

### 6. Start the application
Run the server.py and client.py file
```bash
python server.py
python client.py
```
To upload a image via FTP run:
```bash
python ftp.py
```