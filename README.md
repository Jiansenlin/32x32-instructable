# 32x32-instructable

This is a simple skeleton project to get the STM32 Cube MX projects to work with a standard Eclipse config.

# The STM Cube MX project
is located in the subfolder 'hw/' (for version 1.4)

# and the plasma effect

... a patch to apply to the generated 'main.c' to get the awesome plasma effect on a 32x32 RGB LED display!

# Instructions

Open the project in the 'hw/' subfolder, and do a 'Generate code'. Make sure to only generate needed libs and stuff. Copy everything down to the main folder, and import the Eclipse project into some CDT installation.

Maybe copy the linker script to the appropiate location.

Patch the main.c with the given patch to get the Plasma stuff going.




