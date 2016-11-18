# paper-input value reset bug reproduce

This element reproduces paper-input with iron-form **reset()** function bug. Please follow instruction to reproduce this bug.

Instructions:

- Click "SET RANDOM VALUE" button to set random float to input value
- We can see two forms - one rendered when value was set (blue border), other one was rendered instantly (green border)
- Click each form "RESET" button. In blue form paper-input value was not reset
- Click "SET RANDOM VALUE" again
- Click each form "RESET" button. In blue form paper-input value was set to first random value

**Conclusion:** paper-input element "reset value" is the first value input received ?
