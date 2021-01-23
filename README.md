# netology_ds_diploma_project
Diploma project of Netology Data Scientist Specialization

-= Разработка модели распознавания качества продукта =-

Выбран один из дефектов в исходном изображении.

Создан датасет из 245 исходных изображений и 245 соответствующих масок. 

Подобран алгоритм для определения наличия этого дефекта.

Алгоритм: семантическая сегментация с помощью свёрточной сети U-Net.

Для U-Net характерно:

• достижение высоких результатов в различных реальных задачах, особенно для биомедицинских приложений;

• использование небольшого количества данных для достижения хороших результатов.

Дополнительное преимущество сети U-Net достигается с помощью тюнинга:

• аугментация
• BatchNormalization
• Conv2DTranspose

data - сюда помещаются предобработанные данные (размеченные в программе labelstud.io и )

docs - документы

figures - рисунки, использованные в аналитическом отчёте и презентации

jupyter notebook - рабочие ноутбуки

project report - дипломный проект в форме аналитического отчёта, презентация
