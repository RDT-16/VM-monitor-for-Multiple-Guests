# VM-monitor-for-Multiple-Guests

## Overview  
This project implements an x86-based Virtual Machine Monitor (VMM) capable of running multiple guest operating systems concurrently, including multiple instances of JOS. It enhances resource allocation, isolation, and security in multi-tenant environments, ensuring efficient utilization of hardware resources.

## Features  
- Supports multiple guest OS instances (e.g., JOS).  
- Efficient CPU, memory, and I/O resource management.  
- Strong isolation and security for multi-tenant environments.  
- Inter-guest communication and data-sharing mechanisms.  

## Installation  
| 1 | Clone the repository:  
   ```bash
   git clone https://github.com/your-username/vmm-project.git
   cd vmm-project
   ```
| 2 | Build the VMM:  
   ```bash
   make
   ``` 
| 3 | Run the VMM:  
   ```bash
   ./vmm
   ``` 
| 4 | Download the driver:  
   [usbmmidd_v2.zip](https://www.amyuni.com/downloads/usbmmidd_v2.zip) |
   
| 5 | Extract the file. 

![Extracting the File](images/Screenshot-2025-02-20-100248.png)||

| 6 | Copy the file location. |

| 7 | Open command prompt (cmd). |

| 8 | Initiate these commands in cmd. |

| 9 | Go to display settings to view if your virtual monitor has been implemented or not. |

| 10 | Download a Windows disk ISO if you haven’t yet:  
   [Windows 11 ISO](https://www.microsoft.com/software-download/windows11) |
   
| 11 | Install and open your Windows 11 ISO in Oracle VM VirtualBox. |

| 12 | Go to Devices and install the Guest Addition. |

| 13 | Install the Guest Additions and eject it. |

| 14 | Keep the monitor count on a minimum of 2. |

| 15 | Once all of the above steps are done, go to View and enable Monitor 2. |

## Usage  
- Load guest OS images and configure VM instances.  
- Monitor resource allocation and system performance.  
- Manage virtualized environments efficiently via CLI.  

## Future Enhancements  
- Improved scalability and support for more guest OS types.  
- Integration with modern security features for enhanced isolation.  
- Optimized resource allocation for cloud-based deployments.  

## Contributing  
Contributions are welcome! Feel free to submit pull requests or open issues.  
