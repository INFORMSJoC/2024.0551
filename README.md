[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# TAP-mapper

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [Apache 2.0 License](LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported on in the paper 
[Optimized Noise Suppression for Quantum Circuits](https://doi.org/10.1287/ijoc.2024.0551). 
The software in this snapshot is based on 
[this SHA](https://github.com/fwgfau/tap-mapper/commit/0fc75628d865fa2d4e40f0a3fd8a47567eb477ce) 
in the development repository. 

**Important: This code is being developed on an on-going basis at 
https://github.com/fwgfau/tap-mapper. Please go there if you would like to
get a more recent version or would like support**

## Cite

To cite the contents of this repository, please cite both the paper and this repo, using their respective DOIs.

https://doi.org/10.1287/ijoc.2024.0551

https://doi.org/10.1287/ijoc.2024.0551.cd

Below is the BibTex for citing this snapshot of the repository.

```
@misc{Wagner2024,
  author =        {Friedrich Wagner and Daniel J. Egger and Frauke Liers},
  publisher =     {INFORMS Journal on Computing},
  title =         {{Optimized Noise Suppression for Quantum Circuits}},
  year =          {2024},
  doi =           {10.1287/ijoc.2024.0551.cd},
  url =           {https://github.com/INFORMSJoC/2024.0551},
  note =          {Available for download at https://github.com/INFORMSJoC/2024.0551},
}  
```

## Description

The purpose of this software is to optimize quantum circuits.
Given a quantum circuit and a hardware connectivity,
the software builds an equivalent quantum circuit which meets the connectivity restrictions
while at the same time minimizing gate count and error probability.

In addition to the software, this repository contains [data](data) collected during the experiments
as well as a [script](scripts) which supports in reproducing results.

## Building

Follow the intructions in the [src](src) directory to install the software as a python package.
If you only want to execute the [script](scripts) you can instead run
```bash
pip install scripts/requirements.txt
```

## Results

The [script](scripts) can be used to reproduce the quantum circuits used for Figure 6 in the paper.

## Ongoing Development
This code is being developed on an on-going basis at the author's
[Github site](https://github.com/fwgfau/tap-mapper).

## Support

For support in using this software, submit an
[issue](https://github.com/fwgfau/tap-mapper/issues/new).
