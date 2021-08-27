# FDMIC_Geodynamics
Basic Finite difference / Marker-In-Cell code for teaching purposes.

# Stokes solver
The script [Mechanics_v11_SolVI_ViscousInclusionTest.jl](./Mechanics_v11_SolVI_ViscousInclusionTest.jl) produces first order L2 convergence of velocity and pressure using the SOLVI tests:

<!-- ![](/images/SOLVI_Julia.png) -->
<center><img src="/images/SOLVI_Julia.png" alt="drawing" width="500"/></center>

# Power-law Stokes flow + advection

The script [Mechanics_v11_MultiLayerExt.jl](./Mechanics_v11_MultiLayerExt.jl) allows to model multi-layer necking instabilities:

![](/images/MLPS_Julia.png)

<!-- ![](/images/MultiLayerExtension.gif) -->
<center><img src="/images/MultiLayerExtension.gif" alt="drawing" width="600"/></center>

# Periodic simple shear Stokes flow + advection

With [Mechanics_v11_PeriodicSimpleShear.jl](./Mechanics_v11_PeriodicSimpleShear.jl) one can model periodic shear deformation.

<!-- #![](/images/Periodic_Julia.png) -->

<!-- ![](/images/PeriodicSimpleShear.gif) -->
<center><img src="/images/PeriodicSimpleShear.gif" alt="drawing" width="600"/></center>

# Compressible layer under layer parallel compression

&#8594; Pressure build-up

This can be reproduced with [Mechanics_v11_CompressibleLayer.jl](./Mechanics_v11_CompressibleLayer.jl)
See the paper of [Moulas et al., 2018] (https://onlinelibrary.wiley.com/doi/abs/10.1111/jmg.12446 "Moulas et al., 2018") for more details.

<!-- ![](/images/CompressibleLayer.gif) -->
<center><img src="/images/CompressibleLayer.gif" alt="drawing" width="600"/></center>

