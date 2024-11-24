# 4x4 SRAM Array with 2-to-4 Decoder

## Project Description

This project involves the design and implementation of a **4x4 SRAM array** with a **2-to-4 decoder** for accessing a nibble (4 bits) of data. The design is based on **CMOS technology** and was created using **Cadence Virtuoso**. The primary focus was to optimize the layout for reduced area, minimized delay, and low power consumption.

### Key Features
- **4x4 SRAM Array:** A memory array with 4 rows and 4 columns, storing a 4-bit value in each cell.
- **2-to-4 Decoder:** A decoder responsible for converting a 2-bit address into a 4-row access for reading or writing data.
- **Low Power Consumption:** The design focuses on minimizing dynamic and static power consumption, making it suitable for low-power applications.
- **Area Optimization:** Layout techniques were employed to reduce the chip area while maintaining performance and reliability.

## Design Overview

- **SRAM Array:** The SRAM array is constructed with 16 cells arranged in a 4x4 matrix. Each cell stores a nibble (4 bits) of data.
- **Decoder:** The 2-to-4 decoder takes a 2-bit input address to select one of the 4 rows for read/write access.
- **Access Mechanism:** The SRAM array supports both read and write operations by controlling the wordline and bitlines using the decoder.
  
### Technology Used
- **CMOS Technology**
- **Cadence Virtuoso** for layout and simulation
- **Verilog** for functional modeling and testing

## Features & Optimizations
- **Low-Power Design:** The layout and design of the SRAM cell and decoder were optimized for low static and dynamic power consumption.
- **Area Reduction:** By utilizing efficient layout techniques, the area of the SRAM array was minimized without compromising performance.
- **Performance:** The design was optimized to ensure minimal access delay while maintaining high reliability.


