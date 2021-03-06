complex_mult is a  program that multiplies  two large vectors of Complex numbers and verifies the results. This program is implemented using C++ and DPC++ language for Intel CPU and accelerators.
The Complex class is a custom class and this program shows how we can use custom types of classes in a DPC++ program
  
| Optimized for                       | Description
|:---                               |:---
| OS                                | Linux Ubuntu 18.04, Windows 10 
| Hardware                          | Skylake with GEN9 or newer
| Software                          | Intel&reg; oneAPI DPC++ Compiler (beta)
| What you will learn               | Using custom type classes and offloads complex number computations to GPU using Intel DPC++
| Time to complete                  | 15 minutes  
  
## Key implementation details 
This program shows how we can use custom types of classes in a DPC++ program and explains the basic DPC++ implementation including device selector, buffer, accessor, kernel and command group.

## License  
This code sample is licensed under MIT license. 

## How to Build for CPU and GPU 

### on Linux*  
   * Build the program using Make  
    make all  

   * Run the program  
    make run  

   * Clean the program  
    make clean 

### On Windows

#### Command line using MSBuild

*  MSBuild complex_mult.sln /t:Rebuild /p:Configuration="debug"

#### Visual Studio IDE

* Open Visual Studio 2017
* Select Menu "File > Open > Project/Solution", find "complex_mult" folder and select "complex_mult.sln"
* Select Menu "Project > Build" to build the selected configuration
* Select Menu "Debug > Start Without Debugging" to run the program