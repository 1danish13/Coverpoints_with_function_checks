# Coverpoints_with_function_checks

|     **Name**     | **Description**                                                   | **Arguments**                  |**Return**  |
| ---              | ---                                                               | ---                            | ---        |
| `is_implemented` | checks whether the implementation has the following register      | register name                  | True: if the register is implemented, False: if the register is not implemented | 
| `is_legal_warl`  | checks if a given value is legal for a particular bitmask         | register: The register that is being checked, bit_position_1: The position of the first bit that is being checked, bit_position_2: The position of the second bit that is being checked |   True: if given value is legal for a particular bitmask, False: if given value is not legal for a particular bitmask | 
| `write_val`   |  the value of a register that is going to be written. It is used to check the value that is going to be written to a register after an operation or event         | register name                  | True / False | 


