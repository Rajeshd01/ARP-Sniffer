```
    ___    ____  ____            
   /   |  / __ \/ __ \                    
  / /| | / /_/ / /_/ /                    
 / ___ |/ _, _/ ____/                     
/_/__|_/_/ |_/_/_________________________ 
  / ___// | / /  _/ ____/ ____/ ____/ __ \ 
  \__ \/  |/ // // /_  / /_  / __/ / /_/ /
 ___/ / /|  // // __/ / __/ / /___/ _, _/ 
/____/_/_|_/___/_/ __/_/   /_____/_/ |_|  

```

### ARP Spoof Detector v0.1 (linux)
### BY TEAM  
### ~RAJESH D
### ~SIVAPRAKASH
### ~KRISHNA

This tool will sniff for ARP packets in the interface and can possibly detect if there is an ongoing ARP spoofing attack. This tool is still in a beta stage. 

```
Available arguments: 
----------------------------------------------------------
-h or --help:			Print this help text.
-l or --lookup:			Print the available interfaces.
-i or --interface:		Provide the interface to sniff on.
-v or --version:		Print the version information.
----------------------------------------------------------

Usage: ./arpsniffer -i <interface> [You can look for the available interfaces using -l/--lookup]
```

### How to compile?

1. You should have `libpcap` installed on your linux system. If you don't have, you can do it with the following command

```
$ sudo apt-get install libpcap-dev
```

2. You can compile with the following command

```
$ gcc arpsniffer.c -o arpsniffer -lpcap
```

