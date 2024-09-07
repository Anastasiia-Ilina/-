# - Проект посвящен задаче детекции, а именно - определению принадлежности изображению к классу "Собака" и "Кот".
В основу легла предобученная модель VGG16, в котрую был добавлен новый слой, помогающий провести бинаризацию.
Основой оценки корректости рабоыт нейронной сети стал показатель бинарной кросентропии - Log Loss.
В результате обучения нейроннйо сети был получен результат в 0,171 Log Loss.
Результат классификации отображен на итговых изображениях (Классы "0" и "1")

---

The project is dedicated to the task of detection, namely, determining whether an image belongs to the "Dog" and "Cat" classes.
It is based on the pre-trained VGG16 model, in which a new layer was added to help carry out binarization.
The basis for evaluating the correctness of neural network operations was the indicator of binary cross-entropy - Log Loss.
As a result of neural network training, a result of 0.171 Log Loss was obtained.
The classification result is displayed on the brain images (Classes "0" and "1")
