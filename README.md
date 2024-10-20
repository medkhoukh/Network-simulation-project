# Network Simulation Project
Development of a virtual network simulating the connection between private networks and an Internet Service Provider (ISP).

To run the virtual machines of the network environment, run the START script . 

## Features

- **RIP Routing**: Implemented Routing Information Protocol (RIP) for dynamic routing within the network,
  allowing routers to share information about network reachability and routing paths.

- **DHCP**: Set up a Dynamic Host Configuration Protocol (DHCP) server to automatically assign IP addresses and configuration settings to devices on the network.

- **NAT**: Configured Network Address Translation (NAT) to enable multiple devices on a private network to access external networks using a single public IP address.

- **Private Networks**: Established private networks to isolate traffic among different segments of the network,
  improving security and performance by controlling data flow and access.

- **DNS Server**: Deployed a Domain Name System (DNS) server to resolve domain names into IP addresses,
  facilitating easier access to network resources and improving user experience.

- **Virtualization with Docker**: Utilized Docker for virtualization, allowing multiple instances of network services to run in isolated containers.
  This enhances resource efficiency and simplifies deployment and management of network services.
