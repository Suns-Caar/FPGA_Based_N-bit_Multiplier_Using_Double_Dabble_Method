# FPGA_Based_N-bit_Multiplier_Using_Double_Dabble_Method
Multiplication is one of the primary operations carried out on binary integers in digital
electronics. A circuit known as an n-bit multiplier can multiply two n-bit binary integers to
yield a 2n-bit binary result. In this project, we'll create an n-bit multiplier circuit that
multiplies bits using the shift and add technique. In order to transform the binary output into
BCD format, we will also integrate a binary to BCD converter into the design. The binary
number will be converted to BCD format using the double dabble technique. The design will
be put into practise in Verilog on an FPGA

![image](https://github.com/Suns-Caar/FPGA_Based_N-bit_Multiplier_Using_Double_Dabble_Method/assets/73470491/8466840e-35f5-47f6-b74f-aad7f95b2334)

Algorithm Double Dabble
A quick and effective way to translate binary numbers into BCD representation is to use the
double dabble algorithm. The algorithm uses shifting and adding operations to convert a
binary number into its BCD equivalent. The algorithm involves the following steps:
1. Initialize the BCD result to zero.
2. Shift the binary number left by one bit.
3. If the binary number is greater than or equal to 5, add 3 to the BCD result.
4. Shift the BCD result left by one bit.
5. If the binary number is greater than or equal to 10, add 3 to the BCD result.
6. Repeat steps 2 to 5 until all the bits of the binary number have been processed.

![image](https://github.com/Suns-Caar/FPGA_Based_N-bit_Multiplier_Using_Double_Dabble_Method/assets/73470491/592d66ff-7d63-4b54-8d93-f74a8a186777)

Results:
Device Utilization Report

![image](https://github.com/Suns-Caar/FPGA_Based_N-bit_Multiplier_Using_Double_Dabble_Method/assets/73470491/fa7b2637-32b3-4f41-b71d-167798beb9fd)

Total No of LUTs used = 365
Total No of Registers used = 130

Power Estimation 

![image](https://github.com/Suns-Caar/FPGA_Based_N-bit_Multiplier_Using_Double_Dabble_Method/assets/73470491/9f3b8f6e-b1c9-4aef-a6fc-d5d73f4c0fac)

Simulation 

![image](https://github.com/Suns-Caar/FPGA_Based_N-bit_Multiplier_Using_Double_Dabble_Method/assets/73470491/29c073b1-5094-49aa-a9e0-7431300124c6)


