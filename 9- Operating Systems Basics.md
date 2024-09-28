# Operating System Basics Study Notes

## 1. Introduction to Operating Systems

- Definition: The most important program that runs on a computer.
- Purpose: Interface between computer and user.
- Responsibility: Management and coordination of activities and sharing of computer resources.

## 2. Types of Operating Systems

1. **Real-time OS**
   - Aims at executing real-time applications
   - Responds to input instantly
   - Very fast, small OS

2. **Multi-user vs. Single-user OS**
   - Multi-user: Allows multiple users to access concurrently
   - Single-user: Usable by only one user at a time

3. **Multi-tasking vs. Single-tasking OS**
   - Multi-tasking: Allows execution of multiple tasks simultaneously
   - Single-tasking: Allows only one program to run at a time

4. **Distributed OS**
   - Manages a group of independent computers
   - Makes them appear as a single computer

5. **Embedded OS**
   - Designed for embedded computer systems (e.g., PDAs)
   - Operates with limited resources

## 3. Major Functions of Operating Systems

1. **Resource Management**
   - Allocates computer resources (CPU time, memory, storage, I/O devices)

2. **Data Management**
   - Governs input/output of data
   - Manages storage and retrieval of information

3. **Job Management**
   - Prepares, schedules, controls, and monitors jobs
   - A job is a collection of related programs and their data

4. **Standard Means of Communication**
   - Establishes communication between users and computer systems
   - Provides user interface and standard command set

## 4. Multitasking

- Definition: Capability of running multiple processes simultaneously
- Types:
  1. **Cooperative Multitasking**
     - Requires cooperation between OS and applications
     - Programs check if others need CPU time
  2. **Preemptive Multitasking**
     - OS maintains a priority list of running programs
     - Can modify priority status

- **Single user/Multitasking OS**
  - User performs many tasks simultaneously
  - Common in desktop/laptop computers
  - Examples: Microsoft Windows, Apple macOS, Google Android

- **Multi-user/Multitasking OS**
  - Many users connect to one computer simultaneously
  - Each user has a unique session
  - Examples: UNIX, Linux, VMS, MVS

## 5. User Interface

- Definition: Program that controls display for the user and allows interaction with the system
- Purpose: Allows user to communicate with the operating system
- Functions:
  - Input: Allows users to manipulate the system
  - Output: Allows system to indicate effects of users' manipulation

### Types of User Interface

1. **Command Line Interface (CLI)**
   - Interaction through typed commands
   - Accepts input via keyboard only
   - Not suitable for beginners

2. **Graphical User Interface (GUI)**
   - Interaction through images rather than text commands
   - Accepts input via keyboard and pointing devices
   - Easy to learn

### Elements of GUI
- Pointer
- Icons
- Desktop
- Windows
- Menus

### Comparison of CLI and GUI

| Aspect | CLI | GUI |
|--------|-----|-----|
| Ease of Use | Difficult for new users | Easier to learn |
| Control | More control over file system and OS | Less control, especially for advanced tasks |
| Multitasking | Limited visual multitasking | Easy to view and control multiple things |
| Speed | Faster for experienced users | Slower due to mouse usage |

## 6. Utility Software

- Definition: Programs that perform tasks not typically handled by the operating system
- Purpose: Enhance operating system functionality
- Categories:
  - File defragmentation
  - Data compression
  - Backup
  - Antivirus
  - Screen savers

## Study Tips
1. Understand the different types of operating systems and their use cases.
2. Focus on the major functions of an OS and how they contribute to overall system management.
3. Compare and contrast different types of multitasking and their advantages.
4. Practice using both CLI and GUI to understand their strengths and weaknesses.
5. Familiarize yourself with common utility software and their purposes.
6. Consider how different OS types might be suitable for various computing environments (e.g., personal use, business, embedded systems).
