# io.net. Project breakdown + installing node. Let's go!

**io.net** — is a decentralized network of GPUs designed to provide unlimited computing power to machine learning (ML) applications. The project's mission is to democratize access to computing power by collecting over 1 million GPUs from independent data centers, crypto miners, and projects such as Filecoin and Render. By working with underutilized GPU sources outside of the cloud, io.net aims to solve the current cloud GPU power shortage and make computing more scalable, affordable, and efficient.

### Prerequisites

Ensure you have `curl` installed on your system to download the script. 
- Run the following command to install if not installed already.<br>
     ```
     sudo apt install curl
     ```
     
### Installation

1. **Download the setup script**:

   ```bash
   curl -L https://github.com/ionet-official/io-net-official-setup-script/raw/main/ionet-setup.sh -o ionet-setup.sh

2. Run the script:
   ```bash
   chmod +x ionet-setup.sh && ./ionet-setup.sh
   
## Script Overview

The `ionet-setup.sh` script performs a series of operations:

- Sets global variables and detects the operating system and its version.
- Checks for Nvidia GPU presence and installs necessary drivers and CUDA toolkit based on the detected Linux distribution and version.
- Installs Docker and Docker Compose, along with setting up Nvidia Docker if an Nvidia GPU is detected.
- Adds the user to the Docker group.
## Supported Distributions

- Ubuntu (20.04, 22.04, 18.04)
- Debian (10, 11)

## Contributions

Contributions to this script are welcome. Please ensure that any pull requests or issues are relevant to the script's functionality and compatibility.