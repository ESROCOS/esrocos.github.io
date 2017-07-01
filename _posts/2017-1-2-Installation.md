---
layout: post
title: Installation Instructions
---

Instruction how to install the ESROCOS development environment on your PC.

## Prerequisites
You will require a working TASTE installation. Currently, we suggest you to use the [TASTE Virtual Box image](http://download.tuxfamily.org/taste/TASTE-VM-9.0-32bit.ova). Installation an dusage instructions for TASTE can be found at the [TASTE Community Homepage](http://taste.tuxfamily.org/).

## Instruction
1. Start TASTE Virtual Machine
2. Within the TASTE Linux System, start a shell
3. Download the [bootstrap file](/dl/install_esrocos)
   ```
   mkdir esrocos
   cd esrocos
   wget https://esrocos.github.io/dl/install_esrocos .
   ```
4. Execute boot strap file
   ```
   ./install_esrocos
   ```
   During the installation process you'll be asked...

   The ESROCOS installation can now be found the `esrocos` subfolder...

## First steps
Have a look at our [First Steps Page](/First-Steps) for some use case examples.

