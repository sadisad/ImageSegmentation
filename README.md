# ImageSegmentation
 
![0_WCg2G3SbI_BsGDc0](https://github.com/sadisad/ImageSegmentation/assets/61278337/ddf669b6-9b16-4c6d-a518-3b5137f1261c)


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

## Kesimpulan
UNet Mendapatkan Dice Loss Sebesar **0.088304** dan Dice Coef **0.911695**. 
