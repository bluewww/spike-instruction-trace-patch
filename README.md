# spike-instruction-trace-patch
Patch file for RISCV's spike to generate csv test vectors to aid the verification of Instruction trace encoder implementation.
Once patch has been applied invoke spike in the usual manner but add --ust-trace <spike_trace_file> for the cvs output file.

This repository also contains the csv files for a number of benchmarks. Most of these benchmarks are shipped with ROCKET tools.


