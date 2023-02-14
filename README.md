# Coverpoints_with_function_checks

|     **Name**     | **Description**                                                   | **Arguments**                  |**Return**  |
| ---              | ---                                                               | ---                            | ---        |
| `is_implemented` | checks whether the implementation has the following register      | register name                  | True: if the register is implemented, False: if the register is not implemented | 
| `is_legal_warl`  | checks if a given value is legal for a particular bitmask         | register: The register that is being checked, bit_position_1: The position of the first bit that is being checked, bit_position_2: The position of the second bit that is being checked |   True: if given value is legal for a particular bitmask, False: if given value is not legal for a particular bitmask | 
| `write_val`   |  the value of a register that is going to be written. It is used to check the value that is going to be written to a register after an operation or event         | register name                  | True / False | 
| `old_val`   |  the value of a register before the operation or event. It is used to check the value of a register before an operation or event, and compare it to the value after the operation or event         | register name                  | True / False | 
| `is_trap_2_M`   |  When a trap occurs, a code is written to a specific register indicating the event that caused the trap, otherwise the register is not updated by the implementation.         | register name                  | True: trap is taken in M mode, False:  trap is not taken in M mode | 
| `is_implemented_software`   | register that can be written explicitly by software         | register name                  | True: if register written by software, False:if register not written by software |
| `is_trap`   | used to indicate whether a trap is being taken in the current execution or not         | Boolean flag                  | set to true when a trap occurs and set to false when the normal execution flow is resumed |
