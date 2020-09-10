# scalePut Utility
This utility was developed by [ATA Engineering](http://www.ata-e.com) to use
with the put files generated by Loci/CHEM. This can be useful when attempting
to modify the variables in a put file to use with another simulation. The flow variables and coordinates within the put file can be scaled by user input parameters.

# Dependencies
This python utility requires the h5py and argparse libraries.

# Usage
Detailed usage can be found by passing the script the **-h** or **--help** 
options. The put file to mirror and the plane to mirror about can be specified 
on the command line.

```
scalePut -h
```
```
scalePut -f put.0_myCase -p 1.5
```
