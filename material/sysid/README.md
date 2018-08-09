## System identification module

Material for the system identification module of the workshop

Folder contents:

1. `sysid_linsys_ls`: python notebook for linear system identification by regularized least squares
2. `sysid_rkhs`: python notebook for nonlinear system identification by kernel-based methods

### Summary

In this module we will go through some of the most popular system identification methodologies; we will start with start with identification methods for linear dynamical systems using (regularized) least squares. In particular, we will venture a detailed formulation of such least-squares problems and solve them using CVXPy - a popular tool for numerical optimization. The second part of this module will focus on the identification of nonlinear systems using the kernel trick. After a short introduction to reproducing kernel Hilbert spaces and the exposition of a few key theoretical results, we will use kernel-based method to identify nonlinear systems. We will demonstrate how powerful these methods are by identifying a chaotic system from data.


### Recommended literature


1. This is an excellent startin point: L. Ljung, System Identification: Theory for the User, Prentice-Hall, Upper Saddle River, New Jersey, 1999
2. An accessible introduction to system identification: K.J. Keesman, System identification: an introduction, Springer, 2011
3. A more modern approach to system identification using kernel methods: G. Pillonetto, F. Dinuzzo, T. Chen, G. De Nicolao and L. Ljung, Kernel methods in system identification, machine learning and function estimation: a survey, Automatica 50(1):657-682, 2014
4. P. Van den Hof, Closed-loop issues in system identification, Annual Reviews in Control 22:173-186, 1998



### Competition

The workshop will be concluded by a competition which will feature three tasks, one for each module. For the system identification module, participants will identify an unknown nonlinear system using input-output data.