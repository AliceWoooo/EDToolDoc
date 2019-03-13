# EDTool使用说明文档
访问地址：https://alicewoooo.github.io/EDTool/

## 概况
EDTool 是一个基于 Python 开发的 Excel 表格差异比对工具， 主要通过计算新旧表格之间的列、行、单元格之间的差异，来定位 Excel 文件中修改的内容。 用户可以在交互界面中指定两个用于比较的 Excel 文件，系统将会自动对比名字一致的 Sheet 表， 得出的内容差异在将会在交互界面中标识显示。同时，用户也可以将比对结果导出到本地中进行查看。
### 详细信息
| 名称 | 信息 |
| --- | --- |
| 工具格式 | EXE |
| 导出文件格式 | JSON |
| 运行环境 | Windows |
| 编程语言 | Python 2.7 |
| GUI框架 | PyQT4 |
| Excel表格读取工具 | xlrd |
| 打包工具 | PyInstaller |
