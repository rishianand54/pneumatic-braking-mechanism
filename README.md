# Pneumatic Braking Mechanism

## Abstract

Pneumatic Braking Mechanism is an implementation of regenerative braking system for automobiles. It uses pneumatic compression to store the kinetic energy of the vehicle. The compressed air is used to produce electricity through a turbine, and then used for supercharging the engine of the automobile.

The complete mechanism can be divided into two parts:

- Braking
- Regeneration

Regeneration mechanism can be further subdivided into:

- Expansion
- Supercharging

The rotational motion of wheels of the vehicle is used to drive reciprocating compressors. Compressors are engaged with the help of a clutch and crankshaft unit when brakes are applied. Compression process converts the kinetic energy of the vehicle in the form of compressed air. In the process, vehicle loses its energy and comes to a standstill.

The compressed air goes to a turbine and generator unit where expansion takes place and electricity is produced. The outlet air from turbine at lower pressure is used for supercharging.

## File Manifest

- main.tex
- images/clutch-and-crankshaft-unit-schematic.png
- images/compression-graph.png
- images/compression-process.png
- images/compressor-schematic.png
- images/flow-of-operation.png
- images/turbine-and-generator-unit-schematic.png
- images/work-vs-pressure.png
- images/xmls/clutch-and-crankshaft-unit-schematic.xml
- images/xmls/compression-graph.xml
- images/xmls/compression-process.xml
- images/xmls/compressor-schematic.xml
- images/xmls/flow-of-operation.xml
- images/xmls/turbine-and-generator-unit-schematic.xml
- README
- COPYING

## Compiling

With a working TeX installation, run the following commands:

	cd /path/to/the/working/directory
	pdflatex main.tex
	makeindex main.nlo -s nomencl.ist -o main.nls
	pdflatex main.tex

Ensure that all the required packages are installed.

## Copying

Pneumatic Braking Mechanism is an implementation of regenerative braking mechanism for automobiles. Copyright © 2016 Shailendra Pratap Verma, Siddharth Singh, Shwetang Dubey and Rishi Anand.

This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

## Citations

APA — Anand, R., Dubey, S., Singh, S., & Verma, S. P. (2018, November 2). Pneumatic Braking Mechanism. https://doi.org/10.31224/osf.io/5dtz2

MLA — Anand, Rishi, et al. “Pneumatic Braking Mechanism.” engrXiv, 2 Nov. 2018. Web.

Chicago — Anand, Rishi, Shwetang Dubey, Siddharth Singh, and Shailendra P. Verma. 2018. “Pneumatic Braking Mechanism.” engrXiv. November 2. doi:10.31224/osf.io/5dtz2.

## External Links

[engrXiv Preprint](https://doi.org/10.31224/osf.io/5dtz2)

[Github Repository](https://github.com/rishianand54/pneumatic-braking-mechanism)

[Contact](https://rishianand.me/about/)
