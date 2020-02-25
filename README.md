# From Zero-to-Devito
## Rice OGHPC workshop Wednesday, March 4 (8:15 AM – 3:45 PM): 

* Presented by: Dr. Gerard Gorman, Dr. Fabio Luporini, Dr. Rhodri Nelson, Mr. Navjot Kukreja, Imperial College London
* Conference website: https://rice2020oghpc.rice.edu
* Includes breakfast, morning break, lunch, and afternoon break.

The [Devito](https://www.devitoproject.org/) workshop will consist of a hands-on morning session where participants will learn how to implement finite difference and inverse solvers using Devito. We will provide access to Microsoft Azure VM's with Devito and JupyterHub. Alternatively participants should preinstall Devito on their laptops using the install [instructions provided](https://github.com/devitocodes/devito). 

The afternoon session will be run hackathon style, giving experienced HPC developers the opportunity to develop the Devito JIT-escape hatch (ie directly customising the Devito generated source code), where the target problem is performance optimisation of Devito on GPU processors running on Azure Cloud.  

## Morning: Primer in solving PDE's and inverse problems with Devito
Minimum requirements and prerequisites:
* Laptop with a browser
* Basic Python programming knowledge
* Basic knowledge of finite differences

The format will be roughly as follows:
* Introduction to the Devito (60 mins)
    * The Devito DSL
    * Building differential operators
* Building parallel wave-propagators (60 mins)
    * Source and receivers
    * MPI
    * Boundary conditions
* Gradient calculation via backpropagation (45 mins)
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
