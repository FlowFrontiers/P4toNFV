# P4toNFV: Offloading from P4 Switches to NFV in Programmable Data Plane

Welcome to the supporting page for the manuscript titled, "*P4toNFV: Offloading from P4 Switches to NFV in Programmable Data Planes*."

The paper delves into the potential of offloading intricate traffic processing from programmable P4 switches to network function virtualization (NFV). We specifically explore the merits of P4 switches, their inherent constraints, and how NFV can be a powerful tool to address complex processing challenges these switches face. Central to our exploration is a rigorous offloading optimization mechanism within delay constraints. By employing an M/M/1 queuing model and the Bounded version of Brent's method for optimization, we provide a granular understanding of a P4 switch's attributes under the guidance of an SDN controller, coupled with NFV offloading capabilities. Our findings offer pivotal insights into the offloading rate that notably minimizes packet processing delay.

In the spirit of promoting reproducibility, transparency, and to champion the cause of open science, the scripts used in our experiments are openly accessible to the community. These resources are meticulously crafted to provide a deeper understanding of the methodologies employed, and we hope they serve as a foundation to spur further investigations in this domain.

## Repository Structure:

- [1-offloading-optimisation.ipynb:](1-offloading-optimisation.ipynb) This Jupyter notebook contains scripts related to delay analysis and optimization techniques we employed in our manuscript.
- [2-parametric-sensitivity-impact-analysis.ipynb:](2-parametric-sensitivity-impact-analysis.ipynb) Dive into this Jupyter notebook for scripts pertinent to our parametric sensitivity impact analysis.

The Jupyter notebooks are designed to be self-explanatory, guiding the reader through each step of the process. However, if any issues are encountered or something is unclear, it is encouraged to raise an issue on GitHub. Contributions to the improvement of this repository are greatly appreciated.

##

Feel free to fork, star, or contribute to this repository. For any queries or if you encounter issues, kindly raise them in the "Issues" section, and we'll get back to you as promptly as we can.
