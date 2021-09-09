**Description**

*Home tasks are:*

• Reimplement UART driver with Interrupts<br>
• Reimplement UART driver with DMA<br>
• Develop application for ADC measurement using DMA<br>
• Increase the number of ADC channels to 3 with DMA<br>

ST HAL library are allowed for all tasks<br>

**Requirements**

CubeMX 6.3.0<br>
CubeIDE 1.7.0<br>
Discovery kit with stm32f303vct6<br>

**Build project**
- To build the program open the project in CubeIDE and run the command in menu Project->Build All (Ctrl+B)<br>

**Run the program**
- To run the program click Run button on the toolbox or run the command in menu Run->Run<br>
Discovery kit with stm32f303vct6 must be connected to the computer.

**Notes**
The program is in file main.c.<br>
In all tasks USART2 is used (9600/8/1/No parity). USB-RS232 converter is needed.<br>
In Task3 ADC1 is used (Channel 1 - input PA0).<br>
In Task4 ADC2 is used (Channels 1 to 3 - inputs PA4, PA5, PA6).<br>
TIM8 is used as External Trigger Conversion Source for ADC in Task3 and Task4.