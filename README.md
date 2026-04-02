This project implements a multi-protocol communication controller on FPGA using Verilog HDL. It integrates three widely used communication protocols—UART, SPI, and I²C—into a single configurable system, allowing dynamic selection of the active protocol.

The design is based on a 100 MHz clock and uses finite state machines (FSMs) to ensure accurate timing, synchronization, and reliable data transfer. The UART module supports configurable baud rates (8N1 format), the SPI module operates in master mode with configurable CPOL/CPHA, and the I²C module supports both read and write operations with ACK detection.

A 7-segment display interface is included to visualize received data in hexadecimal format along with the selected protocol indicator.

🔧 Key Features
Unified controller for UART, SPI, and I²C
Configurable timing (baud rate, clock division)
FSM-based modular design
Real-time protocol switching
On-board data visualization
🎯 Applications
Embedded systems communication
FPGA-based digital design learning
Sensor and peripheral interfacing
