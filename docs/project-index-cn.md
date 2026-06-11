# 项目索引

## 总定位

AI-Native Embedded Development Loop 是一个总览仓库，用于展示"嵌入式 + AI Agent 驱动的软硬件开发闭环"。

它不是单一功能仓库，而是多个开源项目的入口和架构说明中心。

## 核心闭环

1. [SOAA：Agent 编排架构](https://github.com/11cookies11/Stack-Orchestrated-Agent-Architecture)
2. [EmbeddedLoop：Renode 仿真中的嵌入式软件闭环](https://github.com/11cookies11/EmbeddedLoopDemo)
3. [NexDAP：真实硬件调试闭环](https://github.com/11cookies11/NexDAP)
4. [KiCad Agent Suite：硬件设计自动化](https://github.com/11cookies11/kicad-agent-suite)
5. [ProtoFlow：通信协议自动化测试](https://github.com/11cookies11/ProtoFlow)

## 辅助工具

1. [RenodeWorkbench：VS Code 仿真工具](https://github.com/11cookies11/RenodeWorkbench)
2. [ShellLink：ESP32-C3 端侧执行器](https://github.com/11cookies11/ShellLink)
3. [Where：Agent 任务可视化](https://github.com/11cookies11/Where)
4. [StencilForge：PCB 钢网生成工具](https://github.com/11cookies11/StencilForge)

## 简历角色

项目发起人 / 架构设计者 / 核心开发者 / AI Agent + Embedded 工具链设计者

## 一句话介绍

我正在构建一套 AI Agent 驱动的嵌入式软硬件开发闭环，让 Agent 不只停留在代码生成，而是可以参与任务编排、固件构建、Renode 仿真、真实硬件调试、硬件设计、通信协议测试和迭代验证。

## 项目关系

```text
SOAA
  -> EmbeddedLoop
  -> NexDAP
  -> KiCad Agent Suite
  -> ProtoFlow

RenodeWorkbench / ShellLink / Where / StencilForge 作为配套工具支撑整个闭环。
```
