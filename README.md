# ImageSegmentation
 

Dalam Repository ini saya dari dan kelompok Elon Musk melakukan implementasi model beberapa model deep learning UNET dan FCN8 dengan datasets CityScapes. Model Deep Learning yang kami coba implementasikan yakni:

## Strategi Implementasi Model
Dalam implementasi model di atas kami menggunakan kriteria untuk uji coba yakni:
1. Optimizer Adam
2. Learning rate yakni 1e-3 dan decay 1e-6
3. Batch size yakni 16
4. Epoch 100
5. Data transform/augmentasi resize ke 256, normalize dan totensorv2

## Dependencies
This lab requires **Python 3.10.11** and the following Python libraries installed:
* Basic Libraries: [NumPy](http://www.numpy.org), [Open-CV](https://opencv.org)
* Visualization Libraries: [Matplotlib](http://matplotlib.org)
* Deep Learning Libraries: [Scikit-Learn](https://www.tensorflow.org), [PyTorch](https://pytorch.org)
