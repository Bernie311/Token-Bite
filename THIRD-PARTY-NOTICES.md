# 第三方组件与素材声明

Token Bite 应用代码保持私有。下列第三方组件保留各自许可，程序 ZIP 内的 `licenses` 提供已归集文本；这些许可不自动成为 Token Bite 的开源许可。

| 组件 | 版本 | 许可 | 程序包内文本 |
|---|---|---|---|
| Python | 3.11.9 | PSF and bundled component notices | `licenses/python/LICENSE.txt` |
| Pillow | 12.3.0 | MIT-CMU and bundled imaging libraries | `licenses/pillow/LICENSE` |
| tiktoken | 0.14.0 | MIT | `licenses/tiktoken/LICENSE` |
| regex | 2026.9.29 | Apache-2.0 / included notices | `licenses/regex/LICENSE.txt` |
| requests | 2.34.2 | Apache-2.0 | `licenses/requests/LICENSE` |
| urllib3 | 2.8.0 | MIT | `licenses/urllib3/LICENSE.txt` |
| idna | 3.20 | BSD-3-Clause | `licenses/idna/LICENSE.md` |
| charset-normalizer | 3.5.2 | MIT | `licenses/charset-normalizer/LICENSE` |
| certifi | 2026.7.22 | MPL-2.0 | `licenses/certifi/MPL-2.0.txt` |
| OpenSSL | 3.0.13 | Apache-2.0 | `licenses/openssl/LICENSE.txt` |
| Tcl | 8.6.12 | Tcl/Tk license | `licenses/tcl8.6/license.terms` |
| Tk | 8.6.12 | Tcl/Tk license | `licenses/tk8.6/license.terms` |
| PyInstaller bootloader | 6.22.3 | GPL with bootloader exception / Apache-2.0 | `licenses/pyinstaller/COPYING.txt` |
| Fusion Pixel and inherited fonts | bundled files | SIL OFL-1.1 | `licenses/assets/fonts/OFL.txt` |
| o200k tokenizer data | bundled file | MIT | `licenses/assets/encodings/TIKTOKEN-LICENSE.txt` |


Pillow 的许可文件包含该轮子随带的图像、字体及压缩库声明。Python 许可文件保留其所含组件声明；另见 [SQLite 上游公共领域说明](https://www.sqlite.org/copyright.html)。Microsoft VC/UCRT 运行组件遵循 Microsoft 对应条款，不能视为本项目原创素材。

certifi 对应的未改动 Python 源文件和 CA PEM 以 `third-party-sources/certifi-source.zip` 随程序包提供，MPL 原文一并保留。这只涉及第三方组件，不包含 Token Bite 应用源码。

版本优先由实际程序内版本常量和配套构建记录核对；regex、idna 等辅助项另与原打包环境文件比对。该表是已归集清单，不宣称完成所有静态链接传递依赖的独立法律审计。

## 状态角色与品牌

程序包含 `clawd-laptop.webp`，来源文件与本机安装的 Clawd Laptop 宠物素材一致，其描述为原 Claude Desktop 角色打字动画。本次未找到允许随独立软件再分发的授权文件；角色和原始画面权利仍归原权利人。**署名不替代再分发授权。** 公开包含该素材的程序与演示前，需要发布者核实适用权利或使用获得授权的素材。

相关 OpenAI、Codex、Anthropic、Claude、Clawd 名称及标记属于各自权利人。Token Bite 是独立项目，不表示官方制作、认证或背书。

## 参考

- [PyInstaller 许可及打包例外](https://pyinstaller.org/en/stable/license.html)
- [OpenSSL 3.0.13 许可](https://github.com/openssl/openssl/blob/openssl-3.0.13/LICENSE.txt)
- [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
- [相同名称第三方素材条目：许可显示 unknown](https://www.aimcp.info/de/codex-pets/clawd-laptop-da7b2012)

最后一个条目仅作核查线索，不作为本地文件拥有分发许可的证据。
