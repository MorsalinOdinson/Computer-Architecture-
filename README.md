# Computer-Architecture-

emulsiV - Simulator - How it works - Monday, July 15, 2024

Step 1: the first step is the initializing of the processors state ![image](https://github.com/user-attachments/assets/850a19c3-dd82-4fce-876b-f23dc7cd8676)
Step 2 : after the initial setup is complete the simulator has to fetch the first intruction from the memory. ![image](https://github.com/user-attachments/assets/3fec2838-dd61-47fd-9686-67256474a219)
In the fetching cycle the PC will hold the address to the next intruction then will send it over to the memory. After the address is recieved by the memory, it is placed in the intruction register. The PC is then incremented to the next address so it can get ready for the next fetch cycle.
Step 3: the intruction that is now in the instruction register now needs to be decoded. This is done by the simulator to get the operation code which is the operation that is to be performed. ![image](https://github.com/user-attachments/assets/db857e2c-7466-476d-95ee-34aea4ca7ebd). The operands that the intructions require are shown. They could be which memory address the instruction will use or which register. Depending on the intructions that were decoded, the control unite is going to generate the right control signals to direct it to the excecution phase.
Step 4: 

