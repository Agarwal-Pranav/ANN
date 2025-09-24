**Artificial Neural Network (ANN) Design**

This repository contains an ANN design featuring multiple fully connected layers. Each neuron in the network utilizes Multiply & Accumulate (MAC) operations, performed using a 32-bit IEEE 754 standard floating-point Arithmetic Logic Unit (ALU).

**Features**

Multi-layer Architecture: Easily configurable number of fully connected layers.
Neurons with MAC Operations: Each neuron executes MAC operations for efficient computation.
Floating-point Precision: All operations utilize 32-bit IEEE 754 floating-point arithmetic for accuracy.
Modular Code Structure: Individual blocks are provided for flexible assembly and experimentation.

**Usage**

Integrate the provided modules to construct your own neural network architecture.
Customize the number of layers and neurons per layer as per your requirements.

**What is IEEE 754?**

IEEE 754 is the standard for floating-point computation, established by the Institute of Electrical and Electronics Engineers (IEEE). It defines formats for representing floating-point numbers and rules for arithmetic operations, rounding, and special values like infinity and NaN (Not a Number).

**32-bit Floating-Point Format (Single Precision)**

A 32-bit floating-point number (often called “single precision”) is divided into three parts:

1 bit for the sign: Indicates whether the number is positive (0) or negative (1).
8 bits for the exponent: Encodes the exponent, using a bias of 127.
23 bits for the fraction (mantissa/significand): Contains the significant digits of the number.
