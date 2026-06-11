# Interview Talking Points

## 30-second version

I am building an AI-native embedded development loop. It connects agent orchestration, embedded software simulation, real hardware debugging, hardware design automation, and protocol testing.

The goal is to move AI agents from simple code generation into real embedded engineering workflows: build, simulate, flash, debug, test, and iterate.

## 1-minute version

My core direction is AI + Embedded. I have industrial embedded experience in stepper drives, multi-axis control, Modbus, EtherCAT, bootloader, and field debugging.

On top of that, I am building a set of open-source tools to explore how AI agents can participate in embedded development. [SOAA](https://github.com/11cookies11/Stack-Orchestrated-Agent-Architecture) provides the stack-based orchestration architecture. [EmbeddedLoop](https://github.com/11cookies11/EmbeddedLoopDemo) proves that agents can complete embedded software development loops in Renode simulation. [NexDAP](https://github.com/11cookies11/NexDAP) pushes the loop toward real hardware through a custom CMSIS-DAP probe. [KiCad Agent Suite](https://github.com/11cookies11/kicad-agent-suite) explores agent-assisted hardware design. [ProtoFlow](https://github.com/11cookies11/ProtoFlow) provides executable protocol workflows for communication testing.

## Key Differentiation

Many AI coding projects stop at code generation.

This project tries to close the real engineering loop:

```text
requirement -> task planning -> code -> build -> simulation -> hardware -> protocol test -> debug -> iterate
```
