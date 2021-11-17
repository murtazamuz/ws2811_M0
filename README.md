# ws2811_M0
I coudnt find any library for ws2811 for arm processors. 
So i made the library in assembly, arm for cortex processors.
Currently this header file is tested on STM32f0Discovery Board.
Might work till M4 line. The code is simple with NOP's added 1.25us Accuracy.
To make it work, 
Pass BSRR(Bit set reset register) address
Pass BS(BitSet),BR(Bit Reset) values. 
STM32 HAL has all these address defined.
