

# Release Notes for
# <mark>STM32_ExtMem_Loader</mark>
Copyright &copy; 2023 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com)

# Purpose

**The source code delivered is a middleware that helps user building its own loader for external SFDP NOR memories.</mark>**

The STM32Cube firmware solution offers a straightforward API with a modular architecture, making it simple to fine tune custom applications and scalable to fit most requirements.

![STM32_ExtMem_Loader_Architecture overview](_htmresc/ExtMemLoader_archi.bmp)


Here is the list of references to user documents:

- [WIKI Page](https://wiki.st.com/stm32mcu/wiki/
Getting_started_with_External_memory_Manager_and_External_memory_loader): Getting started with 
External memory Manager


# Update History
<label for="collapse-section4" aria-hidden="true">__V1.1.2 / 30-April-2026__</label>
<div>

## Main Changes

- docs: Added SW_Security_Level.md to the package.

## Contents

## Known limitations

 - List of the tested memories
   - SFDP : MACRONIX MX66UW1G45G
   - SFDP : MACRONIX MX25UW25645G

- List of the tested and supported bootloader interfaces in STM32Cubeprogrammer:
  - USART
  - USB

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1.
- Keil MDK-ARM toolchain V5.38 using ARM Compiler 6.
- STM32CubeIDE toolchain v1.15.0  using GCC compiler 12.

## Supported Devices and boards

- Not applicable

## Backward Compatibility

- Not applicable

## Dependencies

- Not applicable

</div>

<label for="collapse-section3" aria-hidden="true">__V1.1.1 / 10-October-2025__</label>
<div>

## Main Changes

- docs: Updated the SLA0044 license information.
- fix: Ensured the compiler retains MDK-ARM APIs post-build.

## Contents

## Known limitations

 - List of the tested memories
   - SFDP : MACRONIX MX66UW1G45G
   - SFDP : MACRONIX MX25UW25645G

- List of the tested and supported bootloader interfaces in STM32Cubeprogrammer:
  - USART
  - USB

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1.
- Keil MDK-ARM toolchain V5.38 using ARM Compiler 6.
- STM32CubeIDE toolchain v1.15.0  using GCC compiler 12.

## Supported Devices and boards

- Not applicable

## Backward Compatibility

- Not applicable

## Dependencies

- Not applicable

</div>

<label for="collapse-section2" aria-hidden="true">__V1.1.0 / 24-April-2024__</label>
<div>

## Main Changes

- Update to support memories programming with openbootloader using bootloader interfeces. 

## Contents

## Known limitations

 - List of the tested memories
   - SFDP : MACRONIX MX66UW1G45G
   - SFDP : MACRONIX MX25UW25645G

- List of the tested and supported bootloader interfaces in STM32Cubeprogrammer:
  - USART
  - USB

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1.
- Keil MDK-ARM toolchain V5.38 using ARM Compiler 6.
- STM32CubeIDE toolchain v1.15.0  using GCC compiler 12.

## Supported Devices and boards

- Not applicable

## Backward Compatibility

- Not applicable

## Dependencies

- Not applicable

</div>

<label for="collapse-section1" aria-hidden="true">__V1.0.0 / 28-February-2024__</label>
<div>

## Main Changes

First official version for STM32H7Rs/Sx devices.

## Contents

## Known limitations

 - List of the tested memories
   - SFDP : MACRONIX MX66UW1G45G
   - SFDP : MACRONIX MX25UW25645G

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1.
- Keil MDK-ARM toolchain V5.38 using ARM Compiler 6.
- STM32CubeIDE toolchain v1.15.0  using GCC compiler 12.

## Supported Devices and boards

- Not applicable

## Backward Compatibility

- Not applicable

## Dependencies

- Not applicable

</div>


<abbr title="Based on template cx566953 version 2.1">Info</abbr>