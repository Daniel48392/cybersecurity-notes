## What I learned:
  - Unified Extensible Firmware Interface (UEFI) - firmware that initialises hardware often used interchangeably with BIOS
  - POST (Power on Self Test) - loaded by the UEFI to check if components are present, configured and functioning
  - Client server model - Browser requests webpage and system serves it
      - Request and response - browser may request a webpage from a server which sends the webpage back to the client
      - Protocol - standards and commands used to ensure the server understand the request
      - Port - must connect to the port on the server with provides the relevant service
      - DNS - used to get the IP address of the server from the domain name
  - Hardware Virtualisation - Splitting up a computers resources into smaller independent systems to optimise system resources
  - Hypervisor - software that manages resources for each virtual system
      - Type 1 - runs on the hardware, fast, efficient and ideal for servers
      - Type 2 - runs within an existing operating system, ideal for small set ups (example running multiple OS's on a laptop)
  - Containers - runs a single application with all dependencies to support it and runs on the kernal of the existing system
  - Container images - template used to make containers
  - Cloud Service Models:
      - Infrastructure as a Service (IaaS) - you rent computer resources, you are responsible for software and OS and the provider is responsible for hardware
      - Platform as a Service (PaaS) - cloud provider is responsible for hardware and the operating system, you focus on building and deploying your application
      - Software as a Service (SaaS) - you use a complete application over the internet where the provider manages everything
  
