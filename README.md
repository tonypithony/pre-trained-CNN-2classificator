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


# Sources

* [Binary-classification-for-DCTandSVD-watermarks](https://github.com/tonypithony/Binary-classification-for-DCTandSVD-watermarks)
* [my-check-for-a-result-from-an-ai-article/pretrainedstegaanalyzator](https://github.com/unton3ton/my-check-for-a-result-from-an-ai-article/tree/main/pretrainedstegaanalyzator)
* [Метрики качества моделей бинарной классификации](https://loginom.ru/blog/classification-quality)
* [Classification metrics based on True/False positives & negatives](https://keras.io/api/metrics/classification_metrics/#f1score-class)
* [8 показателей эффективности классификации](https://nuancesprog.ru/p/15146/)
* [Корреляция Мэтьюса](http://www.machinelearning.ru/wiki/index.php?title=%D0%9A%D0%BE%D1%80%D1%80%D0%B5%D0%BB%D1%8F%D1%86%D0%B8%D1%8F_%D0%9C%D1%8D%D1%82%D1%8C%D1%8E%D1%81%D0%B0)
* [Пережевывая Матрицу Несоответствий — Confusion Matrix](https://habr.com/ru/articles/758510/)
* [Оценка качества в задачах классификации и регрессии](https://neerc.ifmo.ru/wiki/index.php?title=%D0%9E%D1%86%D0%B5%D0%BD%D0%BA%D0%B0_%D0%BA%D0%B0%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B0_%D0%B2_%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0%D1%85_%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8_%D0%B8_%D1%80%D0%B5%D0%B3%D1%80%D0%B5%D1%81%D1%81%D0%B8%D0%B8)
