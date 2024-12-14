# Get_next_line

This project involves creating a function `get_next_line()` that reads a line from a file descriptor. The function returns the line read or NULL if there is no more data or an error occurs. 

## Mandatory:
- The function reads one line at a time from the file descriptor.
- If no data is available or an error occurs, return NULL.

## Bonus:
- Implement `get_next_line` using a single static variable.
- Manage multiple file descriptors without losing the reading state.

## Usage
Clone the repository and include the appropriate header file:

```c
#include "get_next_line.h"
