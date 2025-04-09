# RBFDQ-PINN
Supplementary code for the publication: "Y. Xiao, L. M. Yang, Y. J. Du, Y. X. Song, C. Shu; Radial basis function-differential quadrature-based physics-informed neural network for steady incompressible flows. Physics of Fluids 1 July 2023; 35 (7): 073607. https://doi.org/10.1063/5.0159224".
# Abstract
In this work, a radial basis function differential quadrature-based physics-informed neural network (RBFDQ-PINN) is proposed to simulate steady incompressible flows. The conventional physics-informed neural network (PINN) makes use of the physical equation as a constraint to ensure that the solution satisfies the physical law and the automatic differentiation (AD) method to calculate derivatives at collocation points. Although the AD-PINN is expedient in evaluating derivatives at arbitrary points, it is time-consuming with higher-order derivatives and may lead to nonphysical solutions with sparse samples. Alternatively, the finite difference (FD) method can facilitate the calculation of derivatives, but the FD-PINN will increase the computational cost when handling random point distributions, especially with higher-order discretization schemes. To address these issues, the radial basis function differential quadrature (RBFDQ) method is incorporated into the PINN to replace the AD method for the calculation of derivatives. The RBFDQ method equips with high efficiency in the calculation of high-order derivatives as compared with the AD method and great flexibility in the distribution of mesh points as compared with the FD method. As a result, the proposed RBFDQ-PINN is not only more efficient and accurate but also applicable to irregular geometries. To demonstrate its effectiveness, the RBFDQ-PINN is tested in sample problems such as the lid-driven cavity flow, the channel flow over a backward-facing step, and the flow around a circular cylinder. Numerical results reveal that the RBFDQ-PINN achieves satisfactory accuracy without any labeled collocation points, whereas the AD-PINN struggles to solve some cases, especially for high Reynolds number flows.
# Citation
@article{10.1063/5.0159224,
author = {Xiao, Y. and Yang, L. M. and Du, Y. J. and Song, Y. X. and Shu, C.},
title = {Radial basis function-differential quadrature-based physics-informed neural network for steady incompressible flows},
journal = {Physics of Fluids},
volume = {35},
number = {7},
pages = {073607},
year = {2023},
month = {07},
issn = {1070-6631},
doi = {10.1063/5.0159224},
url = {https://doi.org/10.1063/5.0159224},
eprint = {https://pubs.aip.org/aip/pof/article-pdf/doi/10.1063/5.0159224/18042357/073607\_1\_5.0159224.pdf},
}
