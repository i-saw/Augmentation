# Создание датасета или аугментация существующего из видео
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Aiud9kJVGT3kSlmPhDIvs7ELJg66sUqs?usp=sharing)

**Принцип действия:** 
1) Выбираем объект(ы) с помощью bounding box. Можно использовать до 10 классов;
2) Трэкер отслеживает сегментированные объекты;
3) Создается датасет для сегментации из кадров видео;
4) Датасет используется для обучения модели сегментации YOLO (если такое необходимо).
