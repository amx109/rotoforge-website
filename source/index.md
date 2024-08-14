# Introduction to the project

## What is Rotoforge?
Rotoforge is a [free and open source](https://en.wikipedia.org/wiki/Free_and_open-source_software) [hardware](https://en.wikipedia.org/wiki/Open-source_hardware)/software 3d printer for printing metal, plastic and ceramic heterogenously on the home desktop safely and affordably with performance similar to FDM. It takes advantage of a technique known as ["additive friction stir deposition" or AFSD](https://en.wikipedia.org/wiki/Friction_stir_processing).

## Where we are right now
Rotoforge has recently developed into using "Semisolid Metal Direct Write" a type of 3D metal printing where a material in wire form is fed into a hotend to be heated to the temperature range between solidus and liquidus. (basically between fully solid and fully liquid) where the material behaves thixotropically (shear thinning like peanut butter). This is essentially identical to conventional FDM. but with metals, and ceramics thus requiring a hot end that operates at much higher(about 2 orders of magnitude higher) power densities (typically 1-20 watts/square millimeter) and made of materials which will continuously withstand hot sliding abrasive wear with semisolid metals an ceramics.

Few materials meet these requirements. We have thus far opted to use Si3N4-MoSi2 ceramic matrix composite heating elements found in ceramic glowplugs for this purpose. We have used EDM to drill a hole through these glowplugs, mounted them in an ender 3 heat sink and paired them with a belt extruder to feed them fine (24 AWG, 0.5mm OD) wire. 

## Where we want to be
The target total system cost to the end user is <1000 USD with a hotend lifetime in metal printing up to materials including, zinc alloys, aluminum, brass, bronze, copper, monels, and mild steels, ideally not less than 1000 hours. Typical materials costs is bulk metal wire, somewhere between 1 and 100 USD / pound.

## Licensing information (operating principles)
The project is currently licensed under the terms of the AGPL-3.0 and the CERN open hard ware license.

## Why do this? 
1. Because manufacturing freedom for the individual *is* individual creative freedom
2. Plastic trinkets only get you so far
3. A truly self replicating machine and its proported benefits must be able to produce itself *entirely* from raw materials and energy, wherever it might happen to be. Probably, in places that do not include convenient metal foundry and electronics fabrication infrastructure. 
4. Insert your reason here. ;)