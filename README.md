![image](https://github.com/AngelaViVi/Expressior/blob/Expressior_master/src/DynamoCoreWpf/UI/Images/StartPage/dynamo-logo.png) 
====================================

|分支|Expressior_master|Expressior_slim|
|:--------:|:----------:|:-------------:|
|构建状态|[![Build status](https://ci.appveyor.com/api/projects/status/ke5nv5l0d33w5tl2/branch/Expressior_master?svg=true)](https://ci.appveyor.com/project/AngelaViVi/expressior/branch/Expressior_master)| 尚未构建|

### 这是一个可视化编程环境

#### 声明
1. 本程序基于AutoDesk的Dynamo开发,遵循Dynamo的协议.源代码完全公开.<br>
2. 如果侵犯了您或您的组织的合法权益,请联系作者进行删除.<br>
3. 对于由于不遵守Apache协议的其他用户使用本程序而造成的不良影响和损失,作者不负任何责任.<br>
4. [Github of Dynamo](https://github.com/DynamoDS/Dynamo)<br/>

### 目的
1. 构建一个可视化编程工具,能够在代码和"逻辑图"之间进行转换.<br>
2. 将该工具应用到深度学习模型的开发和调试中.<br>
3. 针对深度学习任务提供优化和额外的工具支持.<br>
4. 维持原有程序框架的可扩展性,并针对深度学习任务进行定制,实现对用户可扩展.<br>

### build
1. Microsoft Visual Studio 2015<br>
2. GitHub for Windows<br>
3. Microsoft .NET Framework 4.5.<br>
4. Microsoft DirectX (install from %GitHub%\Expressior\tools\install\Extra\DirectX\DXSETUP.exe)<br>

### 配置
1. DynamoSandBox和LibraryViewExtension使用x64配置,其余使用AnyCpu配置.<br>
2. 启动项目是DynamoSandBox.<br>

### 其他说明
1. [Draw.io](https://www.draw.io/)<br>
2. 由于最终目标不同,这个程序在Dynamo的基础上进行了大幅度的删改,基础版本是Dynamo的RC2.0.0分支.<br>
3. 如果您对这个程序有兴趣,在查阅文档的时候请注意,由于2的缘故,Dynamo的文档可能并不不适用于本程序,您可以向开发者询问感兴趣的问题.<br>
4. 后续开发的默认分支是Expressior_master分支.<br>

### New Features
1. 现在支持Dicom图像的读取了:<br>
![image](https://github.com/AngelaViVi/Expressior/blob/Expressior_master/log/shot/DicomReading.png) 