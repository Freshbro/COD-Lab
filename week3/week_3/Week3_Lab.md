# Program 1: 
### Statement: Convert a 32-bit value from Little Endian to Big Endian format using RISC-V assembly

### Name of file:
lilendian2big.s

### Observation - Single Cycle
- Used the method of casting(using and) to perform the conversion. 
 
### Register Mapping
- x10 -> 0x10000000
  
  x12 -> 0x00000012
  x13 -> 0x78000000
  x16 -> 0x00560000
  x17 -> 0x00003400
  x18 -> 0x00000012
  
  x20 -> 0x78560000
  x21 -> 0x00003412
  x22 -> 0x78563412

### Data Mapping
- **<Memory Address>:** <Value stored>
0x10000000 : 0x78563412

