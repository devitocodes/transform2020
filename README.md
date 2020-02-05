# Rice OGHPC workshop 4th March 2020: From Zero-to-Devito

The [Devito](https://www.devitoproject.org/) workshop will consist of a hands-on morning session where participants will learn how to implement finite difference and inverse solvers using Devito. We will provide access to Microsoft Azure VM's with Devito and JupyterHub. Alternatively participants should preinstall Devito on their laptops using the install [instructions provided](https://github.com/devitocodes/devito). 

The afternoon session will be run hackathon style, giving experienced HPC developers the opportunity to develop the Devito JIT-escape hatch (ie directly customising the Devito generated source code), where the target problem is performance optimisation of Devito on GPU processors running on Azure Cloud.  

## Morning: Primer in solving PDE's and inverse problems with Devito
Minimum requirements and prerequisites:
* Laptop with a browser
* Basic Python programming knowledge
* Basic knowledge of finite differences

* Introduction to Devito (15 mins)
* Implementing finite difference solvers (60 mins)
 * Differential operators
 * Boundary conditions
 * Source and receivers
 * MPI
* Benchmarking and performance turning (30 mins)
* Gradient calculation via backpropogation (30 mins)
* Basic FWI with SciPy and Dask (30 mins)
* Wrap-up and Q&A (15 mins)

## Afternoon: Devito for HPC developers
Minimum requirements and prerequisites:
* Laptop with a browser
* Experience with Git
* C/C++ programming experience
* OpenMP programming experience

* Devito GPU roadmap (15 min)
* Exploiting the Devito JIT-escapehatch (15 mins)
* GPU hackathon (2 hrs)
  * OpenMP 5 offloading - multiple architectures
  * OpenACC offloading
* Performance prizes and wrap-up.
