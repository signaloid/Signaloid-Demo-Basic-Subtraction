[<img src="https://assets.signaloid.io/add-to-signaloid-cloud-logo-dark-v6.png#gh-dark-mode-only" alt="[Add to signaloid.io]" height="30">](https://signaloid.io/repositories?connect=https://github.com/signaloid/Signaloid-Demo-Basic-Subtraction#gh-dark-mode-only)
[<img src="https://assets.signaloid.io/add-to-signaloid-cloud-logo-light-v6.png#gh-light-mode-only" alt="[Add to signaloid.io]" height="30">](https://signaloid.io/repositories?connect=https://github.com/signaloid/Signaloid-Demo-Basic-Subtraction#gh-light-mode-only)

# MICRO Benchmark: `double-subtract`

Benchmark from Tsoutsouras et al. MICRO paper.[^0]

Performs floating-point subtraction of two variables `A` and `B` with associated distributions and places the result in `C`.

## Arguments

```
double-subtract -a <samples file for A> -b <samples file for B> -m <mode>
	-a <samples file for A>: set to `input-A.txt` by default
	-b <samples file for B>: set to `input-B.txt` by default
	-m <mode>: 1 for explicit computation, 0 for implicit uncertainty tracking (0 is the default)
```

## Inputs

The samples are stored in a text file.
The first line of the file is the number of samples that follow.

[^0]: Vasileios Tsoutsouras, Orestis Kaparounakis, Bilgesu Arif Bilgin, Chatura Samarakoon, James Timothy Meech, Jan Heck, Phillip Stanley-Marbell: The Laplace Microarchitecture for Tracking Data Uncertainty and Its Implementation in a RISC-V Processor. MICRO 2021: 1254-1269
