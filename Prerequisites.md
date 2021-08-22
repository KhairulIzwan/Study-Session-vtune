# Tutorial: Analyze Common Performance Bottlenecks with Intel® VTuneTMProfiler - C++ Sample Code (Linux* OS)

## Prerequisites

1. (Intel® VTuneTMProfiler 2021 or later)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#vtune]

2. (Intel® C++ Compiler Classic)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#compilerclassic]

**Notes**
- Installing (Intel® C++ Compiler Classic)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#compilerclassic] required (OpenCL™ Runtimes for Intel® Processors)[https://software.intel.com/content/www/us/en/develop/articles/opencl-drivers.html]
- To avoid headache and problems etc. suggested to install (Intel® oneAPI Base Toolkit)[https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html?operatingsystem=linux&distributions=webdownload&options=offline]

*remarks* : Still figure out how to solve if we wanted (Intel® C++ Compiler Classic)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#compilerclassic] standalone.

## Additional

1. (Intel® oneAPI Base Toolkit)[https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html?operatingsystem=linux&distributions=webdownload&options=offline]

## Installation Flow
1. Install (Intel® VTuneTMProfiler 2021 or later)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#vtune] standalone.

```
wget https://registrationcenter-download.intel.com/akdlm/irc_nas/18012/l_oneapi_vtune_p_2021.6.0.411_offline.sh

sudo bash l_oneapi_vtune_p_2021.6.0.411_offline.sh

echo "# vtune source" >> ~/.bashrc
echo "INSTALLDIR=/opt/intel/oneapi/vtune/2021.6.0/" >> ~/.bashrc
echo "source $INSTALLDIR/vtune-vars.sh" >> ~/.bashrc

source ~/.bashrc
```

**Notes** Installation of (Intel® VTuneTMProfiler 2021 or later)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#vtune] standalone is straightforward. No hanky panky.

2. Install (Intel® oneAPI Base Toolkit)[https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html?operatingsystem=linux&distributions=webdownload&options=offline]

```
wget https://registrationcenter-download.intel.com/akdlm/irc_nas/17977/l_BaseKit_p_2021.3.0.3219_offline.sh

sudo bash l_BaseKit_p_2021.3.0.3219_offline.sh

echo "# oneapi source" >> ~/.bashrc
echo "INSTALLDIR_ONEAPI=/opt/intel/oneapi/" >> ~/.bashrc
echo "source $INSTALLDIR_ONEAPI/setvars.sh" >> ~/.bashrc

source ~/.bashrc
```

**Notes** Go to (Get Started with the Intel® oneAPI Base Toolkit for Linux*)[https://software.intel.com/content/www/us/en/develop/documentation/get-started-with-intel-oneapi-base-linux/top/before-you-begin.html] for more functionalities and samples.
- 

3. (Intel® C++ Compiler Classic)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#compilerclassic] standalone

```
wget https://registrationcenter-download.intel.com/akdlm/irc_nas/17928/l_dpcpp-cpp-compiler_p_2021.3.0.3168.sh

sudo bash l_dpcpp-cpp-compiler_p_2021.3.0.3168.sh
```

## Useful Links
1. (Single Component Downloads and Runtime Versions)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#vtune]


**UPDATED!**
Proper way to install (Intel® VTuneTMProfiler)[https://software.intel.com/content/www/us/en/develop/articles/oneapi-standalone-components.html#vtune] with less hanky panky is by installing (Intel® oneAPI Base Toolkit)[https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html?operatingsystem=linux&distributions=webdownload&options=offline]

