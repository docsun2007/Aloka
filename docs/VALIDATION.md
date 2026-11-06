# 科学与功能验证 / Scientific and functional validation

D、G 两峰各可采用 Gaussian、Lorentzian 或精确 Voigt，共九种组合。精确 Voigt 使用 Faddeeva 函数求值。专业编辑在指定边界内优化，已锁定参数保持在约束值。参数改动先进入候选，确认后形成独立分析版本。

I(D)/I(G) 是拟合 D 单峰与 G 单峰的峰高比。面积比单独记录。使用残差、RMSE、R²、模型不匹配和可辨识性诊断，并结合实验条件判断拟合是否适用。

| 证据索引 | 范围与方法 | 结果 |
| --- | --- | --- |
| E1 · 冻结 REV2 | 50 个预注册合成案例，按冻结规格用独立高精度参考检查数值或预期诊断。包括 B42 局部残差诊断复测与 B49 独立输入生成器的精确零边界复测。 | PASS，50/50。B42 初期 FAIL、B49 初期 BLOCKED 的记录保留。 |
| E2 · 专业编辑 | Windows 可见 GUI 操作覆盖选峰、拖动、锁定重优化、候选取消与确认、样品及版本隔离。 | PASS，已验收范围。 |
| E3 · 工程与导出 | 合成工程迁移后，在新进程恢复并继续编辑；检查 XLSX 与 OriginPro 2026 OPJU 的版本绑定、数据和可编辑性。 | PASS，已验收范围。 |
| OPENSSL-01 · 安装候选 | Windows 11 x64、OriginPro 2026。真实 GUI 验证安装、微软拼音、TXT、拟合、编辑锁定、v2 工程、XLSX/OPJU、独立重开和卸载保护。 | PASS，本机代表性工作流。 |
| OPENSSL-01 · 数值对照 | 同一合成输入比较旧、新运行时。八份数值 CSV 逐字节一致，五张 XLSX 数据表一致。版本、约束、曲线、指标和诊断一致。 | PASS，定向对照。E1 全量基准未在本运行时重跑。 |
| 外部 Windows 电脑 | 保存和 COM 自动化收到两个独立失败反馈。 | FAIL（历史反馈）；本候选外部复测 NOT TESTED。 |
| 其他环境 | Windows 10、Windows ARM64、macOS、Linux 及其他 Origin 版本。 | NOT TESTED。 |
| 对外安装包 | 最终第三方许可和分发材料待确认。 | BLOCKED。 |

证据索引对应内部验收记录，原始数据、日志和开发源码保留在内部。50/50 是通过的预注册合成案例数量，不能推算真实样品的科学准确率。

## English summary

The frozen REV2 suite passed 50 preregistered synthetic cases, including the formal B42 and B49 retests. Interactive editing, project reopening and version-bound Excel and OPJU exports were verified separately. A representative installed workflow passed on Windows 11 x64 with OriginPro 2026. The runtime comparison matched the saved numerical outputs for the same synthetic input. The affected external PCs have yet to be retested with this candidate.

[Known issues](../KNOWN_ISSUES.md) · [Verified environments](../INSTALLATION.md)
