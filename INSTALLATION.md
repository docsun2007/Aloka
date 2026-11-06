# 安装环境与使用说明 / Setup and usage notes

**Aloka 1.0.0 RC1 · Windows x64**

[Windows 安装包 / Windows Setup](https://github.com/docsun2007/Aloka/releases/download/v1.0.0-rc1/Aloka_Raman_Analyzer_1.0.0_RC1_OPENSSL_01_Review_Setup.exe) · [SHA-256 校验 / Checksums](https://github.com/docsun2007/Aloka/releases/download/v1.0.0-rc1/SHA256SUMS_RC1.txt) · [发行说明 / Release notes](https://github.com/docsun2007/Aloka/releases/tag/v1.0.0-rc1)

此页说明候选版本已经验证的环境和使用流程。  
This page describes the environment and workflow verified with the release candidate.

| 项目 / Item | 已验证范围 / Verified scope |
| --- | --- |
| Windows | 本机 Windows 11 x64 已验证安装、运行、保存和重开。 / Installation, operation, saving, and reopening verified locally on Windows 11 x64. |
| Excel | XLSX 生成已验证。Aloka 可独立导出，无需预装 Excel。 / XLSX export verified. Microsoft Excel is optional. |
| Origin | 本机 OriginPro 2026 已验证 OPJU 生成及独立重开。OPJU 需要另行安装并许可的 Origin，以及可用的 COM 自动化。 / OPJU export and independent reopening verified locally on OriginPro 2026. A separately installed and licensed copy of Origin with working COM automation is required. |

Windows 10、Windows ARM64、macOS、Linux 和其他 Origin 版本未获本轮兼容性确认。  
Windows 10, Windows on ARM, macOS, Linux, and other Origin versions are outside the verified scope.

## 基本流程 / Basic workflow

1. 建立样品组，逐组添加 TXT 测量文件并检查实验结构。 / Group TXT measurements by sample and check the experiment structure.
2. 设置分析区间和预处理参数，再执行分析。结合残差和诊断查看结果。 / Set the analysis range and preprocessing, run the analysis, and review the residuals and diagnostics.
3. 如需调整，从 Raman 图进入专业编辑器，锁定所需参数、重优化并确认结果。 / If changes are needed, open the peak editor from the Raman plot, lock the required parameters, refit, and confirm the result.
4. 在有写权限的目录保存 `.raman` 工程，按需导出 XLSX 或 OPJU。 / Save the `.raman` project to a writable folder and export XLSX or OPJU as needed.

问题反馈 / Feedback: [GitHub Issues](https://github.com/docsun2007/Aloka/issues).