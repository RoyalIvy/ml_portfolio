# Computer vision портфолио

## [Тестовое задание по OpenCV в компанию Mindset](https://github.com/RoyalIvy/ml_portfolio/tree/master/opencv_test_room)

Тестовое задание по преобразованию панорамного снимка помещения в 3д модель помещения для просмотра с разных ракурсов

Панорамный снимкок 
![Панорама](/opencv_test_room/src/panorama.png?raw=true)

Пример проекции

![Проекция](https://github.com/RoyalIvy/ml_portfolio/blob/master/opencv_test_room/src/perspective_4.png)

![Остальные примеры проекций](https://github.com/RoyalIvy/ml_portfolio/tree/master/opencv_test_room/src)

## [Пет-проект по классификации изображений времен года в средней полосе России](https://github.com/RoyalIvy/ml_portfolio/tree/master/season_project)

Пет-проект Machine Learning по классификации изображений по временам года

Для проекта проверялись две сверточные нейросети InceptionV3 и ResNet50. В качестве основы для классификации изображений времен года была выбрана ResNet50, так как показывала наилучшие результаты

Было произведено 6 итераций по улучшению модели и финальная версия была выложена для демострации пет-проекта. Нейросеть дообучалась на более чем 5000 изображеняй 4 классов: весна, лето, осень, зима.

Ввиду характера датасета и некоторой сложности подбора объектов для обучения максимально высокая точность составила только - 90.28%. По f1-метрике видно, что наиболее низкая точность по классу "весна", также по матрице ошибок, которая не вошла в финальную версию проекта, было замечено, что чаще всего модель ошибалась в предсказаниях изображений, которые довольно спорны с точки зрения понимания времени года, т.е. без явно характерных признаков сезона. Например фотографии поздней весны или ранней осени чаще провоцировали неточности. Однако, если брать в среднем, то точность составит чуть более 90% на тестовом наборе данных.

Если тестировать проект, лучше подбирать фотографии с явными признаками сезона и хорошим освещением.
