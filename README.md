# DAY 4 

training

# Hardware

## What is Computer Hardware?

Hardware refers to the physical components of a computer — things you can see and touch like CPU, motherboard, RAM, hard disk, ports, etc.

## Motherboard –

Central Hub of the System

The motherboard is the main printed circuit board that connects all parts of a computer.

## Basic Structure of a Motherboard

The motherboard is a flatboard made of printed circuits. It has many small parts on it. These parts include slots, sockets, and connectors. Each section of the motherboard has a specific role. For example:

^ The CPU socket holds the central processing unit (CPU).

^ RAM slots are used for memory modules.

^ Other connectors help attach storage devices and graphics cards.

### Function of Motherboard

The primary function of a motherboard is to provide a central platform where different components like the processor (CPU), memory modules (RAM), storage drives (HDD/SSD), and expansion cards can be integrated and work together seamlessly. It manages the data, instructions, and power flow between these connected devices.

In simpler terms, you can think of a motherboard as the command centre that allows the different parts of a computer to talk to each other and function as a complete system. It houses vital components like the CPU socket (where the processor is installed), memory slots (for RAM modules), and various ports/interfaces to connect peripherals. The motherboard also distributes power from the power supply unit (PSU) to all the connected components.

![image](https://github.com/user-attachments/assets/89bbed52-213e-4031-b363-96ab23b16ad9)

## Memory Hierarchy

|Memory      | Speed   | Size   | Use|
|------------|---------|--------|-----|
|Registers	 |Fastest  |Smallest|	CPU instruction handling|
|Cache Memory|Very Fast|Small	  |Frequently used data for CPU|
|RAM	       |Fast	   |Medium	|Temporary working memory|
|Hard Disk	 |Slow    |Large	  |Permanent storage|


![image](https://github.com/user-attachments/assets/b75ef317-aafe-4a45-9f5a-8c6fd08dd670)

# Power Supply (SMPS)

^ Converts AC ↔ DC (Switch Mode Power Supply)

^ Provides power to all components

^ Works with CMOS Battery to:

• Keep BIOS settings

• Maintain system clock even when PC is off

##  Booting Process (Power ON to OS)
- Power goes to ROM
- Bootstrap loader is activated
- OS is copied from Hard Disk → RAM
- CPU starts processing via registers and cache
✅ This startup process is called Booting

####  What Happens When You Power On Your PC (Hardware Level)

^ Power supply starts

• Sends power to all components.

^ CPU wakes up

• Looks for instructions from BIOS/UEFI.

^ BIOS/UEFI runs

• Performs POST (Power-On Self-Test) to check hardware.

^ Boot device is found

•Searches for a bootable device like SSD/HDD.

^ Bootloader is loaded

• Loads a small program into RAM.

^ Operating system starts loading 

• The OS kernel takes control and the system starts.

 ## Cache Memory
 
^ Between CPU and RAM
^ Holds frequently accessed data
^ Reduces speed mismatch
^ Saves CPU time by fetching data faster than RAM
✅ Cache memory is faster than RAM ✅ Most required data is kept in cache

### Why Do We Need Cache Memory?
^ Cache memory reduces the speed gap between the fast CPU and slower main memory (RAM).

^ It stores frequently accessed data and instructions for quicker access.

^ It minimizes the time the CPU spends waiting for data, improving efficiency.

^ It increases overall system performance by reducing memory access delays.

^ It decreases the load on main memory by handling repeated data access.

^ It speeds up the execution of loops and functions by keeping them readily available.

### RAM Types
|Type|	Full Form	Feature|
|----|--------------------|
|SRAM|	Static RAM	No refresh, fast, costly|
|DRAM| Dynamic RAM	Needs refresh, slower, widely used|

### Storage Devices

Device	Use
Hard Disk	Main permanent storage
SSD	Faster version of HDD (Solid State)
DVD Drive	Optical disk reading
Blu-ray Disc	New version of DVD (double layer)
Floppy Disk	Very old data storage
Pen Drive	Portable data transfer
🌐 9. Input/Output Ports & Interfaces
Port/Device	Purpose
HDMI Port	High-quality video/audio output
VGA Port	Old analog display (needs converter)
LAN Adapter	Connects to local network
NIC	Enables networking/internet
USB Ports	Connects pen drives, keyboard, mouse etc.
Data Cables	Usually copper wires used for transfer
🔧 10. BIOS, Firmware, and Drivers
Term	Explanation
BIOS/UEFI	Firmware stored in ROM; runs before OS starts
Drivers	Utility software that enables hardware working
🔌 11. Extra Hardware Concepts
Concept	Description
Modem	Converts analog ↔ digital signals
UPS	Backup power source (uses battery)
SMPS	Converts voltage (AC ↔ DC)
Bootstrap	Startup instructions in ROM to load OS
Registers	Tiny memory in CPU; faster than RAM, used for execution
🧠 12. Chipset & Bridges (Detailed)
Bridge	Function
Northbridge	Connects CPU to RAM, GPU, cache
Southbridge	Connects CPU to I/O devices like USB, HDD, network
🧩 These two bridges together form the motherboard chipset – managing data flow inside the system.

IMPORTANT NOTE

Study difference between RAM & ROM
Study difference between RAM & Cache memory
Study difference between RAM & Registers
Study difference between RAM & Hard disk
Study difference between RAM & ROM

