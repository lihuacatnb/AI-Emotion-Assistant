# 基于Spark4.0 Ultra模型的AI情绪助手

---

📖 **本 README 为中文版本**，点击这里查看 [English version](./README_EN.md)  

---

## 1.项目简介
本项目基于 **Spark 4.0 Ultra 模型** 构建了一个多样化的 **AI 情绪助手系统**。
系统支持：
- **面具助手**：雷电将军、初音未来、心理专家  
- **快捷指令助手**：台湾女生、哲学家等  
- **功能扩展**：在“发现”模块可导入自定义 API 进行画图等操作  

前端使用 **React 框架**，后端基于 **讯飞星火平台**，适合本科毕业设计或 AI 情绪助手学习研究。

## 2.项目基础
- 前端基于开源项目 [**NextChat**](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)  
- 开源文件位于 `/others/from-open-resources.zip`


## 3.项目运行
### （1）前端环境
- Node 18.16.0
- Yarn 1.22.22（安装包在 others 文件夹中）

### （2）前端运行
- yarn install
- yarn build
- yarn start

### （3）后端环境
讯飞星火平台（需获取接口地址、APIKey 和 APISecret）

### （4）后端运行
- 在讯飞星火平台获取 **接口位置**
<br>
<img src="/others/show1.png"/> <br>
<br>
<br>

- 获取 **APIKey** 和 **APISecret**  
<br>
<img src="/others/show22.png"/>
<br>

- 在 __/app/config/server.ts__ 中，找到 __// iflytek only__ 注释，填入 __接口位置__ , __APIKEY__ 和 __APISecret__，如图
<br>
<img src="/others/show3.png"/>
<br>

## 4.注意事项
- ⚠️ **头像显示问题**：头像无法显示可能是网络原因，使用国外网络即可显示 
- ⚠️ **报错问题**：出现 500 错误或模块加载慢，多为网络问题，使用国外网络即可解决  
- ⚠️ **build 类型报错**：项目中存在许多类型检查的逃避声明，主要是由于开发人员在更换电脑后，运行 yarn build 时频繁遇到类型错误，但是项目本身没有问题，所以开发人员不得不选择使用逃避类型检查的方式来运行项目  
- 💬 **对话使用**：首页默认通用模型，切换面具或快捷指令即可与情绪助手对话  
- 🎨 **画图功能**：项目中的 __发现__ 模块中还有个画图功能，可以自行导入对应的api使用




## 5.开发人员团队
- 狸猫C型AI
- 特别感谢 **燕京理工学院 陈炜导师**

## 6.项目展示
<img src="/others/show4.png"/><br>
<br>
<br>
<img src="/others/show5.png"/><br>
<br>
<br>
<img src="/others/show6.png"/><br>
<br>
<br>

---

<p align="center">⭐️ 如果你觉得有帮助，欢迎点个 Star 支持一下！ ⭐️</p>
