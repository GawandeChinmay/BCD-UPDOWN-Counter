# BCD-UPDOWN-Counter
A synchronous BCD Up/Down Counter designed in Verilog HDL that counts from 0–9 in Binary-Coded Decimal format. The counter increments or decrements based on a control signal, wraps around at boundary values, and includes clock and reset inputs. Suitable for simulation and FPGA/VLSI implementation in digital systems.



Simulation results:

Transition form 9 to 0 (upcounting mode ) when reset is at logic 0.
<img width="1554" height="805" alt="Screenshot 2026-02-23 093228" src="https://github.com/user-attachments/assets/09ca8722-bc58-44af-af5d-d59dc7020ae2" />
<img width="1553" height="788" alt="Screenshot 2026-02-23 093537" src="https://github.com/user-attachments/assets/021a55dd-2d74-4152-81e6-7493513f772f" />

Transition form 0 to 9 (upcounting mode ) when reset is at logic 0.
<img width="1547" height="792" alt="Screenshot 2026-02-23 093253" src="https://github.com/user-attachments/assets/32fe2851-f14d-43b2-8a96-b10ec2a969aa" />
<img width="1558" height="790" alt="Screenshot 2026-02-23 093301" src="https://github.com/user-attachments/assets/a7cb25ad-1ec7-44c8-bf67-c4d2be60b538" />
