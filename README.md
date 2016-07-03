# LASAN
The Lightweight Authentication for Secure Automotive Networks (LASAN) is an authentication and authorization framework for automotive scenarios. The details will be published in: Philipp Mundhenk, Andrew Paverd, Artur Mrowca, Sebastian Steinhorst, Martin Lukasiewycz, Suhaib A. Fahmy and Samarjit Chakraborty. "A System Level Design Approach to Authentication and Authorization in Automotive Networks". In: ACM Transactions on Design Automation of Electronic Systems (TODAES).

This repository contains intermediate and final results necessary to reproduce the measurements and conclusions  described in the above paper.

##Parameters
This directory contains the basic parameter set for the IVNS, found on an STM32F415 microcontroller.

##Performance
This directory contains the summarized latency measurements for multiple different authentication frameworks. All results have been achieved with the IVNS (https://github.com/PhilippMundhenk/IVNS). All measurements are based on the parameter sets above, thus simulating and STM32F415 microcontroller. Due to storage space considerations, only the summarized results have been added. The folders structure is as follows:
\<Framework under Test\>/\<Crypto Library\>/\<HW Acceleration\>

##Verification
This directory contains the Scyther files required for verifying the ECU authentication and stream authorization protocols.
