# 有道API Workflow

由于macOS自带字典功能大多时候并不能满足使用，故而想到利用Alfred向有道和Google等提供的API发送请求来方便日常的翻译需求。

略过有道API的申请，具体workflow的实现照搬了[这位博客大佬](https://www.cnblogs.com/flipped/p/9473701.html)的流程。

- 补上了向Alfred输出结果时的基本释义项
- 补上了请求参数`to`使其能够支持中译英，以及各种别的语言译成中文

## 具体使用步骤
1. 下载`yd.alfredworkflow`后导入Alfred
2. 在Alfred设置中找到并以文件夹形式打开，即`Open in Folder`
3. 打开其中的`yd.py`文件，将其中的第11行和第13行对照注释和自己申请的有道服务进行修改
4. 保存退出就能正常使用
