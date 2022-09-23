# Introducction

## Glossary

### Acronyms

- **ASIC** Application-Specific Integrated Circuit.
- **FPGA**: Field-Programmable Gate Array.
- **GPS**: Global Positioning System.
- **IDE**: Integrated Development Dnvironment.
- **OS**: Operating System.
- **POSIX**: Portable Operating System Interface.
- **RT**: Real Time.
- **UI**: User Interface.

## What are embedded systems?

A system with a **programmable computer**, but not general purpose.

### Where they are?

It is estimated that there are an average of 40 embedded systems per house.

- **Automotive**: Engine control, braking system, etc.
- **Home electronics**: Washing machine, refrigerator, microwave, toaster, etc.
- **Consumer electronics**: Mobile phones, mp3, ebooks, tv, cameras, gps, etc.
- **Industrial control**: Manufacturing control systems, sensors, etc.
- **Medical**: Dialysis machines, cardiac monitors, etc.
- **Office**: Fax, photocopier, printers, etc.

Many systems are composed of several embedded systems, i.e. mobile phones.

### Architecture

| Layer       | Components                   |
|------------:|:-----------------------------|
| Application | services, _UI_               |
| Middleware  | frameworks, protocols        |
| Platform    | Controlers, _OS_             |
| Hardware    | Microcontrolers, peripherals | 

### Characteristics

- **Unique function**: A single function performed repeatedly.
- **_Reliable_**: Minimun error probability, maintainability, disponibility, secure connections. 
- **Limited resources**: Manufacturing cost, size (physical and memory), energy consumption, eficiency. 
- **_RT_**: Reponse time limited. 
- **Reactive**: Input by sensors, output by actuators.
- **Complex algorithms**: Physical environment with which they interact interact with is complex.
- **_UI_**: Dedicated interfaces, i.e. pedals, steering wheels, buttons, etc.
- **Multi rate**: Some tasks must be performed in _RT_, others do not. 

No all embedded systems have all the characteristics.

### Clasification

Usually classified as small, medium and sophisticated.

| characteristic \ classification | Small | Medium | Sophisticated | 
|---------------------------------|-------|--------|---------------|
| Processor | 8 and 16 bits | 16, 32 and 64 bits | _FPGA_, _ASIC_ | 
| Hardware complexity | Low complexity | peripherals, interfaces, etc. | Designers |
| Software complexity | No complex operations | Medium size Software | Designers must be experts |
| Tools disponibility | Programmed in a simple environment | Debugger, compilers and / or _IDE_ | Complete environment needed |
| Examples | Calculator | Washing machine, microwave | Robots, braking and landing | 

## Topics about embedded systems

- Architecture and _OS_ of embedded systems.
- Software: _POSIX_, _RT_ and planning.
- Firmware for [Arduino](https://www.arduino.cc). 


