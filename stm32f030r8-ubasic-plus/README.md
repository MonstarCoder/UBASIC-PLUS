To build the uBasic-Plus for this evaluation board the following steps are required:

- create new project using, say ac6, and copy Inc and Src directories from the repository
- download the UART source and header from the Drivers/Src and Drivers/Inc folder and put them in the respective driver folder that your IDE has created for you. This is important since the files there provide extended UART Interrupt routines with circular buffer for Read and an equivalent of Serial.available function from Arduino.

The version posted here was built with ac6 and sw4stm32/cubemx environments.
