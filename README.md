# GNN-based Reduced OPF Model
This work implements multiple ML models including GNN to identify a subset of critical lines to be monitored in OPF models, leading to size-reduced OPF models.

This set of codes/data implements our NAPS paper "Reduced Optimal Power Flow Using Graph Neural Network". DNN, CNN and GNN are used to reduce constraints mainly line thermal limit constraints for OPF.


## Python Environment:
Codes are implemented in Python, using Jupyter Notebook. ML model uses Tensorflow and Spektral (GNN) libraries. Optimization is implemented using Pyomo in python. A solver is required for pyomo to run.

To run the program, you may need to have the data files replaced in the proper folder.


## Test Power Systems
The following test power system was used in this work:
1. IEEE 73-bus system: the original data of this test system are described in this reference: "The IEEE Reliability Test System-1996. A report prepared by the Reliability Test System Task Force of the Application of Probability Methods Subcommittee" and link is <a class="" target="_blank" href="https://ieeexplore.ieee.org/document/780914">here</a>.


## Citation:
If you use any of our codes/data for your work, please cite the following papers as your reference:

Thuan Pham and Xingpeng Li, “Reduced Optimal Power Flow Using Graph Neural Network”, *North American Power Symposium*, Salt Lake City, UT, USA, Oct. 2022. 

Paper website: https://rpglab.github.io/papers/ThuanP-GNN-ROPF/


## Contributions:
Thuan Pham developed this set of programs/data. Xingpeng Li supervised this work.


## Contact:
Dr. Xingpeng Li

University of Houston

Email: xli83@central.uh.edu

Website: https://rpglab.github.io/


## License:
This work is licensed under the terms of the <a class="off" href="https://creativecommons.org/licenses/by/4.0/"  target="_blank">Creative Commons Attribution 4.0 (CC BY 4.0) license.</a>


## Disclaimer:
The author doesn’t make any warranty for the accuracy, completeness, or usefulness of any information disclosed; and the author assumes no liability or responsibility for any errors or omissions for the information (data/code/results etc) disclosed.