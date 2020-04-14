# CPU
CPU Microarchitecture Designs

### Introduction

This repository will hold lots of various "experimental" CPU architecture and microarchitecture designs which I am currently
playing around with. These will all be toy architectures that are relatively simplistic compared to commercial CPU
architectures. The structure of the repository will be broken down into a few pieces: ISA, Microarchitecture, Components, and
Simulation.

### ISA

There will be a few different ISAs designed. Most designs will use the same ISA, since that allows for reuse of decoding
logic. However, some microarchitectures will test out most advanced features, so they effectively necessitate a more
complicated ISA.

### Microarchitecture

There will be different microarchitecture designs, which will be both prototyped in simulators and with actual Chisel or
Verilog code for synthesis.

### Simulation

Before trying to write out a hardware description to encode a particular microarchitecture, it would be useful to prototype
the design in a custom simulator. This will help in calculating performance statistics and seeing the effectiveness of the
applied techniques.
