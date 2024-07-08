# RTL Simulation Reading Group Notes

## Papers / Patents

### Emulation HW

Custom ASIC-based emulation hardware produced by industry.

- [Yorktown simulation engine](https://ieeexplore.ieee.org/document/1585479) (DAC 1982, IBM)
- [A survey of HW accelerators used in CAD](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5005647) (IEEE Design and Test 1984, Tom Blank (Stanford))
- [Logic simulation engines in Japan](https://ieeexplore.ieee.org/abstract/document/43078) (IEEE Design and Test 1989, NEC / Fujitsu)
- [Multiprocessor for HW emulation](https://patents.google.com/patent/US5551013A/en) (Patent 1994, IBM / Cadence)
- [Emulating multi-ported memory circuits](https://patents.google.com/patent/US5940603A/en) (Patent 1997, Quickturn / Cadence)
- [Speeding Up Look-up-Table Driven Logic Simulation](https://link.springer.com/chapter/10.1007/978-0-387-35498-9_34) (Springer 1999, Fujitsu)
- [Sahara: Massively Parallel Dedicated Hardware for Cycle-Based Logic Simulations](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ecjc.20193) (Wiley 2005, Fujitsu)

### FPGA Overlays

FPGA overlay-oriented emulation hardware and techniques for word-level FPGA compilation.

- [Time multiplexed FPGA architecture for logic emulation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=518231) (CICC 1995, UToronto)
- [A CAD framework for Malibu: an FPGA with time-multiplexed coarse-grained elements](https://dl.acm.org/doi/abs/10.1145/1950413.1950441) (FPGA 2011, UBC)
- [Overgen](https://polyarch.cs.ucla.edu/papers/micro2022-overgen.pdf) (MICRO 2022)

### Academic Attempts at Emulation

Academic efforts to create emulation hardware either using an FPGA overlay or modeling a custom emulation ASIC.

- [Cyclist](https://dl.acm.org/doi/abs/10.1109/ICCAD.2017.8203892) (ICCAD 2017)
  - [flo-llvm](https://github.com/palmer-dabbelt/flo-llvm), [libflo](https://github.com/palmer-dabbelt/libflo)
  - [Chisel DREAMER emulation platform](https://wiki.eecs.berkeley.edu/dreamer/Main/20141203Notes)
- [Accelerating RTL Simulation with Hardware-Software Co-Design](https://dl.acm.org/doi/abs/10.1145/3613424.3614257) (MICRO 2023)
- [Manticore: Hardware-Accelerated RTL Simulation with Static Bulk-Synchronous Parallelism](https://dl.acm.org/doi/10.1145/3623278.3624750) (ASPLOS 2023)

### Compiler Partitioning Strategy

- [Yorktown simulation SW support](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1585481) (DAC 1982, IBM)
- [Load and Communications Balancing on Multiprocessor Logic Simulation Engines](https://web.archive.org/web/20170222020308id_/http://openscholarship.wustl.edu/cgi/viewcontent.cgi?article=1814&context=cse_research) (1987)
- [Efficient circuit partitioning algorithms for parallel logic simulation](https://dl.acm.org/doi/abs/10.1145/76263.76303) (SC 1989, UIUC)
- [Performance analysis of a parallel logic simulation machine](https://www.sciencedirect.com/science/article/pii/0743731589900294?) (1989)
- [Multiple-level partitioning: an application to the very large-scale hardware simulator](https://ieeexplore.ieee.org/abstract/document/78241) (JSSC 1991)

### FireSim ancestors

- [FPGA-Accelerated Simulation Technologies (FAST): Fast, Full-System, Cycle-Accurate Simulators](https://ieeexplore.ieee.org/abstract/document/4408260) (MICRO 2007)
- [RAMP: Research Accelerator for Multiple Processors](https://ieeexplore.ieee.org/abstract/document/4287395) (IEEE Micro 2007)
- [RAMP Blue: A Message-Passing Manycore System in FPGAs](https://ieeexplore.ieee.org/abstract/document/4380625) (FPL 2007)
- [RAMP Blue: Implementation of a Manycore 1008 Processor FPGA System](http://people.eecs.berkeley.edu/~krste/papers/Burke_RAMP_Blue_RSSI_2008.pdf) (RSSI 2008)
- [A-Ports: an efficient abstraction for cycle-accurate performance models on FPGAs](https://dl.acm.org/doi/pdf/10.1145/1344671.1344685) (FPGA 2008)
- [Quick Performance Models Quickly: Closely-Coupled Partitioned Simulation on FPGAs](https://ieeexplore.ieee.org/abstract/document/4510733) (ISPASS 2008)
- [A-Port Networks: Preserving the Timed Behavior of Synchronous Systems for Modeling on FPGAs](https://dl.acm.org/doi/abs/10.1145/1575774.1575775) (2009)
- [ProtoFlex: Towards Scalable, Full-System Multiprocessor Simulations Using FPGAs](https://dl.acm.org/doi/abs/10.1145/1534916.1534925) (2009)
- [The Future of Architectural Simulation](https://ieeexplore.ieee.org/abstract/document/5506934) (IEEE Micro 2010)
- [RAMP gold: an FPGA-based architecture simulator for multiprocessors](https://dl.acm.org/doi/abs/10.1145/1837274.1837390) (DAC 2010)
- [A case for FAME: FPGA architecture model execution](https://dl.acm.org/doi/abs/10.1145/1815961.1815999) (ISCA 2010)
- [HAsim: FPGA-based high-detail multicore simulation using time-division multiplexing](https://ieeexplore.ieee.org/abstract/document/5749747) (HPCA 2011)
- [Leveraging latency-insensitivity to ease multiple FPGA design](https://dl.acm.org/doi/abs/10.1145/2145694.2145725) (FPGA 2012)
- [A cycle-accurate, cycle-reproducible multi-FPGA system for accelerating multi-core processor simulation](https://dl.acm.org/doi/abs/10.1145/2145694.2145720) (FPGA 2012)
- [Golden Gate: Bridging The Resource-Efficiency Gap Between ASICs and FPGA Prototypes](https://ieeexplore.ieee.org/abstract/document/8942087) (ICCAD 2019)
- [FASED: FPGA-Accelerated Simulation and Evaluation of DRAM](https://dl.acm.org/doi/abs/10.1145/3289602.3293894) (FPGA 2019)

### Power, gate level Simulation

- [Using a hardware simulation engine for custom MOS structured designs](https://ieeexplore.ieee.org/abstract/document/5390298) (IBM 1984)
- CPF_palladium
- LowPowerCPF-Simulation-Guide

### Software RTL Simulation

- [VLSI Logic and Fault Simulation on General-Purpose Parallel Computers](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=215006) (TCAD 1993, IBM)
- [LiveSim: A Fast Hot Reload Simulator for HDLs](https://ieeexplore.ieee.org/abstract/document/9238634) (ISPASS 2020)
- [A Case for Accelerating Software RTL Simulation by Scott Beamer](https://ieeexplore.ieee.org/abstract/document/9099598) (IEEE Micro 2020)
- [ESSENT: Efficiently Exploiting Low Activity Factors to Accelerate RTL Simulation](https://ieeexplore.ieee.org/abstract/document/9218632) (DAC 2020)
- [Fast behavioural rtl simulation of 10b transistor soc designs with metro-mpi](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10137080) (DATE 2023)
- [RepCut: Superlinear Parallel RTL Simulation with Replication-Aided Partitioning](https://dl.acm.org/doi/abs/10.1145/3582016.3582034) (ASPLOS 23)
- [On Accelerating PyRTL Simulation with Essential Signal Simulation Techniques](https://ieeexplore.ieee.org/abstract/document/10218453) (ISEDA 23)
- [Khronos: Fusing Memory Access for Improved Hardware RTL Simulation](https://dl.acm.org/doi/abs/10.1145/3613424.3614301) (MICRO 23)
- [TaroRTL: Accelerating RTL Simulation using Coroutine-based Heterogeneous Task Graph Scheduling](https://jsm.ece.wisc.edu/docs/lin-europar2024.pdf) (Euro-Par 24)

### HW-Accelerated (Non-FPGA) RTL Simulation

- [RTLFlow: From RTL to CUDA: A GPU Acceleration Flow for RTL Simulation with Batch Stimulus](https://dl.acm.org/doi/abs/10.1145/3545008.3545091) (ICPP 22)
- [Parendi: Thousand-Way Parallel RTL Simulation](https://arxiv.org/abs/2403.04714) (Arxiv Preprint 2024)

---

## Tentative schedule

## Week 1 - uarch

- [Multiprocessor for HW emulation](https://patents.google.com/patent/US5551013A/en)

### Summary

#### Processor design

- Instructions execute step by step (no control flow, fixed set of instructions in IMEM). Each iteration through the instruction memory corresponds to one target cycle
- Two data memory (denoted as input/data stack)
    - In each step, the function bit out (FBO) is stored in the data stack
    - In each step, the input from the switch is stored in the input stack. Instruction encodes which other processor to accept the incoming switch bit from (a bit can be ignored or broadcasted to X other processors)
    - Need to perform logic computation in a BFS manner in order to use the values created from previous steps
- LUTs are configured to simulate arbitrary N-1 gates. Operands are read from the input/data stack.
- Bits can be forwarded to nearby processor (N-3 ~ N+3) instead of going through the network.
    - Way of saving one cycle: if the bit goes over the network, to use it, the processor has to store it in the input stack and use it in the following cycle
- Instruction memory is split into two parts: left and right
    - For logic emulation, left and right both encodes the operation to perform
    - For memory (SRAM?) emulation, the right instruction is essentially the data array. 16 processors are grouped and a bit from each group is used to generate the address for the memory operation

#### Emulation module, board, platform

- Module
    - 64 processors are grouped together as a module
    - All the processors within a module are connected as a crossbar
- Board
    - Collection of emulation modules
    - Module ports are connected in a pre-configured fashion
- Platform
    - Collection of boards, DRAM(?), host communication logic, and other platform control logic
- Need to synchronize across every cycle across all boards. How should this global synchronization achieved? Also can we allow certain parts to slip ahead of this global synchronization barrier (I think we can, but the  benefit might not be significant due to straggler effects)

---

- Can connect multiple processors to simulate logic where the logic depth is larger than the max steps
    - The performance degradation as the target design size increases is gradual
- Inter board communication has to happen in fixed latency / compiler is aware of the latency (to the compiler, the link doesn't really matter except that the scheduling might change a little bit)
- Need to have a core that can run testbench code near the machine (display messages, assertions, C++ models ...)
- For 4 state, just use software and inject state
    - However, there are other cases where 4 state sim make sense : external IP can inject 4 state, low power simulation...
    - Cadence added support for X-prop in their latest Palladium
    - Problem with X-prop is that you have to use 2 bits to simulate a single bit (00 -> 0, 01 -> 1, 10 -> X, 11 -> Z) but can be very area inefficient (especially X's are a rare state compared to just 0 & 1)
    - But for the problems that we are trying to deal with (functional & performance verification) 2 state simulation may be sufficient
- Expanding SRAM depth is cheap because we can use custom macros
    - So when you can increase the frequency of the design, you would want to increase the SRAM depth so that each processor can emulate more gates w/o performance loss
    - However, if the frequency is fixed, increasing the number of steps per cycle translates to lower simulation perf
    - So that seems to be the reason that the IBM people found out 128 steps
    - Need to find the optimal step for FPGA & ASIC w/ modern technology nodes.
- One implementation option: add the processor grid as a FireSim LI-BDN where the interface is fixed (e.g., your tile)
    - Can share the FireSim bridge/IO infrastructure
    - Can save FPGA resources by mapping parts of the design directly on the FPGA and only the part where you anticipate RTL changes on the emulation processors
    - For Fpga overlay (300 MHz), may have to make the network more simple to save FPGA routing resources
        - The compiler has to be aware of the network latency (network has to be designed to have static latency & maps well onto an FPGA in such a way it matches switch boxes well)
        - The compiler has to be able to pipeline instructions to hide extra network latency
    - GCD is a good place to start
    - FMR will increase (perhaps similar to when running TracerV)
        - Jerry's opinion is that we shouldn't try to compromise on performance
        - In my opinion, this is somewhat inevitable and not too bad
- Approximating how many gates we can emulate when using a FPGA overlay
    - FPGA can simulate N ASIC gates
    - Each emulation processor corresponds to M ASIC gates, and has max T steps (T gates)
        - M has to take account of the network
    - Gates that can be emulated is approximately (N / M * T)
    - Need to measure T/M by implementing a dummy module and building a bitstream with it

### Discussion/Questions

- Should the compiler always cut across register boundaries?
    - If a RTL block mapped to a single processor contains sequential logic, the processor cannot use the bit in the data stack that correpsonds to the FF as it will be overwritten. So that bit must go across the network and come back and the compiler would have to insert NOPs. -> utilization vs performance tradeoff
    - Alternatively, can double the on-chip memory so that each half can work like a master (producing bits) and slave (storing bits for the next cycle). This enables more partitioning flexibility in the compiler but decreases area efficiency of the processors
- How many processors can fit in a single FPGA & how many processors/modules/boards would we need to simulate a reasonably sized CY SoC?
- What are some problems that might show up when scaling this system up in such a way that it can support a billion gate simulation?
- (Since this word seems like some magic keyword to people) Heterogeneous integration of processor designs? Can we design certain modules/blocks to have different number of operands, bitwidth, ... to optimize for area & performance?
- How to do X-propagation? We can encode that by just using 2 bits instead of 1 bit but that will have a significant area overhead. However, the most recent palladium started supporting X-propagation as well. Maybe they only have certain processors that have X-modeling while most processors only support 2 state simulation? Static analysis to identify gates that will not be X's for certain.

## Week 2 - uarch

<!-- - [Yorktown simulation engine](https://ieeexplore.ieee.org/document/1585479) -->
- [Yorktown simulation engine](https://dl.acm.org/doi/pdf/10.5555/800263.809186)

### Discussion
- What is the GDM for? Why not just use LUTs like in the patent
- Go over SRAM emulation

- What does it mean to propagate the clock distribution logic?
    - It must be due to how their clock distribution network is designed
    - Pre multi-clock domain ages
    - Can simulate clock gating, however there is no performance benefit from logic skipping
    - You can have logic in the clock tree -> clock in is a combinational of some data & clock
    - So you can simulate a FF as transistors, gate and functiona level, as you go down the abstraction takes more cycles to simulate a single FF
- 4 state simulation support
    - Can model x optimixim & pessimism
- Very different from cyclist
- If there is slipping, it has to be fixed amount because you will need memory to perform some sort of bookkeeping
- Skipping has to happen in a coarse-grained manner & the parts that can be skipped at the same time has to be pre-determined
    - Also the amount of host cycles that can be skipped has to be predetermined & known by the compiler -> kind of reaches a multicore simulation logic
    - However, the simulation throughput is determined by the worst case processor steps
- Core functional logic
    - GDM : it is for x-prop pess & opt for tuning (for 4 state simulation)
        - x opt: X & 1 -> 0 or 1
        - x pess: X & 1 -> X
        - x symbolic: if the output can be proved, use that value (even with this, there are cases when you need x prop for registers in RR-arbiter)
        - interrupt logic
            - propagation of X when happens after a certain point in simulation to check if x prop breaks stuff
            - can be used to generate trigger conditions
- vs Quickturn
    - much more effort was put to perform 4 state sim & clock gating modeling
    - possibly because they had low confidence about their digital logic
    - z3 has 4 state -> (emulated 4 state by using multiple bits, probably x-optimistic simulation)
- How clock trees are modeled in modern palladiums

## Week 3 - uarch

- [Logic simulation engines in Japan](https://ieeexplore.ieee.org/abstract/document/43078?casa_token=nD2xnLdyzTYAAAAA:rY_2eFFqS8Imhzso9TwMOKM2qQ6E5eQ0rZVc54LK_iRS4cVwM2CNewPATFflru2O-nGR-r7kvNg)
- [Sahara: Massively parallel dedicated hardware for cycle-based logic simulations, Hanamura et. al., 2005](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ecjc.20193)

## Week 4 - compiler

- [Yorktown simulation SW support](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1585481)

## Week 5 - compiler

- [Multiple-level partitioning: an application to the very large-scale hardware simulator](https://ieeexplore.ieee.org/abstract/document/78241?casa_token=DJP4vvOHJxMAAAAA:GWONYTISKBjXjdnueyLsLCknZq9MFjiwGPbg-UCdpj6g05_DYEf6nEZebsIC7V-cXWlgTMNbILY)

## Week 6 - compiler

- ~~~[Load and Communications Balancing on Multiprocessor Logic Simulation Engines](https://web.archive.org/web/20170222020308id_/http://openscholarship.wustl.edu/cgi/viewcontent.cgi?article=1814&context=cse_research)~~~
- [Efficient circuit partitioning algorithms for parallel logic simulation](https://dl.acm.org/doi/abs/10.1145/76263.76303)

## Week 7 - misc

- [Performance analysis of parallel logic simulation machine](https://www.sciencedirect.com/science/article/pii/0743731589900294?)
- [Emulating multi-ported memory circuits](https://patents.google.com/patent/US5940603A/en)

## Week 8 - Power & gate level simulation

- CPF_palladium (cadence manual)
- LowPowerCPF-Simulation-Guide (cadence manual)

## Week 9 - FPGA overlay

- [Overgen](https://polyarch.cs.ucla.edu/papers/micro2022-overgen.pdf)

## Week 10 - FPGA based emulation

- [Time multiplexed FPGA architecture for logic emulation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=518231)
- [CAD fromwork for Malibu: an FPGA with time-multiplexed coarse-grained elements](https://dl.acm.org/doi/abs/10.1145/1950413.1950441)
