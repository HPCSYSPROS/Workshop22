# An Automated Approach to Continuous Acceptance Testing of HPC Systems at NERSC

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7320179.svg)](https://doi.org/10.5281/zenodo.7320179)

**Authors**
* Shahzeb Siddiqui, Lawrence Berkeley National Laboratory (LBNL)
* Erik Palmer, Lawrence Berkeley National Laboratory (LBNL)
* Sameer Shende, University of Oregon
* Wyatt Spear, University of Oregon
* Prathmesh Sambrekar, Arizona State University
* Sijie Xiang, Carnegie Mellon University

**Abstract:**
We demonstrate a continuous acceptance testing strategy used at NERSC that can be implemented in the broader HPC community. To accomplish this task, we designed a new framework that can handle the complex parts of HPC systems, allowing us to verify a system is working optimally. buildtest [1] is an acceptance testing framework that can automate the testing of HPC systems and enable HPC support teams to painlessly create and run tests. Testing is initiated by changes to the system/software stack at scheduled system outage that demands for NERSC staff to build, run and monitor test results using GitLab’s Continuous Integration (CI) [2]. Test results are clearly communicated to developers and users via the CDash [3] web interface and test failures are documented as github issues. Together this framework forms a robust method for verifying cutting edge software stacks’ function in challenging HPC environments.
