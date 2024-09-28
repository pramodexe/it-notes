# Data Processing Study Notes

## 1. How Computers Process Data

### Central Processing Unit (CPU)
- **Control Unit**: 
  - Acts as the "brain" of the CPU
  - Directs data flow between CPU and other devices
  - Stores microcode (CPU's built-in instructions)
- **Arithmetic Logic Unit (ALU)**:
  - Performs arithmetic operations: +, -, ×, ÷, ^
  - Performs logical operations: =, ≠, >, <, ≥, ≤
- **Registers**: 
  - Small, high-speed memory areas in CPU
  - Hold data and instructions currently being processed
  - Size (e.g., 32-bit, 64-bit) affects processing capacity

### Memory
- **RAM (Random Access Memory)**:
  - Volatile: loses content when power is off
  - Stores current data and program code needed by CPU
  - More RAM generally means faster performance
- **ROM (Read-Only Memory)**:
  - Non-volatile: retains content when power is off
  - Holds essential startup instructions (bootstrap program)
- **Types of RAM**: 
  - Dynamic RAM (DRAM): Needs frequent recharging, cheaper
    - Variations: SDRAM, Rambus DRAM, DDR SDRAM (faster types)
  - Static RAM (SRAM): Holds content longer, faster but more expensive
  - Flash Memory: Retains data when powered off, used in devices like digital cameras

### Machine Cycle
1. **Instruction Cycle**: 
   - Fetch: Retrieve instruction from memory
   - Decode: Interpret the instruction
2. **Execution Cycle**: 
   - Execute: Carry out the instruction
   - Store: Save the result if necessary

### CPU Architectures
- **CISC (Complex Instruction Set Computing)**:
  - Longer instructions, shorter code
  - Emphasis on hardware
  - Multiple clock cycles per instruction
  - Harder to pipeline (execute multiple instructions simultaneously)
- **RISC (Reduced Instruction Set Computing)**:
  - Simpler instructions, longer code
  - Emphasis on software
  - One clock cycle per instruction
  - Easier to pipeline

### Processing Types
- **Serial Processing**: Execute one instruction at a time
- **Parallel Processing**: 
  - Use multiple processors simultaneously
  - Can perform trillions of operations per second (teraflops)
  - Used in supercomputers and advanced servers

## 2. Factors Affecting Processing Speed

- **Registers**: 
  - Size (word size) determines amount of data processed at once
  - Modern PCs typically have 32-bit or 64-bit registers
- **RAM**: 
  - More RAM allows more data and programs to be held in memory
  - Reduces need for "swapping" (moving data between RAM and hard disk)
  - Swapping significantly slows down performance
- **System Clock**: 
  - Sets pace for CPU operations
  - Measured in Hertz (Hz) - cycles per second
  - Example: 2 GHz clock "ticks" 2 billion times per second
  - Faster clock generally means more instructions executed per second
- **Bus**: Data path between components
  - **System Bus**: Internal 
    - Data bus: Carries actual data
    - Address bus: Carries memory addresses
  - **Expansion Bus**: For peripheral devices
  - Bus width and speed affect data transfer rates
- **Cache Memory**: 
  - High-speed memory for recently used data and instructions
  - Levels: L1 (fastest, smallest), L2, L3 (larger but slower)
  - Located on CPU or between CPU and RAM
  - More cache generally improves performance significantly

## 3. Extending Processor's Power to Other Devices

### Ports
- Connect external devices to the computer
- Common types:
  - USB (Universal Serial Bus): Versatile, widely used
  - VGA/HDMI: For displays
  - Ethernet: For network connections
  - Audio ports: For speakers and microphones

### Expansion Slots and Boards
- Allow addition of new devices and capabilities
- Install expansion boards into slots to add new ports or features
- Technologies: 
  - USB: Allows connecting multiple devices to one port
  - IEEE 1394 (FireWire): High-speed data transfer, good for video
  - SCSI: Older standard for connecting multiple devices

## Key Concepts to Remember

- Computers use binary (base-2) number system: Only understand 0 and 1
- ASCII: Standard 7-bit text encoding, 128 characters
- Unicode: Expanded character set, covers most world languages
- CPU performance often measured in MIPS (Millions of Instructions Per Second)
- Bus speed measured in Mbps (Megabits per second) or MBps (Megabytes per second)
- Cache memory significantly impacts computer speed by reducing time to access frequent data
- Pipelining: CPU technique to process multiple instructions simultaneously, improving efficiency

## Study Tips
- Understand the flow of data: Storage → RAM → Cache → CPU
- Visualize the CPU components working together: Control Unit directing, ALU computing, Registers holding immediate data
- Compare computer memory types to human memory: RAM is like short-term memory, ROM is like instincts or reflexes
- Think of the system clock as the heartbeat of the computer, setting the pace for all operations
