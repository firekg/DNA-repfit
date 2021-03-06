# Demo for fitting DNA replication fraction data

## Origin and usage
* This repository contains a modified subset of the code used for [Modeling genome‐wide replication kinetics reveals a mechanism for regulation of replication timing](http://msb.embopress.org/content/6/1/404). Scott Cheng-Hsin Yang, Nicholas Rhind, and John Bechhoefer. Molecular Systems Biology 6:404 (2010).
* The code is good for fitting time-course replication fraction.
* Original fitting was done in Igor Pro 6 on Windows.
* The folder **FasterMicroArrayFitFunc** contains an implementation of the main fitting function in c. These were used for the genome-wide fit.
* In function fastfxt(...), the comment label "diff" marks new changes compare to original code.

## Warning
* The following instructions have been tested only for an MIM fit to fake data on Igor Pro 7.0 (Mac).

## Getting started
* Download, install, and open [Igor Pro](https://www.wavemetrics.com/support/demos.htm).
* In Igor, Windows --> New --> Procedure.
Copy the content of **fit_microarray.txt** into the procedure file. Click the **Compile** button.
* In Igor, Windows --> New --> Notebook.
Copy the content of **fit_notes.txt** into the notebook file.
* Follow instructions in notebook.
