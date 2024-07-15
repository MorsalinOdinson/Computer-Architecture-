# Computer-Architecture-

emulsiV - Simulator - How it works - Monday, July 15, 2024

Stage 1: the first step is the initializing of the processor's state![image](https://github.com/user-attachments/assets/850a19c3-dd82-4fce-876b-f23dc7cd8676)
Stage 2: after the initial setup is complete the simulator has to fetch the first instruction from the memory. ![image](https://github.com/user-attachments/assets/3fec2838-dd61-47fd-9686-67256474a219)
In the fetching cycle, the PC will hold the address to the next instruction then will send it over to the memory. After the address is received by the memory, it is placed in the instruction register. The PC is then incremented to the next address so it can get ready for the next fetch cycle.
Stage 3: the instruction that is now in the instruction register now needs to be decoded. This is done by the simulator to get the operation code which is the operation that is to be performed. ![image](https://github.com/user-attachments/assets/db857e2c-7466-476d-95ee-34aea4ca7ebd). The operands that the instructions require are shown. They could be which memory address the instruction will use or which register. Depending on the instructions that were decoded, the control unit is going to generate the right control signals to direct it to the execution phase.
Stage 4: execution
Stage 5: memory access
