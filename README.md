### While waiting for the motor control/JF firmware from [Trevi Vibratori SRL](https://trevivibratori.com/it/), I'm starting to upload some simple examples for the Nucleo-f411re board. But... ⬇️

## See **[here](https://tit8.github.io/Trevi.pdf)** for more insights. 

We've done it without a microcontroller because the power controller needs a switching frequency above tens of KHz. This is for 4-8 electromagnets, so the interrupt latency and the GPIO response of an MCU would kill the application and buying a costlier MCU would not make the application better. We started with physical logic gates on PCB (from Onsemi, CMOS), and then an FPGA would greatly play with the parallel version. It fulfils our needs ✔️.

<img style="width:50%;margin:auto;display:block" src="https://github.com/user-attachments/assets/627456ed-2faf-4a8b-a455-160ed0c62f4b" >

