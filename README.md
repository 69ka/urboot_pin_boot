# Project Description

In this project, we utilize [urboot](https://github.com/stefanrueger/urboot/tree/main) as our bootloader. However, unlike the original implementation, access to the bootloader does not occur after a few seconds but is triggered when the PE7 pin is set to low (0).

## Key Features

- **Modified Boot Process**: The bootloader is entered only when the PE7 pin is low, allowing for better control over the boot process and preventing accidental entry into the bootloader.
- **Compatibility**: The project maintains compatibility with the original urboot, providing all its functionalities and capabilities.
- **Easy Configuration**: Simple integration and configuration to meet your specific requirements.

## Usage
To enter the bootloader, set the PE7 pin to low (0). After that, the bootloader will be activated.

Feel free to adapt this description as needed or add additional details!