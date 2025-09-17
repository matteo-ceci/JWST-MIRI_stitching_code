# JWST-MIRI_stitching_code
This software accompanies the submitted A&A article 'MIRACLE II: Unveiling the multi-phase gas interplay in the circumnuclear region of NGC 1365 via multi-cloud modeling', arXiv:2507.08077. 

This notebook presents a step-by-step implementation of the **stitching and correction procedure** developed within the **Mid-IR Activity of Circumnuclear Line Emission** (**MIRACLE**; JWST GO program 6138; Co-PIs: C. Marconcini and A. Feltre). The method includes:  

- corrections to the World Coordinate System (WCS),  
- reprojection onto a common spatial grid,  
- interpolation onto a uniform spectral axis,  
- stitching of multiple MIRI segments into a single datacube,  
- and a flux correction through continuum fitting across overlapping regions.  

This procedure ensures a continuous combination of all MIRI channels into a homogeneous datacube, enabling robust spectral and spatial analysis.  

If you use it for published research, you are requested to cite the paper that describes the procedure, https://arxiv.org/pdf/2507.08077.
