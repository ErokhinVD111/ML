# ML
В процессе работы была построена нейронная сеть, определяющая что за объект находится на фотографии.

Основная библиотека, которая использовалась - TensorFlow https://www.tensorflow.org/

Нейронная сеть может распознать несколько видов одежды: T-shirt/top, Trouser, Pullover, Dress, Coat,
Sandal, Shirt, Sneaker, Bag, Ankle boot.
Естественно, точность распознования очень сильно зависит от качества фото. 
Поэтому далеко не каждая фотография с одеждой будет корректно распознана. 

Для исполнения кода использовалась среда Colaboratory https://colab.research.google.com/

Пример распознавания одежды на картинке из интернета с помощью нейронной сети:

Фотография рубашки из интернета:

![image](https://user-images.githubusercontent.com/81001066/163848708-2abac1e6-f123-482f-8ab3-a3b33b19c908.png)

Пример распознования рубашки на фото нейронной сетью:

![image](https://user-images.githubusercontent.com/81001066/163848116-cc0a2ef1-2c67-43a1-9351-ace529a02261.png)

Фотография кроссовка из интернета:

![image](https://user-images.githubusercontent.com/81001066/163848825-78418b01-7f11-4261-afe2-e260fd44fe70.png)

Пример распознования кроссовка на фото нейронной сетью:

![image](https://user-images.githubusercontent.com/81001066/163848187-8bd806f9-c657-430a-a150-928b9e79cd00.png)

Фотография футбоки из интернета:

![image](https://user-images.githubusercontent.com/81001066/163848988-045d2980-eaea-47b0-ba35-cafbde6e2f32.png)

Пример распознования футболки на фото нейронной сетью:

![image](https://user-images.githubusercontent.com/81001066/163848241-e483ed37-c8e7-4eab-99f5-421823f40b9b.png)

Фотография пальто из интернета:

![image](https://user-images.githubusercontent.com/81001066/163849251-0a0668dd-e476-4607-9659-680990b0af3a.png)

Пример распознования пальто на фото нейронной сетью:

![image](https://user-images.githubusercontent.com/81001066/163848283-4ff69d8f-16f5-4fee-afef-f4f81bf6a10d.png)

Из полученных результатов можно сделать вывод, что нейронная сеть работает с недостаточной точностью.
Прежде всего это связано с качеством найденных фотографий. Но в любом случае она спокойной отличает фото с кроссовоком 
от фото с футболкой. А это уже какой-никакой успех!
