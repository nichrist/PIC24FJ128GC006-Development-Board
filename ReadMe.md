Code in C for set up the PIC as a WINUSB device and display to a LCD2X16 display temperature measurements from TMP175 sensor.

There is some introductory code also written in XC16:

- This example firmware setup  PIC 24FJ128GC006 as a WinUsb Device, execute a state machine in order the PIC to communicate via the USB port with a PC using appropriate software (GUI in Visual C++) and read via I2C port the TMP175 temperature sensor.
- Analogue to Digital conversion using PIC16F876A internal available AD converter and transmitting the data readings to the PC via the RS232 port.

Also you can find the source code of a simple Windows application written in Visual C++. This application receives and sends data from and to RS232 buffer, evaluates the voltage that the ADC reads and displays it.

Thank you

