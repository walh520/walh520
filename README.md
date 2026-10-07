# walh520 · 技术美术作品

**2028 届｜渲染 / 引擎 / 工具向 TA 实习**

围绕实时渲染、GPU 模拟与编辑器工具做项目，把效果实现、代码结构和验证边界一起呈现。

[作品集主页](https://walh520.github.io/) · [作品总集](https://www.bilibili.com/video/BV1MVak6jEPv/) · [B 站主页](https://space.bilibili.com/1080308077) · [GitHub](https://github.com/walh520)

> 本轮仅整理已上传到 GitHub 的部分作品，不代表全部作品。视频可能展示比仓库更多的功能、场景和资产；代码公开范围以每个项目说明为准。

## 精选项目

### [RenderingEngine](https://github.com/walh520/RenderingEngine)

把光传输、遍历后端、GPU 执行架构与时域重建放在同一运行时中比较，配套可复现捕获与分层验证。

Windows x64 研究与工程演示平台；局部 Debug 验证有记录，完整性能与视觉验收仍需补齐。

### [TA GPU Agents](https://github.com/walh520/TA_GPUAgents-Portfolio)

以效果 Profile 组织 GPU Agent、渲染后端和编辑器配置，连接 RDG 调度与 Niagara 数据接口。

公开 Profile / GPU / Niagara 源码快照；本地另有 Snowfall 与雨滴转移更新。UE 构建、PIE 与性能尚待验证。

### [TARibbon Dynamics](https://github.com/walh520/TARibbon-Portfolio)

围绕 GPU 持久状态、XPBD、Bake 数据与编辑器预览构建单片布料链路，并连接深度、速度和阴影通道。

GPU XPBD 单片布料源码快照；本地增加基础透明材质路径，透明排序、阴影及专用 Velocity 不作保证。

## 全部已上传部分

| 项目 | 当前公开内容 | 演示 |
| --- | --- | --- |
| [RenderingEngine](https://github.com/walh520/RenderingEngine) | Vulkan 路径追踪与 ReSTIR 实验平台；Windows x64 研究与工程演示平台；局部 Debug 验证有记录，完整性能与视觉验收仍需补齐。 | [总集](https://www.bilibili.com/video/BV1MVak6jEPv/) |
| [TA_GPUAgents-Portfolio](https://github.com/walh520/TA_GPUAgents-Portfolio) | UE GPU Agent 与效果渲染；公开 Profile / GPU / Niagara 源码快照；本地另有 Snowfall 与雨滴转移更新。UE 构建、PIE 与性能尚待验证。 | [视频](https://www.bilibili.com/video/BV1bxeJ6dEgf/) |
| [TARibbon-Portfolio](https://github.com/walh520/TARibbon-Portfolio) | UE GPU 单片布料系统；GPU XPBD 单片布料源码快照；本地增加基础透明材质路径，透明排序、阴影及专用 Velocity 不作保证。 | [视频](https://www.bilibili.com/video/BV1n5eA6FEAH/) |
| [TAVisualFracture-Portfolio](https://github.com/walh520/TAVisualFracture-Portfolio) | CPU 固定步长视觉破碎预览；CPU 固定步长编辑器预览；独立核心测试有记录，不是 GPU / Chaos 完整物理系统。 | [视频](https://www.bilibili.com/video/BV1Tteb6jEEr/) |
| [TA_Snow-Portfolio](https://github.com/walh520/TA_Snow-Portfolio) | 积雪数学与 Shader 核心节选；公开仓库仅数学/Shader 节选；本地有 Actor、表面捕获与网格链路，两者均未在本轮构建或运行验收。 | [视频](https://www.bilibili.com/video/BV1v8H76wEix/) |
| [ToonShaderMath](https://github.com/walh520/ToonShaderMath) | 定制 UE 5.7.4 · Toon / Substrate Shader 节选；11 个公开 Shader 与当前本地 UE 引擎对应文件一致；完整引擎接入未公开，来源授权仍需核对。 | [视频](https://www.bilibili.com/video/BV11Sej6kEGi/) |

## 阅读方式

先看演示了解作品，再在项目 README 查看实现与贡献、方案取舍、代码入口、验证状态、依赖和限制。源码可阅不等于开源许可；本页不以源码存在代替运行验证，也不提供未经测量的性能数字。

UE_ToonRendering 当前为空仓库，暂不作为精选项目；保留现有仓库。
