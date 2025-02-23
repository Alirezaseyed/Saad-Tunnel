# Saad Tunnel Script

## Overview
This script automates the installation and configuration of `obfs4proxy`, `jq`, and network tunneling with `netplan` to create a secure tunnel. It provides an interactive menu for setting up IRAN or foreign servers.

## Features
- Installs required dependencies (`jq`, `obfs4proxy`, `netplan`)
- Configures `obfs4proxy` for secure tunneling
- Supports both IRAN and foreign tunnel setups
- Provides an interactive CLI menu
- Includes a function to uninstall the tunnel setup
- BBR optimization for better network performance

## Requirements
- Ubuntu/Debian-based system
- Root privileges

## Installation
```bash
<(curl -Ls https://raw.githubusercontent.com/Alirezaseyed/Saad-Tunne/main/install.sh)
```

## Usage
Upon execution, the script will:
1. Check for required dependencies and install them if missing.
2. Configure `obfs4proxy` and generate necessary certificates.
3. Offer an interactive menu:
   - Configure Tunnel (IRAN or Foreign Server)
   - Uninstall Saad
   - Install BBR for network optimization
   - Exit

### Setting up an IRAN or Foreign Tunnel
- Select option `1` from the menu.
- Choose `IRAN` or `Kharej (Foreign)`.
- Enter the required details (IP addresses, IPv6 local address).
- The tunnel will be configured automatically.

### Uninstalling
- Select option `2` to remove all configurations and stop services.

### Installing BBR
- Select option `3` to optimize network performance using BBR.

## Notes
- Ensure the system has `netplan` installed before running the script.
- The script modifies `/etc/netplan/` configurations, so back up existing settings if necessary.

## License
This script is open-source. Feel free to modify and distribute it as needed.

## Contact
For issues or improvements, contact:
- Telegram: [@seddalii](https://t.me/seddalii)
- GitHub: [your-repo](https://github.com/your-repo)

