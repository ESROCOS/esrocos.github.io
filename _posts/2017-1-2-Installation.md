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
   chmod 770 install_esrocos
   ./install_esrocos
   ```
   During the installation process you'll be asked a few questions. Choose the following options:
   * When asked for the access protocoll for git repositories, choos `http`.
     ![Git access protocol selection]({{ site.url }}/images/installation-git_source.png)
   * When asked to select an ESROCOS version to install, choose `monolithic`.
     ![ESROCOS Version selection]({{ site.url }}/images/installation-version_selection.png)
5. Initialize Workspace
   The ESROCOS installation can now be found the `/home/assert/esrocos` folder of your TASTE Virtual Box image. To setup your ESROCOS workspace, you need to source the `env.sh` file, which is located within your ESROCOS workspace folder.
   ```
   source /home/assert/esrocos/env.sh
   ```
   You might want to automatically intialize the ESROCOS workspace, evrytime you start a terminal in yout TASTE Virtual Box. This can be achived by instructing the shell to automatically source the `env.sh` file.
   ```
   echo "source /home/assert/esrocos/env.sh" >> ~/.bashrc
   ```

<p style="text-align: center;">
<b>Congratulations, now your ESROCOS installation is ready to be used!</b>
</p>


## First steps
Have a look at our [First Steps Page](/First-Steps) for some use case examples.

