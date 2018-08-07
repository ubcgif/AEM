.. _running:

Running the programs
====================

This section provides describes how to run all executables pertaining to the AEM package.

.. note::

    All executable files, input files, output filenames and files specified within input files can be specified in the following manner:

    - as just the filename if contained within the current working directory (Example: *filename.txt*)
    - as a file path relative to the current working directory (Example: *sub_dir\\filename.txt*)
    - as the full path (Example: *C:\\Users\\Name\\Tests\\filename.txt*)

    Executable files should **not** be renamed. However, input file names can be specified by the user if desired.

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

Contents
--------

To learn the specifics of running each executable, see the following sections:

  .. toctree::
    :maxdepth: 1

    OcTree Mesh Generation <programs/createOcTree>
    Creating Octree Models <programs/createModel>
    Forward Modeling <programs/forward>
    Additional Cell and Face Weights <programs/weightsFiles>
    Inversion <programs/inversion>
