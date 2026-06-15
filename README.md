This repo contains the corresponding code for the paper Quantifying Crop Disease Trait Dynamics through
Longitudinal Imaging and Temporal Analytics by Ewen et al.
The corresponding sample dataset is availible at https://greenskeye.usask.ca/speedbreeding/

The repository includes the Jupyter notebooks necessary to run the computational
pipeline of the paper. A sample workflow within each file is provided.

The suggested order of notebooks highlighted by the workflow for raw images is:

[Preprocessing](preprocess.ipynb) --> [Segmentation](segment_anything.ipynb) --> [Colour and Quantitative Analysis](rust_analysis_workflow.ipynb) --> [AUDPC](AUDPC.ipynb) 
