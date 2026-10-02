# Hi, I'm 4Vmus 👋

Embedded Firmware Developer

I mainly work with STM32-based embedded systems and industrial communication.

My current focus is expanding from low-level firmware development toward
embedded Linux, networking, system integration, and higher-level system architecture.

---

# 🧭 Embedded Engineering Roadmap

My portfolio is organized by capability rather than by individual projects.

Each section represents a technical area that I have worked with,
and the repositories below will gradually contain independent implementations,
examples, and project records.

---

## 01. MCU & Embedded Fundamentals

- STM32G0 / C0 / L0 / L1 / F3 / F4 / H7 Series
- Peripheral driver and low-level firmware development
- Interrupt / DMA based data processing
- Hardware interface and device integration
- Flash memory and configuration management
- Watchdog and fault recovery

### Portfolio

- [ ] STM32 Peripheral Integration Example
- [ ] STM32 Driver Architecture
- [ ] Embedded Error Handling Example
- [ ] Watchdog & Fault Recovery Example

---

## 02. RTOS & Firmware Architecture

- FreeRTOS
- Task architecture and scheduling
- Queue / Mutex / Semaphore
- Task Notification / Event handling
- Periodic task design
- Shared resource protection
- State-based firmware design
- Fault recovery architecture

### Portfolio

- [ ] FreeRTOS Task Architecture Example
- [ ] Queue / Mutex Communication Example
- [ ] Periodic Task Scheduling Example
- [ ] Embedded State Machine Example

---

## 03. Serial & Industrial Communication

- UART
- RS-232
- RS-485
- Modbus RTU
- Custom binary protocol
- JSON-based protocol
- CRC validation
- Sequence control
- Timeout / Retry handling
- Multi-device polling

### Portfolio

- [ ] STM32 UART Communication Example
- [ ] RS-485 Communication Example
- [ ] Modbus RTU Master
- [ ] Multi-Device Modbus Polling
- [ ] Custom Protocol Parser
- [ ] JSON Framing Protocol

---

## 04. CAN / CAN-FD Communication

- CAN
- CAN-FD
- Message filtering
- ID management
- Message dispatching
- Error handling
- Communication state management

### Portfolio

- [ ] STM32 CAN Example
- [ ] STM32 CAN-FD Example
- [ ] CAN Message Dispatcher
- [ ] CAN Communication Error Handling

---

## 05. Ethernet & TCP/IP

- Ethernet
- LwIP
- TCP client communication
- Socket communication
- DHCP / Static IP
- Reconnection logic
- Communication timeout handling
- Network state management

### Portfolio

- [ ] STM32 LwIP TCP Client
- [ ] Embedded TCP Reconnection Example
- [ ] DHCP / Static IP Configuration
- [ ] Network Fault Recovery Example

---

## 06. Industrial Control & State Machine

- State machine design
- Interlock logic
- Protect logic
- Emergency stop handling
- Fault detection
- Recovery logic
- Sensor monitoring
- Output control

### Portfolio

- [ ] Embedded State Machine Framework
- [ ] Protect Logic Example
- [ ] Emergency Stop Logic
- [ ] Interlock Control Example
- [ ] Fault & Recovery Architecture

---

## 07. Sensor & Data Acquisition

- ADC-based sensor input
- 4–20 mA signal processing
- Temperature measurement
- Differential pressure measurement
- Energy / Power meter integration
- Sensor scaling and conversion
- Modbus sensor polling
- Multi-channel data acquisition

### Portfolio

- [ ] 4–20 mA Sensor Conversion
- [ ] Sensor Calibration Example
- [ ] Power Meter Modbus Interface
- [ ] Multi-Device Sensor Polling
- [ ] Multi-Channel Data Acquisition Example

---

## 08. Embedded UI

- Character LCD
- Menu UI
- Button input handling
- Long press / short press events
- Page navigation
- Edit mode
- Status display
- Configuration interface

### Portfolio

- [ ] Embedded LCD Menu
- [ ] Button Event Handler
- [ ] Embedded Configuration UI

---

## 09. Bootloader & Firmware Update

- Bootloader architecture
- Firmware update process
- USB-based firmware update
- Flash programming
- Firmware validation
- Update failure handling

### Portfolio

- [ ] STM32 Bootloader Example
- [ ] Firmware Update Architecture
- [ ] Firmware Validation Example
- [ ] Update Failure Recovery Example

---

## 10. Embedded Linux

- Raspberry Pi
- Embedded Linux
- Linux process and service management
- Serial communication
- Socket programming
- Python
- systemd
- Logging

### Portfolio

- [ ] Raspberry Pi Serial Gateway
- [ ] Linux Device Communication
- [ ] Embedded Linux Service
- [ ] Linux Data Logger

---

## 11. Gateway & System Integration

- MCU ↔ Gateway communication
- Serial / CAN / Ethernet integration
- Embedded Linux gateway
- Device data aggregation
- TCP / MQTT / REST API
- Server communication
- Database integration
- End-to-end system architecture

### Target Architecture

```text
Device
  ↓
STM32 Firmware
  ↓
RS-485 / CAN / Ethernet
  ↓
Embedded Linux Gateway
  ↓
TCP / MQTT / REST API
  ↓
Server / Database
  ↓
Web Dashboard
