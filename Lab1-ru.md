# Процедурная визуализация и нейронный рендеринг
[Read in English][en]

## Лабораторная работа 1. "Преобразование и визуализация 3D модели в различных форматах"


## Задачи
1. Выбрать и загрузить 3D модель в формате **.obj** для дальнейшей работы с ней.
2. Преобразовать свою 3D модель в разные формы представления и дальнейшая визуализация. Форматы представления: 
    - Полигональный меш
    - Облако точек
    - Сэмплированное облака точек
    - Воксельное представление с разной частотой дискретизации
    - SDF модель
3. Также должны быть фотографии 3D модели с разных ракурсов.	


## Решение
### 1. Выбор модели 
Для работы по данному курсу выбраны 2 модели - персонажи компьютерной игры **"Ведьмак: Дикая Охота"**: [**Геральт из Ривии** и **Йеннифэр из Венгерберга**][models-ru]

### 2. Преобразование модели в различные форматы и визуализация 

Данная работа осуществлялась с помощью следующих библиотек и программ: 
- **[Trimesh]**
- **[Open3D]**
- **[Polyscope]**
- **[PyTorch3D]** (использовались сервисы **[Google Colab]** и **[Kaggle]**)

Реализация **Jupyter Notebook**-ах преобразования модели в разные форматы и дальнейшей визуализации:

|Фомат|[PyTorch3D Rendering]|Trimesh|Open3D|Polyscope|
|---|---|---|---|---|
|Mesh|![PyTorch3D_GeraltMesh]||||
|Point Cloud|![PyTorch3D_GeraltPC]||||
|Sampled Point Cloud|![PyTorch3D_GeraltSPC]||||
|Voxel|||||
|SDF|[random value]||||


---
[PyTorch3D Rendering]: Notebooks/Pytorch3D.%203D%20model%20rendering.ipynb
[PyTorch3D_GeraltMesh]: Results/Pytorch3D.%20Mesh%20Rendering%20(Geralt).gif
[PyTorch3D_GeraltPC]: Results/Pytorch3D.%20Point%20Cloud%20Rendering%20(Geralt).gif
[PyTorch3D_GeraltSPC]: Results/Pytorch3D.%20Sampled%20Point%20Cloud%20Rendering%20(Geralt).gif

[Trimesh]: https://trimsh.org/
[Open3D]: http://www.open3d.org/
[Polyscope]: https://polyscope.run/py/
[PyTorch3D]: https://pytorch3d.org/
[Google Colab]: https://colab.research.google.com/
[Kaggle]: https://www.kaggle.com/

[models-ru]: Models3D/README-ru.md
[models]: Models3D/README.md

[ru]: Lab1-ru.md
[en]: Lab1.md

