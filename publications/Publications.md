<link href="../gc.css" rel="stylesheet" type="text/css">

# Publications

## Service dedicated architecture
In order to limit the number of physical servers, virtualisation splits the hardware resources into multiple virtual machines, each dedicated to one service or application.A complete operating system should be installed on each virtual machine.Why multi-tasking and multi-purpose operating systems are used for running one single application?If the operating system crashes, all services will be unavailable or impacted. Virtual machines limit trouble spreading.The system that I propose will have to be configured statically and automatically according to the capabilities of the physical system and the profile of the application that will have to be deployed. Only the components necessary to operation of the application will be installed. The code of the system and application will be stored on a partition in read-only mode. This operating system will be transparent for application, providing a traditional system call interface in order to avoid porting the applications.

[Texte en français](SDA-ICSSEA2006-Fr.pdf)
[Full text](SDA-CIC2006.pdf)
