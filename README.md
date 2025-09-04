统一配置头部注释格式和函数注释格式：
//头部注释
    "fileheader.customMade": {
        "Description": "",   // 介绍文件的作用、文件的入参、出参。
        "Author": "",   //作者
        "Date": "Do not edit",  // 设置后默认设置文件生成时间
        "License": "Apache 2.0"   //许可证
    },
    // 函数注释
    "fileheader.cursorMode": {
        "description": "", // 函数注释生成之后，光标移动到这里
        "param": "", // param 开启函数参数自动提取 需要将光标放在函数行或者函数上方的空白行
        "return": "", 
    },
    "fileheader.configObj": {
        "cursorModeInternalAll": {
             "ts": true, // ts文件后缀是函数内生成函数注释
             "js": false, // js文件后缀是在函数外生成函数注释
             "python": true, // python语言类型文件时在函数内生成函数注释
             "defaultSetting": false // 默认是在函数外生成注释
        }
}
