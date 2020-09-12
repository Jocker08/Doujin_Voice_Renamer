# Doujin_Voice_Renamer

### 使用说明:

**关键字**："circle", "workno", "title" 和 "cv", 模板中的这四个关键字将会被程序替换

**默认模板**: "template": "workno [circle] title (cv)"

**自定义模板**: 请修改 "config.json" 中的 "template"

例如："template": "[circle] title (workno)"

重命名前：RJ149268 哀しみのイき人形

重命名后：[Hypnotic_Yanh] 哀しみのイき人形《催眠音声・男女版同梱》 (RJ149268)

### 注意：

如需在自定义模板包含 "(cv)", 请将其放在模板字符串的末尾

- 正确的例子: "template": "workno [circle] title (cv)"
- 错误的例子: "template": "workno [circle] (cv) title" 这可能会导致在重命名后，文件夹名称中出现多余的空格

![示例图片](https://i.loli.net/2019/08/29/KJxOBVktrlfZ6sa.png)
