CONVOLUTION NEURAL NETWORK TO CLASSIFY HAPPY AND SAD FACES 

![WhatsApp Image 2025-05-26 at 4 18 32 PM](https://github.com/user-attachments/assets/20e6ff19-3058-44f9-8d63-12a957d0c60a)

| Layer (type)                  | Output Shape          | Param #      |
|------------------------------|----------------------|--------------|
| conv2d (Conv2D)              | (None, 254, 254, 16) | 448          |
| max_pooling2d (MaxPooling2D) | (None, 127, 127, 16) | 0            |
| conv2d_1 (Conv2D)            | (None, 125, 125, 32) | 4,640        |
| max_pooling2d_1 (MaxPooling2D)| (None, 62, 62, 32)  | 0            |
| conv2d_2 (Conv2D)            | (None, 60, 60, 16)   | 4,624        |
| max_pooling2d_2 (MaxPooling2D)| (None, 30, 30, 16)  | 0            |
| flatten (Flatten)            | (None, 14400)        | 0            |
| dense (Dense)                | (None, 256)          | 3,686,656    |
| dense_1 (Dense)              | (None, 1)            | 257          |
