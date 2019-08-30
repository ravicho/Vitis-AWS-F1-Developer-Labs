# SDAccel AWS F1 Developer Labs


Welcome to the SDAccel AWS F1 Developer Labs. By going through these labs you will gain hands-on experience with AWS F1 and learn how to develop accelerated applications using the Xilinx SDAccel development environment.

### Prerequisites

In order to run the SDAccel AWS F1 Developer Labs, you need the following:
* An AWS account
* Access to AWS F1 instances
* Familiarity with launching an AWS EC2 F1 instance with RDP services enabled

If you need help with any of the above, follow the [**setup instructions**](./setup/instructions.md)

### Supported Versions

These labs are based on SDAccel 2018.3 available with the FPGA Developer AMI v1.6.0. Please make sure to select this version when you launch your instance. To find this AMI, search for "FPGA Developer AMI - 1.6.0" in the Community AMIs.

### Developer Lab Modules

#### Module 1 - Introduction to the SDAccel Flow
* Running the "Hello World" example
* Introduction to the SDAccel development environment
* Using the SDAccel GUI to optimize applications

[**FOLLOW THE INSTRUCTIONS**](./modules/module_01/README.md)

#### Module 2 - Developing, profiling and optimizing F1 applications with SDAccel
* Running the "Filter2D" Example

#### Module 3 - Methodology for Optimizing Accelerated FPGA Applications
* Determine the software functions to be accelerated
* Begin with a baseline design of 2D convolution of an RGBA video and a set of filter coefficients using ffmpeg
* Perform a series of optimization methods to achieve the performance target

[**FOLLOW THE INSTRUCTIONS**](./modules/module_03/README.md)

---------------------------------------

Visit the [SDAccel Developer Zone](https://www.xilinx.com/products/design-tools/software-zone/sdaccel.html) for more information about FPGA acceleration
