# BuildCored-Orcas-Day25
FirmwarePatcher — BUILDCORED ORCAS Day 25

What it does. This script scans a file of ones and zeros to find specific patterns like text strings or known computer instructions, and then uses an AI to explain what those sections mean in plain english. 

Hardware concept. The concept is Firmware Analysis, which is the process of reverse engineering the software that lives directly on hardware like  microwave, a car sensor, or a router. Researchers do this to find hidden passwords, security holes, or to understand how a device works when they don't have the original source code.

Screen recording. https://drive.google.com/file/d/1TXNd7d_tClaQWeXpQfrlxUnhiVHlKyN1/view?usp=sharing

What I would do differently. I would use a tool like Binwalk to automatically calculate to find hidden files or compressed data anywhere in the binary. You would also use a Disassembler (like Ghidra) to turn those hex bytes back into readable assembly code to see exactly what logic the processor is executing.

Run it. python day25_starter.py
