# Project Roles

## Overall Role

**Project initiator / architecture designer / core developer**

Responsibilities:

1. Define the overall AI Agent + Embedded development loop.
2. Design system architecture and project boundaries.
3. Implement core modules and workflow prototypes.
4. Integrate simulation, real hardware, hardware design, and protocol testing.
5. Write documentation and maintain open-source repositories.

## Project-specific Roles

### SOAA

Repository: [11cookies11/Stack-Orchestrated-Agent-Architecture](https://github.com/11cookies11/Stack-Orchestrated-Agent-Architecture)

Role: Agent orchestration architecture designer / core developer

Responsibilities:

- Designed stack-based task orchestration.
- Defined deterministic program step + AI decision point collaboration model.
- Designed JSON file protocol for task handoff.
- Implemented task nesting, context persistence, and recoverable workflow.

### EmbeddedLoop

Repository: [11cookies11/EmbeddedLoopDemo](https://github.com/11cookies11/EmbeddedLoopDemo)

Role: Embedded simulation workflow designer / AI-agent validation lead

Responsibilities:

- Designed the AI Agent + Renode embedded software verification workflow.
- Built multi-MCU, bare-metal, FreeRTOS, Zephyr, and multi-node examples.
- Created build, simulation, log inspection, and validation workflows.

### NexDAP

Repository: [11cookies11/NexDAP](https://github.com/11cookies11/NexDAP)

Role: Hardware debug loop designer / embedded probe developer

Responsibilities:

- Designed RP2040 + ESP32-C3 CMSIS-DAP architecture.
- Planned SWD access, flashing, status reading, and remote control workflow.
- Explored how agents can control real embedded targets.

### KiCad Agent Suite

Repository: [11cookies11/kicad-agent-suite](https://github.com/11cookies11/kicad-agent-suite)

Role: Hardware automation toolchain designer / core developer

Responsibilities:

- Defined `circuit-model.json` as hardware intermediate representation.
- Split hardware design into agent-executable tasks.
- Organized requirement modeling, component selection, power tree, pinmux, schematic modules, PCB constraints, and bring-up docs.

### ProtoFlow

Repository: [11cookies11/ProtoFlow](https://github.com/11cookies11/ProtoFlow)

Role: Protocol automation framework designer / DSL runtime developer

Responsibilities:

- Designed YAML DSL for embedded communication workflows.
- Implemented state-machine execution model.
- Abstracted UART, TCP, Modbus RTU, XMODEM, timeout, retry, condition jump, and CRC validation.

### RenodeWorkbench

Repository: [11cookies11/RenodeWorkbench](https://github.com/11cookies11/RenodeWorkbench)

Role: VS Code extension developer / simulation tooling developer

Responsibilities:

- Built Renode session management workflow.
- Integrated firmware build, artifact sync, GDB attach, UART log test, and diagnostics.

### ShellLink

Repository: [11cookies11/ShellLink](https://github.com/11cookies11/ShellLink)

Role: ESP32 device-side runtime developer

Responsibilities:

- Built ESP32-C3 remote shell and DSL runtime.
- Implemented Telnet shell, YAML config, file operations, DSL execution, Modbus TCP slave, and UART protocol test harness.

### Where

Repository: [11cookies11/Where](https://github.com/11cookies11/Where)

Role: Agent visualization tooling developer

Responsibilities:

- Built VS Code task visualization plugin.
- Parsed Markdown task plans into visual progress views.
- Supported task status mapping, auto refresh, history, and editing.

### StencilForge

Repository: [11cookies11/StencilForge](https://github.com/11cookies11/StencilForge)

Role: Desktop tool developer / PCB manufacturing helper tool developer

Responsibilities:

- Built Gerber / Excellon to STL conversion workflow.
- Integrated CadQuery / Trimesh backend.
- Implemented stencil cutout, fixture generation, and VTK preview.
