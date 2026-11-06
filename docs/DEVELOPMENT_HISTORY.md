# 研发历史 / Development history

## 从 Demo 到工作台

2026 年 9 月，Raman Demo 从整理碳材料 Raman 谱图和 D/G 峰拟合的实际需要出发。现存 Git 基线从 10 月 13 日开始。随后加入手动样品分组、重复测量、四列 TXT 处理和图形版本绑定，逐步形成七步工作台。

## 科学验证和交互编辑

10 月下旬，研发将峰高比的定义与出图结果对齐，并用预注册案例和独立参考检查拟合、诊断及边界情形。B42 暴露了局部残差诊断漏报，B49 暴露了独立测试输入生成器的精确零舍入边界。两例保留原记录并完成正式复测。

11 月初，专业编辑加入九种 D/G 峰型组合、参数锁定和重新优化。用户可先查看候选，确认后再保存为新版本。图组明确绑定结果版本，便于追溯导出图形的来源。

## 工程文件与安装候选

E3 将恢复数据和结果所需的信息封装到 .raman 工程，并支持 XLSX 与可编辑 Origin 工程。Aloka 品牌、中英文界面和独立 Windows 安装候选随后进入验收。11 月 6 日的内部运行时更新通过代表性工作流。发行许可和外部兼容仍须单独确认。

Aloka 由 Sun’s Workshop 独立开发。开发中使用了 AI 辅助工具，交付结果通过实际运行、回归测试和人工验收确认。

## English summary

Aloka evolved from a Raman demo into a workbench that keeps sample data, peak edits, confirmed results and figure versions linked. Scientific validation exposed a missed warning and a reference rounding edge case. The original evidence and formal retests were retained. The 1.0.0 RC1 work added self-contained projects, bilingual UI and a Windows installer candidate. Public downloads remain closed.

[Changelog](../CHANGELOG.md) · [Validation](VALIDATION.md)
