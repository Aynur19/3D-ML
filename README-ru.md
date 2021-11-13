# Процедурная визуализация и нейронный рендеринг (3D-ML)
[Читать на английском](README.md)

## Лабораторная работа №1
### Задачи:
1. Выбрать и загрузить 3D-модель в формате .obj для дальнейшей работы с ней
2. Преобразовать свою 3D-модель в разные формы представления: 
 - Полигональный меш
 - Облако точек
 - Воксельное представление с разной частотой дискретизации
 - Сэмплированные облака точек
 - SDF-модель
3. Визуализировать представления. 
4. Также должны быть фотографии 3D-модели с разных ракурсов.		

### Программы с решениями
1. [ModelRenderingToMesh.ipynb](Notebooks/ModelRenderingToMesh.ipynb): 
    - загрузка модели формата **.obj**
    - преобразование меша из модели
    - визуализация меша с помощью **Trimesh**, **Polyscope**, **Open3D**
    - добавление шума и применение фильтрации для меша с помощью **Open3D**
2. [ModelRenderingToVoxel.ipynb](Notebooks/ModelRenderingToVoxel.ipynb):
    - загрузка модели формата **.obj**
    - преобразование модели в меша
    - преобразование меша в воксельное представления с разной частотой дискретизации с помощью **Trimesh**
3. [Pytorch3D. 3D model rendering.ipynb](Notebooks/Pytorch3D.%203D%20model%20rendering.ipynb):
    - загрузка модели формата **.obj**
    - преобразование модели в меш, визуализация
    - преобразование меша в сэмплированное облако точек, визуализация
    - все преобразования выполнены с помощью **PyTorch3D**
    - рекомендуется запускать в **Google Colab** или **Kaggle**

### Результаты
1. [Geralt. Mesh Rendering Result (PyTorch3D)](Results/Geralt.%20Mesh%20Rendering%20Result.mp4) - результат рендеринга проеобразованной модели в меш (PyTorch3D)
2. [Geralt. Point Cloud Rendering Result (PyTorch3D)](Results/Geralt.%20Point%20Cloud%20Rendering%20Result.mp4) - результат рендеринга проеобразованной модели в сэмплированное облако точек (PyTorch3D)

<video width="320" height="240" controls>
  <source src="Results/Geralt.%20Mesh%20Rendering%20Result.mp4" type="video/mp4">
</video>

## Лабораторная работа №2

## Лабораторная работа №3