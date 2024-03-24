![](https://raw.githubusercontent.com/tonypithony/pre-trained-CNN-2classificator/main/05_1543348250-660x320.jpg)

![](https://raw.githubusercontent.com/tonypithony/pre-trained-CNN-2classificator/main/acc_whitewm_norm100epochs.png)

![](https://raw.githubusercontent.com/tonypithony/pre-trained-CNN-2classificator/main/Снимок%20экрана_2024-03-24_09-48-17.png)

![](https://raw.githubusercontent.com/tonypithony/pre-trained-CNN-2classificator/main/mtx.JPG)

![](https://raw.githubusercontent.com/tonypithony/pre-trained-CNN-2classificator/main/mcc.JPG)

## keras == 2.15.0, python == 3.11.5.
![](https://raw.githubusercontent.com/tonypithony/pre-trained-CNN-2classificator/main/keras-2.15.0-python-3.11.5.png)


Оптимизатор Adam: достаточно упомянуть, что это более сложный оптимизатор, в котором скорость
обучения задается адаптивно. Кроме того, он намного менее чувствителен
к масштабу параметров — настолько нечувствителен, что мы можем снова воспользоваться исходным (ненормализованным) входным сигналом t_u и даже
увеличить скорость обучения до 1e-1, и Adam даже глазом не моргнет [PyTorch. Освещая глубокое обучение (стр 179,186)](https://vk.com/wall-193131136_22498)
