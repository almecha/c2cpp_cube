# c2cpp_cube
Small tool to synchronize main.c and main.cpp after code generation by stm32cubemx
## Installation
1. Download the c2cpp script 
2. Make executable:
    ```bash
    chmod +x c2cpp
    ```
4. Move into your $PATH (for example /usr/local/bin/):
   ```bash
    mv c2cpp /usr/local/bin/
    ```
## Usage
And from the terminal you can use it like this
    ```
     c2cpp <directory> [--c-file <C_FILENAME>] [--cpp-file <CPP_FILENAME>]
    ``` .  
  For example: 
    ```
    c2cpp Tests/Core/Src
    ``` .
And it will copy all the changes outside USER blocks from ```main.c``` to ```main.cpp```
