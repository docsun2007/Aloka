# 第三方组件说明 / Third-party notices

Aloka 的 Windows 候选版使用 Qt、PySide6、Shiboken6、CPython、NumPy、SciPy、Matplotlib、Pillow、openpyxl、et_xmlfile、pywin32 及相关组件。各组件分别适用其自身许可证，第三方许可证授予的权利予以保留。

The Windows release candidate uses Qt, PySide6, Shiboken6, CPython, NumPy, SciPy, Matplotlib, Pillow, openpyxl, et_xmlfile, pywin32, and related components. Each component is governed by its own license. Rights granted by applicable third-party licenses are preserved.

- Qt 与 Qt for Python 含适用 LGPLv3 的组件。 / Qt and Qt for Python include components available under the LGPLv3. [Qt licensing](https://doc.qt.io/qt-6/licensing.html) · [Qt for Python](https://doc.qt.io/qtforpython-6/)
- 科学计算、绘图与 Excel 组件的条款由其各自项目提供。 / Scientific, plotting, and Excel libraries are governed by their respective project licenses. [NumPy](https://numpy.org/doc/stable/license.html) · [SciPy](https://github.com/scipy/scipy/blob/main/LICENSE.txt) · [Matplotlib](https://matplotlib.org/stable/project/license.html)
- Origin、OriginPro 和 Excel 是各自权利人的产品。OPJU 导出使用用户另行安装的 Origin。 / Origin, OriginPro, and Excel are products of their respective owners. OPJU export uses the user’s separate Origin installation.

本页为展示阶段的组件说明。完整发行声明与适用的对应源码材料仍在审核，安装包尚未开放。  
This page summarizes third-party components for the showcase. The complete distribution notices and applicable corresponding-source materials remain under review. Installer downloads are not available yet.
## 候选运行时 / Candidate runtime

内部候选使用 CPython 3.14.10、OpenSSL 3.5.9 及 Qt 6.12.0。Qt 在 Windows 上使用 Schannel。发行候选载荷排除了 Qt Virtual Keyboard、Qt PDF/PDFium 和可选 Qt OpenSSL 后端。适用的许可证通知、对应源码和库替换信息仍在整理。

The internal candidate uses CPython 3.14.10, OpenSSL 3.5.9 and Qt 6.12.0. Qt uses Windows Schannel. The candidate payload excludes Qt Virtual Keyboard, Qt PDF/PDFium and the optional Qt OpenSSL backend. Applicable license notices, corresponding source and library replacement information remain under review.

[CPython license](https://docs.python.org/3/license.html) · [OpenSSL license](https://openssl-library.org/source/license/)
