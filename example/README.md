# Example

This directory contains two PDF files reporting on the internal structure of an HDF5 file produced by this version of OpenFOAM.It should be noticed that the structure is virtually identical to the standard file structure produced by standard OpenFOAM.

In order to reduce the number of HDF5 files created and also to allow the deletion of individual time dumps, it was essential to have an HDF5 file for each time dump containing information from all processes for that time dump.

This version of OpenFOAM was run on 8 processes and produced a number of time dumps.  The time dump at 1 second is reported here.

File name | Description | Generated by
------ | ----- | --------
[1.h5.zip](https://github.com/stefsal/OeRC_OpenFOAM_HDF5/blob/master/example/1.h5.zip) |  file 1.h5 (zipped)  |  
[HDF5_struct_short.pdf](https://github.com/stefsal/OeRC_OpenFOAM_HDF5/blob/master/example/HDF5_struct_short.pdf) |   structure of 1.h5 (no data) | h5ls -r 1.h5
[HDF5_struct_long.pdf](https://github.com/stefsal/OeRC_OpenFOAM_HDF5/blob/master/example/HDF5_struct_long.pdf) |  structure and attributes of 1.h5 (no data) | h5dump -A 1.h5
