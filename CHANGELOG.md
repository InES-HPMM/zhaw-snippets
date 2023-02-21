# Change Log

All notable changes to the "zhaw-snippets" extension will be documented in this file.

## 1.0.0

- Initial release

### 1.0.1

- Added header snippet for latex
- Moved to yarn

### 1.0.2

- Fixed latex header snippet

### 1.0.3

- Added header snippet for python
- Added header snippet for shell
- Added at least one empty line after the header insertion.

### 1.0.4

- Removed angle brackets from python header snippets
- Updated readme

### 1.0.5

- Updated the python header, to match common usage
- Standardized the header over all file types

### 1.0.6

- fix(python): moved one-line docstring onto the same line as the double quotes
  (PEP257)
- fix(python): added space after '=' symbol


### 1.0.7

- fix(vhdl): add escape character before @zhaw to escape the @ symbol (conflict
  with doxygen commands)
- fix(vhdl): remove the brief and detailed description from the header because
  doxygen expects the entity description before the entity declaration
- fix(python): define the authors email address in the \_\_email\_\_ variable
