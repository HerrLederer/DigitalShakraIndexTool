# Digital Shakra Index Tool
Static binary checker against bad spirits in your binaries and files.


## Background
Improper balance of instructions, too many uneven jump addresses, excessive use of assignments and a non-harmonic use of text segment cause software to have too many bad spirits, stressing users and equipment as well as tending towards too many crashes or other malfunctions.

With the Digital Shakra Index Tool you can get an evaluation of binaries and files with an index of 10 being perfect while 0 leaving you with a terrible Digital Shakra Index.

Our recommmendation: Add this tool as one of your CI/CD stages along with your linters and other static code checking tools.
Make it reject any commit that causes the binaries being unbalanced and having a Digital Shakra Index below 6.

## Usage

> DigitalShakraIndexTool.exe < filename >

## Results
Digital Shakra Index may Range from 0 to 10. 

### Index: 0
This piece of software is totally inbalanced. Expect crashes and a lot of CPU wear. You should not even think about executing it.

### Index: 4
Binaries with an Index of 4 are known for their problematic behaviour. A lot of software makers who didn't spend attention on this ended up with a bad reputation. Products of this Shakra Index include FrameMaker, SAP UI,  Rational Doors classic and many Open Source web frameworks.

### index: 6 

This Index should be the lowest that you might accept for your binary. It will still not be harmonic in its shape and will cause sublte stress to the user.

### Index: 8

8 While not being perfect yet, your piece of software is already in a good shape. No CPU wear to be expected and crashes are unlikely, but might still happen every now and then.

### Index: 10

Congratulations, this binary is in perfect shape without any bad spirits.

## Why are there no sources?

We spent months and years on the engineering to figure out the effects of compiler, assembler and linker versions and their parametrization.
Just compiling it on your own will have a severe impact on the Shakra Index of the tool, so we specially optimized it for you to ensure you get the correct values, provided by a binary that is free of bad spirits.

