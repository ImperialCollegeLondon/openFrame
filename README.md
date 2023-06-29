# Introduction to openFrame

This repository hosts information and instructions associated with the modular openFrame microscope, a cost-effective platform based on open-hardware core components that can be configured or adapted to most light microscopy techniques and is intended to be used with open-source software, making instruments straightforward to maintain and to upgrade. openFrame microscopes are based on stackable cylindrical aluminium layers centred on an optical axis that can accommodate a range of generic or specialised microscope components and which are ready to be mounted to external components such as optical cage systems. 
We are licensing the core openFrame components under under the permissive version of the CERN Open Hardware License Version 2 ([https://ohwr.org/cern_ohl_p_v2.pdf](https://ohwr.org/cern_ohl_p_v2.pdf)), including the component designs hosted on this repository. We do not wish to restrict users in their ability to utilise openFrame components and, as well as supporting the assembly of open instrumentation, openFrame components can be used with closed-source and proprietary technologies

## Where to find information

### CAD designs
The CAD files for the openFrame components licensed under the permissive version of the CERN Open Hardware License Version 2 can be found in the folder called “CAD”. This folder also contains suggested specifications for fabrication of these components. 

### [Assembly instructions](https://github.com/ImperialCollegeLondon/openFrame/wiki)
As they become available, assembly instructions for creating an openFrame-based epifluorescence microscope will be found in the [wiki](https://github.com/ImperialCollegeLondon/openFrame/wiki) for this repo. Please note that as the system is modular and extensible, a much larger range of configurations are possible, but it is not feasible to document the assembly of every possible permutation. 

### Software
We make extensive use of Micro-Manager to control openFrame instrumentation but understand that this may not always be the first choice of all users or developers. Micro-Manager uses the Lesser GPL license ([https://www.gnu.org/licenses/lgpl-3.0.en.html](https://www.gnu.org/licenses/lgpl-3.0.en.html)), and any Micro-manager device adapters we have written (for the openFrame hardware components licensed under the permissive version of the CERN Open Hardware License Version 2 in this repository) are licensed under the LGPL v3.0.
Any other software for the open-source components openFrame hardware components licensed under the permissive version of the CERN Open Hardware License Version 2 in this repository is licensed under the BSD 2-clause license ([https://opensource.org/license/bsd-2-clause/](https://opensource.org/license/bsd-2-clause/)). 

### Acknowledgements
The openFrame is a compact, modular, open-source microscope conceived by Paul French and developed with colleagues from the Photonics Group at Imperial College London, and then designed, supported, and extended in collaboration with Cairn Research. The first prototype openFrame microscope was co-designed and fabricated by Simon Johnson and Martin Kehoe in the Optics instrumentation facility of the Physics Department at Imperial College London with input. Subsequently the design and implementation were refined in a collaboration with Cairn Research Ltd by Frederik Görlitz and Sunil Kumar at Imperial supervised by Paul French, working with Callum Hollick at Cairn supervised by Jeremy Graham. Callum Hollick fabricated subsequent prototypes and designed the current version of core openFrame components, which are represented in these CAD files. 
