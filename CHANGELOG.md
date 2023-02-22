### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

#### [v1.1.3](https://github.com/InES-HPMM/zhaw-snippets/compare/v1.1.2...v1.1.3)

- ci: create two jobs, one which builds the extension, the other releases the extension [`b57830a`](https://github.com/InES-HPMM/zhaw-snippets/commit/b57830a4ca38200ec6d5c8732762436c866f1064)

#### [v1.1.2](https://github.com/InES-HPMM/zhaw-snippets/compare/v1.1.1...v1.1.2)

> 22 February 2023

- ci: renamed job to release [`9dc9f4d`](https://github.com/InES-HPMM/zhaw-snippets/commit/9dc9f4d7c25f99cc89fdb4db8d27cb0564a12496)

#### [v1.1.1](https://github.com/InES-HPMM/zhaw-snippets/compare/v1.0.7...v1.1.1)

> 22 February 2023

- chore: automatically generate the changelog when bumping the version of the package [`9372e3f`](https://github.com/InES-HPMM/zhaw-snippets/commit/9372e3ff1c60c2979427cbe832964f0b1c1aa4df)
- ci: GitHub workflow definition to automatically release and publish the extension [`a478aba`](https://github.com/InES-HPMM/zhaw-snippets/commit/a478abaff9c9315e9394a48f2162d1b60f8c83ed)
- docs: update the info in the readme [`4f9f4ee`](https://github.com/InES-HPMM/zhaw-snippets/commit/4f9f4ee8f40b18df0a38d5267d760f0710fadfd4)
- chore: add pre-commit hooks to automatically format json files with prettier [`7e3ebb4`](https://github.com/InES-HPMM/zhaw-snippets/commit/7e3ebb46c19f114be9a8958194041ca9c93d3320)
- chore: update info in package.json [`ff4bdf8`](https://github.com/InES-HPMM/zhaw-snippets/commit/ff4bdf8799c5d2334706443737ae0aa8cbb26c7f)
- fix: remove unecessary dependencies or move them to devDependencies [`e7a9804`](https://github.com/InES-HPMM/zhaw-snippets/commit/e7a98043f1d085eb1beddb16dce9d4a42ad75e53)

#### [v1.0.7](https://github.com/InES-HPMM/zhaw-snippets/compare/v1.0.6...v1.0.7)

> 21 February 2023

- fix(python): define the authors email address in the **email** variable [`28d3d23`](https://github.com/InES-HPMM/zhaw-snippets/commit/28d3d23e2e476e354d3ebcb962a1a4f3ceab1e53)
- fix(vhdl): add escape character before @zhaw to escape the @ symbol (conflict with doxygen commands) [`9e1cae7`](https://github.com/InES-HPMM/zhaw-snippets/commit/9e1cae7143930c087fb6cb3750cb15f1c9089fe2)
- fix(vhdl): remove the brief and detailed description from the header because doxygen expects the entity description before the entity declaration [`c8521e8`](https://github.com/InES-HPMM/zhaw-snippets/commit/c8521e8b4c96b413f929c33b993b7936639cf588)

#### v1.0.6

> 20 December 2022

- Build with yarn. [`dad1ca8`](https://github.com/InES-HPMM/zhaw-snippets/commit/dad1ca80a7c9d53084dc52e350c2408e363c7957)
- Updated packages and readme [`178d3c7`](https://github.com/InES-HPMM/zhaw-snippets/commit/178d3c7fdb932560ca93d64b9a9d6d691d3286a6)
- Standardized the header over all file types [`3044730`](https://github.com/InES-HPMM/zhaw-snippets/commit/3044730a0200e49b22dcaade6787c01c2c6cb386)
- Added header snippets for shellscript and python [`ee2c0ba`](https://github.com/InES-HPMM/zhaw-snippets/commit/ee2c0bacfd26f22605e1605f4c302d2f3431d3cf)
- Added necessary changes and files to provide this plugin as a vscode extension. [`20b79c0`](https://github.com/InES-HPMM/zhaw-snippets/commit/20b79c06e2b020087a6025ce52571d2ad399e3f9)
- Added InES file header snippets for vhdl and c/cpp. [`fe40a83`](https://github.com/InES-HPMM/zhaw-snippets/commit/fe40a83eae9a28197d983d1f07e2346bd9798a6b)
- Add InES header snippets for latex files. [`3e1bb26`](https://github.com/InES-HPMM/zhaw-snippets/commit/3e1bb265fd0d8ff035c7bf26a6ffdd78b5f9982a)
- Added installation instructions for VSCode and vim/nvim. [`8256745`](https://github.com/InES-HPMM/zhaw-snippets/commit/8256745fa20fbf0aadcce7afaad9377361596e9a)
- Updated the python header [`57f6cee`](https://github.com/InES-HPMM/zhaw-snippets/commit/57f6cee9a4f7c11759408eeddb95fae001758256)
- Split c and cpp snippets. [`c73c660`](https://github.com/InES-HPMM/zhaw-snippets/commit/c73c660415ef105371aae5bed83125fd1221f7f1)
- Initial commit [`0778e1a`](https://github.com/InES-HPMM/zhaw-snippets/commit/0778e1a0fe38df2fb3f8dff3650ff37164319d8c)
- Fixed the latex header snippet. [`234c3b8`](https://github.com/InES-HPMM/zhaw-snippets/commit/234c3b865459934c4b79a3832be9dc96df9f9d2e)
- fix(python): moved one-line docstring onto the same line as the double quotes (PEP257) [`5ce3a36`](https://github.com/InES-HPMM/zhaw-snippets/commit/5ce3a36c231f17cc6b0d0d6e3ad1e7f86f9e8d06)
- Removed angle brackets around the email address in the python header [`db9cae8`](https://github.com/InES-HPMM/zhaw-snippets/commit/db9cae8edbbad0a16d55bfd6cb96eae64cfc0a86)
- Added necessary changes and files to provide this plugin as a vscode extension. [`10930a4`](https://github.com/InES-HPMM/zhaw-snippets/commit/10930a42a9dc594e64138821d0e3ccfe68b3c6d0)
- Added necessary changes and files to provide this plugin as a vscode extension. [`6924273`](https://github.com/InES-HPMM/zhaw-snippets/commit/692427336033db05aa2df774d09a2658c6ce89eb)
- Added at least one empty line after the header insertion [`9a3a9d6`](https://github.com/InES-HPMM/zhaw-snippets/commit/9a3a9d6f553b7340dc4e2664cb2dc5bba1a97eea)
- fix(python): added space after '=' symbol [`a71db21`](https://github.com/InES-HPMM/zhaw-snippets/commit/a71db210e152745b83b633196e8d59a087cb9c20)
- Fixed the issue, where the backslash in front of the pipe character would be escaped. [`7203be6`](https://github.com/InES-HPMM/zhaw-snippets/commit/7203be67c6c5b85c26282d74aefdb8193b4f4e69)
