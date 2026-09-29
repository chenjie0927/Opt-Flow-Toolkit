# Opt-Flow-Toolkit：One Source, Dual Build Targets for WASM and MPI

同一份 OSTRICH / Flow 源码，支持两种编译目标：
- WASM — 面向浏览器 / WebAssembly 运行环境
- MPI — 面向传统 HPC 并行环境
- 采用 INP 模板文件 + 字符串占位符的方式进行动态配置

## 目标
- 保持 OSTRICH / Flow 核心算法源码统一，不为两个目标分叉维护
- 通过构建层适配，分别产出 WASM 与 MPI 版本
- 最小化对上游源码的侵入性修改

## 参考
- docs\architecture\OSTRICH - One Source, Dual Build Targets for WASM and MPI.md