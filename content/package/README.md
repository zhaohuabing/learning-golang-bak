Package用于组织一组逻辑上紧密相关的go文件。是go语言中代码重用的基础单元。在文件系统中，一个Package对应一个文件夹，文件夹中包含该package中的多个go文件。在go语言模型中，一个Packag中包含了多个紧密相关的变量，结构体和方法。

Package中包含的内容：

```bash
└── package                           
    ├── variable
    ├── function
    └── struct
        ├── variable
        └── method
```