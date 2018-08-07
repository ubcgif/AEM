.. _elements:

Elements of the Program AEM
===========================

This section provides a brief description of each program in the AEM package. In addition, we describe the file formats for all input and supporting files used by the coding library.

Program Library
---------------

The main executable programs within the AEM program library are:

    - **AEMesh:** creates an OcTree mesh based on the survey geometry
    - **AEM:** predicts data for a conductivity model

Also included are the following Octree utility programs:

    - **extract_mesh:** 
    - **interface_weights:** 
    - **create_weight_file:** creates the weighting on each cell in the model
    - **face_weights:** creates weights on the faces of cells
    - **octree_cell_centre:** computes the cell centres of each octree cell
    - **octreeTo3D:** converts and octree mesh to a 3D base mesh
    - **refine_octree:** refine the octrees
    - **remesh_octree_model:** converts the octree model to base mesh


Main Input Files
----------------

Here, we describe the main input files for executables contained with the AEM package.

.. toctree::
    :maxdepth: 2

    Create octree mesh <inputfiles/createOcTree>
    Create octree model <inputfiles/createModel>
    Forward modeling <inputfiles/forward>
    Create face weights <inputfiles/weightsFiles>
    Inversion <inputfiles/inversion>


Supporting Files
----------------

Here, we describe the formats of supporting files used to run **AEM.exe**. The input files for each executable program are described in the :ref:`running the programs<running>` section.

.. toctree::
    :maxdepth: 1

    Survey and Locations File <files/surveyFile>
    Predicted Data File <files/preFile>
    Observations File <files/obsFile>
    Topography File <files/topoFile>
    Tensor Mesh File <files/tensor_mesh>
    Octree Mesh File <files/octree_mesh>
    Model File <files/model>
    Model and Face Weights Files <files/weights>












