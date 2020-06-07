# PV_cluster
Clustering PV panels in a non-uniform array into electrical groups

This is a rewrite of the octave code used in the following paper in a jupyter notebook:
http://www.ibpsa.org/proceedings/BS2019/BS2019_210725.pdf

**Paper Abstract:**
This paper demonstrates a clustering method for grouping PVs of arbitrary orientation affected by nonuniform local shading. For a project with 44,000 PV panels cladding doubly curved roof surfaces, every panel has a unique orientation. In addition, clerestory windows cause non-uniform near-field shading. The combination of curvature and shading causes every panel to receive a different amount of irradiance at any time. The PV panel with lowest output (lowest irradiance) in a MPPT string limits the output of the whole string. The method for grouping 44,000 PV panels into 296 MPPT strings affects the total annual energy producing. The PV array grouped with clustering generated 7.7% more energy annually compared to the same array grouped in a simple grid.
