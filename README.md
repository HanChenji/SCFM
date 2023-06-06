# Reliable Simulation Points Selected by SCFM

This is the repository for the cross-microarchitecture reliable simulation points and their weights for SPEC CPU 2006 benchmark suite, selected by the SCFM.

## Contents

For every test in SPEC CPU 2006, we provide with three files in the directory ```result```

- __N__: the interval size with the unit of million
- __simpoints__: the simulation points
- __weights__: the weights

## Benchmark and Compilation Options

We use the SPEC CPU 2006 as the benchmark and compile with the following options:
```-mabi=lp64 --static -march=loongarch64 -Ofast -mlsx```

## Environment

1. we use the __gcc8.3__ for __LoongArch__ as the compiler.
2. we run the SPEC CPU 2006 on the __linux__ with kernel version __4.19__.