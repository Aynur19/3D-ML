# Procedural and Neural Rendering (3D ML)
[Read in Russian](README-ru.md)

## Lab 1
### Tasks:
1. Select and download a 3D model in **.obj** format for further work with it
2. Convert your 3D model to different presentation forms: 
    - Polygonal mesh
    - Point cloud
    - Voxel representation with different sampling rates
    - Sampled point clouds
    - SDF model
3. Render views. 
4. There should also be photographs of the 3D model from different angles.		

### Jupyter Notebooks
1. [ModelRenderingToMesh.ipynb](Notebooks/ModelRenderingToMesh.ipynb): 
    - loading model format **.obj**
    - converting model to mesh
    - render mesh with **Trimesh**, **Polyscope**, **Open3D**
    - adding noise and filtering the mesh with **Open3D**
2. [ModelRenderingToVoxel.ipynb](Notebooks/ModelRenderingToVoxel.ipynb):
    - loading model format **.obj**
    - converting model to mesh
    - converting mesh to voxel representations with different sampling rates using **Trimesh**
3. [Pytorch3D. 3D model rendering.ipynb](Notebooks/Pytorch3D.%203D%20model%20rendering.ipynb):
    - loading model format **.obj**
    - converting model to mesh, rendering
    - converting the mesh to a sampled point cloud, rendering
    - all transformations are done with **PyTorch3D**
    - it is recommended to run in **Google Colab** or **Kaggle**

### Results
1. [Geralt. Mesh Rendering Result (PyTorch3D)](Results/Geralt.%20Mesh%20Rendering%20Result.mp4) - the result of rendering the projected model to the mesh (PyTorch3D)
2. [Geralt. Point Cloud Rendering Result (PyTorch3D)](Results/Geralt.%20Point%20Cloud%20Rendering%20Result.mp4) - the result of rendering the projected model into a sampled point cloud (PyTorch3D)


