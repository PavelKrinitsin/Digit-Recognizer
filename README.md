# *Digit Recognizer*
**Educational task on building a classifier for handwritten digit images based on the MNIST dataset**
<p align="center">
    <img src="https://github.com/PavelKrinitsin/Classification-of-bearings/blob/main/1.jpg" width="300">
</p>

## Description
Целью данной работы является исследование способа решения проблемы снижения срока службы подшипников качения, установленных на промышленном оборудовании, в результате их некачественной смазки в процессе эксплуатации. 
В работе рассматривается метод классификации состояний подшипников в зависимости от их диагностических параметров: различных показателей вибрации и температуры. Классификация осуществляется методами классического машинного обучения: методами KNN, RandomForestClassifier, SVM с целью выявления наилучших показателей точности модели. В процессе проведения исследования выполнен анализ влияния каждого из диагностических параметров – признаков на показатели работы алгоритмов модели классификации. Полученная модель позволяет качественно, с 98% точностью, производить оценку состояния смазки подшипников качения и выдавать рекомендации по проведению своевременного сервисного обслуживания оборудования. 


The purpose of this work is to explore a method for solving the problem of reduced service life of rolling bearings installed on industrial equipment due to their poor lubrication during operation. 
This work examines a method for classifying the conditions of bearings depending on their diagnostic parameters: various indicators of vibration and temperature. Classification is carried out using traditional machine learning methods: KNN, RandomForestClassifier, SVM methods with the aim of identifying the best model accuracy indicators. During the research, an analysis of the impact of each diagnostic parameter – features on the performance indicators of the classification model algorithms was performed. The obtained model allows for a quality, 98% accuracy, assessment of the condition of rolling bearing lubrication and provides recommendations for timely maintenance of equipment.

___

## Results
Все три модели показали удовлетворительный результат обучения и могут быть применены в качестве практической модели классификации подшипников по состоянию их смазки:
1.  Модель RandomForestClassifier показала наиболее высокие результаты классификации как на тестовых, так и на тренировочных данных. На тестовых данных ее ошибка не превышает 2%;
2.  Наиболее значимым признаком для предсказания целевой переменной "Bearing State" у всех трех моделей оказался признак V-rms - показатель виброскорости (м/с).


All three models showed satisfactory training results and can be applied as a practical model for classifying bearings based on the condition of their lubrication:
1. The RandomForestClassifier model demonstrated the highest classification results on both test and training data, with an error rate on the test data not exceeding 2%.
2. The most significant feature for predicting the target variable "Bearing State" in all three models was the V-rms feature - a measure of vibration velocity (m/s).


___

## Tags
Python, Machine Learning, Classification tasks
