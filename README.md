# template-tools
A command tool.To generate some template,autodownload some dependencies.

该项目用于快速下载webpack的loader依赖
使用用法如下:
```bash
root>>  node main.js -h
Usage: main [options]

generate some dependencies or some templates quickly

Options:
  -V, --version               output the version number
  -d,--download <loader>      to download webpack loader(use ',' to split args)
                              (multi choices: css,file,webpack)
  -s,--switchTool <toolName>  to switch the download tool,need to use with -d (choices: "npm", "cnpm", default: "npm")
  -h, --help                  display help for command

```
1.0.0->1.0.1

修复了不能使用命令的问题