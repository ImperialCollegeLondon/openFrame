# Introduction to _openFrame_

This repository hosts information and instructions associated with the modular _openFrame_ microscope, a cost-effective platform based on open-hardware core components that can be configured or adapted to most light microscopy techniques and is intended to be used with open-source software, making instruments straightforward to maintain and to upgrade. _openFrame_ microscopes are based on stackable cylindrical aluminium layers centred on an optical axis that can accommodate a range of generic or specialised microscope components and which are ready to be mounted to external components such as optical cage systems. 
We are licensing the core _openFrame_ components under under the permissive version of the CERN Open Hardware License Version 2 ([https://ohwr.org/cern_ohl_p_v2.pdf](https://ohwr.org/cern_ohl_p_v2.pdf)), including the component designs hosted on this repository. We do not wish to restrict users in their ability to utilise _openFrame_ components and, as well as supporting the assembly of open instrumentation, openFrame components can be used with closed-source and proprietary technologies

Please see the ["How to cite openFrame" file](https://github.com/ImperialCollegeLondon/openFrame/blob/main/HOW%20TO%20CITE%20OPENFRAME.md) for information on how to cite _openFrame_

For further information on the modules that make up openFrame and associated information, please check the [wiki](https://github.com/ImperialCollegeLondon/openFrame/wiki) for this repository. 

## Where to find information

### [CAD designs](https://github.com/ImperialCollegeLondon/openFrame/tree/main/openFrame%20CAD)
The CAD files for the _openFrame_ components licensed under the permissive version of the CERN Open Hardware License Version 2 can be found in the folder called [_openFrame_ CAD](https://github.com/ImperialCollegeLondon/openFrame/tree/main/openFrame%20CAD). The [_openFrame_ part description PDFs](https://github.com/ImperialCollegeLondon/openFrame/tree/main/openFrame%20part%20description%20PDFs) folder contains important information such as hole tapping data, as well as suggested specification information relevant for fabrication of these components. 

### [Assembly instructions](https://github.com/ImperialCollegeLondon/openFrame/wiki)
As they become available, assembly instructions for creating an openFrame-based epifluorescence microscope will be found in the [wiki](https://github.com/ImperialCollegeLondon/openFrame/wiki) for this repo. Please note that as the system is modular and extensible, a much larger range of configurations are possible, but it is not feasible to document the assembly of every possible permutation. 

### Software
We make extensive use of [Micro-Manager](https://micro-manager.org/Version_2.0) to control _openFrame_ instrumentation but understand that this may not always be the first choice of all users or developers. Micro-Manager uses the Lesser GPL license ([https://www.gnu.org/licenses/lgpl-3.0.en.html](https://www.gnu.org/licenses/lgpl-3.0.en.html)) for its core and the BSD 2-clause license ([https://opensource.org/license/bsd-2-clause/](https://opensource.org/license/bsd-2-clause/)) for the GUI and device adapters, and any 
Micro-Manager device adapters we have written (for the openFrame hardware components licensed under the permissive version of the CERN Open Hardware License Version 2 in this repository) are licensed under the BSD 2-clause license.

Any other software for the open-source components _openFrame_ hardware components licensed under the permissive version of the CERN Open Hardware License Version 2 in this repository is licensed under the BSD 2-clause license ([https://opensource.org/license/bsd-2-clause/](https://opensource.org/license/bsd-2-clause/)). 

### Acknowledgements
The _openFrame_ is a compact, modular, open-source microscope conceived by Paul French and developed with colleagues from the [Photonics Group](https://www.imperial.ac.uk/photonics/) at [Imperial College London](https://www.imperial.ac.uk/), and then designed, supported, and extended in collaboration with [Cairn Research](https://www.cairn-research.co.uk/). The first prototype _openFrame_ microscope was co-designed and fabricated by Simon Johnson and Martin Kehoe in the Optics instrumentation facility of the Physics Department at Imperial College London with input. Subsequently the design and implementation were refined in a collaboration with Cairn Research Ltd by Frederik Görlitz and Sunil Kumar at Imperial supervised by Paul French, working with Callum Hollick at Cairn supervised by Jeremy Graham. Callum Hollick fabricated subsequent prototypes and designed the current version of core _openFrame_ components, which are represented in these CAD files. 
