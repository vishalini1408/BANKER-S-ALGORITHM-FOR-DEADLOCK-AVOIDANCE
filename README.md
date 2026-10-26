EXPERIMENT 7: BANKER'S ALGORITHM FOR DEADLOCK AVOIDANCE

Aim
To implement and study Banker's Algorithm for the Deadlock Avoidance Problem.

Description
This C program implements Part C (Banker's Algorithm) from the Operating Systems lab manual. It reads the Allocation and Maximum matrices, calculates Need = Maximum - Allocation, reads the Available resources, and searches for a safe execution sequence.

It displays the safe sequence when all sessions can finish; otherwise, it displays "Unsafe State".

Files
- experiment7_bankers_algorithm.c : C source code for Banker's Algorithm.
- experiment7_output.png : Output screenshot from the uploaded lab manual (Experiment 7, Part C).

Compile
gcc experiment7_bankers_algorithm.c -o experiment7

Run
./experiment7

Input format
1. Enter the number of sessions and resource types.
2. Enter the Allocation matrix, row by row.
3. Enter the Maximum matrix, row by row.
4. Enter the Available vector.

Note
The attached output image is the screenshot from the manual. The prompts in the screenshot may differ slightly from the source code wording.
