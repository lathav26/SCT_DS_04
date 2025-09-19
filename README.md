#  Hand Gesture Recognition with CNN  

##  Description  
A PyTorch-based hand gesture recognition system using CNN. The model is trained on the Hagrid dataset with data augmentation, supports multi-class classification, evaluates accuracy, and visualizes predictions for gesture recognition applications.  

##  Features  
- Custom CNN built with PyTorch  
- Data augmentation for robustness  
- Training & validation accuracy tracking  
- Visualization of predictions  
- Easy to run on Google Colab or local system  

## Dataset  
Organize dataset in `ImageFolder` format:  

> If using the **Hagrid repo**, run `dataset.py` first to generate image folders.  

## 🛠️ Tech Stack  
- Python  
- PyTorch  
- Torchvision  
- Matplotlib  
- NumPy  

## 📊 Example Training Output  
Epoch 1/3, Loss: 1.2345, Train Acc: 78.90%, Val Acc: 75.30%
Epoch 2/3, Loss: 0.8456, Train Acc: 85.20%, Val Acc: 81.70%
...

