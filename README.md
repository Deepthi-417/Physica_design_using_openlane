# Physical_design_using_openlane.DAY-1-Introduction to openlane
 
This repository is all about the physical design using the open source EDA tool,that is openlane.Openlane is open source environment which is used to run stimulus.It is very compatible with paid EDA tools.Before going into the topic lets learn the basic terminologies of chip.
The below diagram shows us the arduino board which is a basic board.We can easily identify the chip in the board.That is the chip focussing on from now on wards.
![Screenshot 2024-03-24 074109](https://github.com/Deepthi-417/Physica_design_using_openlane/assets/107666398/d190894d-094a-4cfa-a28b-17a6d5b7f066)

From the figure we can navigate easily the chip which is palced on the board.It is shown in the square box with leads outside as we dipicted in the picture.
![Screenshot 2024-03-24 074321](https://github.com/Deepthi-417/Physica_design_using_openlane/assets/107666398/21888077-3364-45ac-b2ba-6b5aa5409852)
Inside that box as we say simply,the structure is shown in above.The white colour line on the square box is called pins or leads which are placed for the purpose of connecting ths I/O devices outside the chip.
![Screenshot 2024-03-24 074455](https://github.com/Deepthi-417/Physica_design_using_openlane/assets/107666398/a981d92d-32c0-4f67-800d-c39639b031b7)
The area shown as a chip is called core area.Inside the chip contains transistors and some electronic devices like capacitors,resistors,inductors and power supplt lines.
Pads are the area where connection points at the chips exterior that connects the package of the chip.
Die is the core without the package outside it.Simply it is the fabricated area without pin mapping.
IPS is abbreviated as "Inches Per Square" which is a parameter to specify number of components on the chip.As number of components on the chip increases the density of components will increase.
Introduction to RISC-V
Before knowing  about Risc-v processors lets know CISC processor.
CISC-Complex Instruction Set computer:which is used to perform complex calculations.
RISC-Reduced Instruction Set Computing:It is the basic processor which performs simple tasks and computations.
ISA(Instruction Set Architecture):ISA includes the with the specific architecture,which enables the computer to understand the in instructions to perform specific task.
Among CISC and RISC processors,RISC processors are preferable because it provides us or the designer with less complexity,flexible to different tasks,And simple instruction set,and mainly it is compatible to all users to workwith.
![Screenshot 2024-03-24 074634](https://github.com/Deepthi-417/Physica_design_using_openlane/assets/107666398/a28cc39b-05c6-4db6-a1f7-8855e7907ac4)
              Fig.RISCV SOC 
The above figure shows the RISCV SOC which is used in chips.
Before getting started with the Openlane.Let us see one example.Let us assume we are working with an application example,stop watch app.While designing that app we write a set code which is understand by the human i.e, C,C++,Python etc,That is what we see on the computer screen.But behind the computer screen there is series of operations that are being for a while.Compiler converts the human understandable language to machine understandable code .Compiler converts high level code to instructions formar and then to .exe executable files and then,to 1's and 0's whcih is machine language.It is processed inside the hardware inside the computer.
