# Some small useful files for normal development

- *cmd_reg* - Converts windows console default encodeing to UTF-8 encoding

## 1. *cmd_reg*

I konw programmer love `UTF-8`, The file can solve a trouble that windows console default encoding is `GBK`.

I just did two jobs, one of which is to created a new Key `"CodePage"`(key name) of windows console in the Registry Editor(`regedit`), and changed its value to 65001(`UTF-8` page code), the other thing is modify the console size and font style in `console settings` and extract the registration file in Registry Editor(`regedit`).

You only need to double-click the registration file(`cmd.reg`) to register the infomation.
