# Material_calibration_raytracing
--------------------------------------------------------------------------------
This repository focuses on material calibration for wireless communication simulations, enabling accurate modeling of radio propagation in complex environments. It provides tools to define and optimize material properties, such as relative permittivity, conductivity, and scattering coefficients, ensuring physical consistency with real-world behavior. The comparison made with respect to the fake produced ground truth Using a [Sionna Link-level Simuator](<https://nvlabs.github.io/sionna/>).

# Abstract
-------------------------------------------------------------------------------------
Material calibration is a critical aspect of creating accurate and reliable digital twins, especially in wireless communication systems. Digital twins aim to replicate real-world environments virtually, where material properties like relative permittivity, conductivity, and scattering significantly influence the propagation of electromagnetic waves. Using gradient-based optimization techniques, the framework adjusts material parameters to minimize discrepancies in propagation metrics like path gain and coverage. The repository also includes methods for generating and analyzing coverage maps to validate calibrated materials, supporting advanced research in material modeling for digital twins and next-generation communication systems. In the next work, we aim to calibrate the material based on real empirical data.  

Running this code requires Sionna 0.16 or later. To run the notebooks on your machine, you also need Jupyter.

# Files
-------------------------------------------------------------------------------------
Cape town_material_learning.ipynb demonstrates how we can optimize the material in the secne compare to the defined ground truth. You need to download the cape town xml file to import the scene. You need also to downlod the meshes file. You can download it from the open street map using blender for the area defined by the coordinates (−33.921, 18.4212) to (−33.918, 18.4260). You need to add the mitsuba on blender for the export.   
