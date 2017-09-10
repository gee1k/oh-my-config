# .editorconfig

- 通配符

| 通配符 | 说明 |
|------|------|
| * | 匹配除/之外的任意字符串 |
| ** | 匹配任意字符串 |
| ? |	匹配任意单个字符 |
| [name] |	匹配name字符 |
| [!name] |	匹配非name字符 |
| {s1,s2,s3} |	匹配任意给定的字符串(since 0.11.0) |

- 属性

| 属性 | 说明 |
|------|------|
| root | 表明是最顶层的配置文件，发现设为`true`时，才会停止查找.editorconfig文件 |
| indent_style | 设置缩进风格，`tab`或者`space`。tab是hard tabs，space为soft tabs。 |
| indent_size |	缩进的宽度，即列数，整数。如果`indent_style`为tab，则此属性默认为`tab_width`。 |
| tab_width |	缩进为`tab`时，缩进的宽度。默认是`indent_size`。 |
| end_of_line |	换行符，`lf`、`cr`和`crlf` |
| charset |	编码，`latin1`、`utf-8`、`utf-8-bom`、`utf-16be`和`utf-16le`。 |
| trim_trailing_whitespace |	设为`true`表示会除去换行行首的任意空白字符。 |
| insert_final_newline |	设为`true`表明使文件以一个空白行结尾。 |
