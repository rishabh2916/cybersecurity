# Operating System

## The Invisible Manager

**Operating System (OS)** is a layer between the hardware and the applications. From the application's perspective, the OS provides an interface to access the different hardware components, such as CPU, RAM, and disk storage. Examples of OS are Android, FreeBSD, Linux, macOS, and Windows.
![os working image](./assets/os-interface.svg)

- Your **hardware** (CPU, RAM, storage, connected devices): The runways, airplanes, fuel systems, radar, and other physical infrastructure.
- Your **applications** (web browser, game launcher): The various airlines and their passengers, all trying to take off, land, and request services.
- Your **operating system (Windows, Linux, macOS)**: The entire air traffic control system, directing all of this activity. It schedules resources, manages traffic, resolves conflicts, and ensures safety.

### System Privilege Layers

- **Kernel space:** The privileged, locked-down core of the OS. This is where the kernel, the part of the operating system that directly manages hardware and system resources, runs. It has unrestricted access to the CPU, memory, storage, and all hardware components.
- **User space:** Where all standard applications run. Applications in the user space are deliberately prevented from accessing hardware directly. Whenever they need to open or save a file, play a sound, or connect to Wi-Fi, they must make a system call and request that the kernel act on their behalf.

### OS Responsibility

1. Precess Management
1. Memory Management
1. File System Management
1. User Management
1. Device Management

### Operating System Security

1. **Authentication:** Verifies who you are through login passwords and biometrics
1. **Permissions:** Controls exactly what each user and app is allowed to read, write, or execute
1. **Isolation:** Keeps every process in its own protected box (kernel/user space separation)
1. **System Protection:** Safeguards critical system files and settings from unauthorized changes

![information about this computer](./assets/01-lab-preview.png)
