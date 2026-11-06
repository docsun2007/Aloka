# 已知问题 / Known issues

| 问题 | 已确认范围 | 遇到时 |
| --- | --- | --- |
| 工程保存报 WinError 5 | 一台外部 Windows 电脑在微信接收目录写入时遇到拒绝访问。具体原因待查。工程必须先保存成功，Excel 才会生成。 | 在普通可写目录使用新文件名重试，保留原文件。记录失败阶段和错误码。 |
| Origin 自动化退出 0x36C10000 | 一台外部电脑的 OriginPro 2026 可手动生成并重开 OPJU，Aloka 自动化导出失败。开发电脑同主版本通过。失败阶段与原因待复测。 | 保留阶段与退出码，可单独保存工程与导出 XLSX。 |
| 平台 | Windows 11 x64 和本机 OriginPro 2026 已验证。其他 Windows、架构和 Origin 版本未确认。 | 反馈时附环境版本和已脱敏的复现记录。 |

On one external PC, saving to a messaging download folder returned WinError 5. Try a writable folder and a new filename. On another, OriginPro 2026 could save and reopen OPJU manually, but automation returned 0x36C10000. Both external retests are pending.

[Report an issue](https://github.com/docsun2007/Aloka/issues) · [Validation scope](docs/VALIDATION.md)
