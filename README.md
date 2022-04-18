# Qubic a quorum-based computations protocol.

In this tutorial we'll setup a [Qomputor](https://www.computors.org/computing/qomputor "Qomputor") Node. This tutorial is a community initiative. For more information or questions join [Syzygy Discord ](https://discord.gg/2vDMR8m "Syzygy Discord").

Qubic software is running on baremetal machines without any OS installed, the software is a so called UEFI application and for security reasons we compile it ourselves with the .cpp files provided by [Come-from-Beyond](https://twitter.com/c___f___b "Twitter"). The latest releases will always be on [Syzygy Discord ](https://discord.gg/2vDMR8m "Syzygy Discord").

Because we use a UEFI application, the successful use of the software is very dependent on the system that is used. Here are some examples of motherboard/cpu combinations that have been tested and which are working successfully.

| Motherboard        | CPU         | RAM  | Connection |
| ------------------ |:-----------:| ----:| -------:   |
| MSI B450-A PRO MAX | Ryzen 3950x | 64GB | 1gbps      |

For now, the exact conditions for a successful system are not yet available. 

# Hardware Requirements
* Highend CPU
* Motherboard which accept unsecure UEFI software (disable secure boot)
* 64GB Ram
* 1GBps internet connection
* 128GB USB Stick

# Software Requirements
* [Visual Studio Code](https://visualstudio.microsoft.com/vs)
* [Rufus](https://rufus.ie)

# The steps we will take to achieve a successful efi application

1. Prepare motherboard/bios settings
2. Compiling Qubic
3. Prepare USB
4. Run

# Preparing motherboars and bios settings 

