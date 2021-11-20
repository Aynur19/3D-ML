# Procedural and Neural Rendering
[Read in Russian][ru]

## Laboratory work 1. "Conversion and visualization of 3D models in various formats"

## Tasks
1. Select and download a 3D model in **.obj** format for further work with it.
2. Convert your 3D model into various forms of presentation and further visualization. Presentation formats:
    - Polygonal mesh
    - Point cloud
    - Sample point clouds
    - Voxel representation with different sampling rates
    - SDF model
3. There should also be photographs of the 3D model from different angles.


## Solution
### 1. Model selection
For work on this course, 2 models have been selected - the characters of the computer game **"The Witcher: Wild Hunt"**: **[**Geralt from Rivia** and **Yennefer from Vengerberg**][models]

### 2. Model conversion and rendering

This work was carried out using the following libraries and programs:
- **[Trimesh]**
- **[Open3D]**
- **[Polyscope]**
- **[PyTorch3D]** (used services **[Google Colab]** and **[Kaggle]**)

Implementation of **Jupyter Notebook** model transformation into different formats and further rendering:

|Format|[PyTorch3D Rendering]|Trimesh|Open3D|Polyscope|
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