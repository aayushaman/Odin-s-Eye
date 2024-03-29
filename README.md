# Odin-s-Eye

## About Odin-s-Eye

**Odin-s-Eyee** is a RAM dump collection tool designed for Windows, Linux, and macOS-based operating systems. It empowers forensic experts, system administrators, and security professionals to efficiently capture system memory for analysis, diagnostics, and incident response across diverse platforms.

## Key Features

- **Cross-Platform Compatibility:** Odin-s-Eye is engineered to work seamlessly on Windows, Linux, and macOS, offering a unified solution for RAM dump collection, regardless of the underlying operating system.

- **Low-Level Memory Access:** The tool provides low-level access to the system's physical and virtual memory, ensuring that it captures a comprehensive and accurate representation of the system's RAM.

- **User-Friendly Interface:** Odin-s-Eye offers an intuitive command-line interface, making it accessible to both seasoned professionals and those new to memory forensics. Users can specify the output file and start the collection process with a simple command.

- **Configurable Collection:** Users can customize the memory collection process, allowing them to select specific memory regions, filter out non-essential data, and specify the output file format.

- **Efficient Data Handling:** Odin-s-Eye is optimized for efficient memory handling, ensuring minimal system impact during the data collection process. It minimizes the risk of system instability or data corruption.

- **Comprehensive Output:** The collected RAM dump is saved in a binary format, preserving the memory structure for in-depth analysis and investigation.

## Installation

To install Odin-s-Eye, follow these steps:

1. Clone this repository.
   
   ```
      git clone https://github.com/yourusername/your-repo.git
   ```
   
2. Build the project
   ```
      cd Odin-s-Eye
      make
   ```
3. Run Odin-s-Eye
   ```
      ./Odin-s-Eye [options]
   ```
4. Usage
   ```
      ./Odin-s-Eye -o outputfile.bin
   ```
