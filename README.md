# 基于Spark4.0 Ultra模型的情绪助手
# Emotion Assistant Based on the Spark4.0 Ultra Model

## 1.项目简介（Project Introduction）
本项目基于 Spark 4.0 Ultra 模型的 API 构建了一个多样化的情绪助手系统。系统内置了不同的情绪助手面具，如雷电将军、初音未来和心理专家。此外，还通过快捷指令添加了特色情绪助手，如台湾女生、哲学家等。系统前端使用 React 框架开发，后端基于讯飞星火平台。项目适用于本科毕业设计，暂不推荐用于商业用途。
<br>
<br>
_The project is based on the Spark 4.0 Ultra model API to build a variety of emotion assistant systems. The system includes built-in emotion assistant masks such as Raiden Shogun, Miku, and Psychologist. Additionally, it adds special emotion assistant masks through shortcut instructions, such as Taiwan girls and philosophers. The front-end is developed using the React framework, and the back-end is based on the XunFei Spark platform. The project is suitable for undergraduate dissertation work, and it is not recommended for commercial use._
<br>
## 2.项目基础（Project Foundation）
本项目前端使用了开源项目 __NextChat__，网址为 https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web
<p>开源文件在 __/others__ 文件中的 __from-open-resources.zip__ 中。</p>
<br>
<br>
<p>_This project uses the open-source project __NextChat__. The website is https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web </p>
<p>The open source file is in the __from-open-resources.zip__ file in the __/others__ file._</p>

<br>
## 3.项目运行（Project Running）
### （1）前端环境 （Front-end Environment）
Node 18.16.0

Yarn 1.22.22 （安装包在 others 文件夹中 _The installation package is in the others folder_）

### （2）前端运行 （Front-end Running）
yarn install

yarn build

yarn start

### （3）后端环境 （Back-end Environment）
讯飞星火平台 

### （4）后端运行 （Back-end Running）
在讯飞星火平台上，找到 __接口地址__，如图

_Find the __API endpoint__ on the Xunfei Spark platform, as shown in the picture._
<br>
<br>
<img src="/others/show1.png"/>
<br>
<br>
<br>
在讯飞星火平台上，找到 __APIKEY__ 和 __APISecret__，如图

_Find the __APIKEY__ and __APISecret__ on the Xunfei Spark platform, as shown in the picture._
<br>
<br>
<img src="/others/show2.png"/>
<br>
<br>
<br>
在 __/app/config/server.ts__ 中，找到 __// iflytek only__ 这行注释，填入 __接口位置__ , __APIKEY__ 和 __APISecret__，如图

_Find the __// iflytek only__ line in __/app/config/server.ts__, fill in the __API endpoint__, __APIKEY__, and __APISecret__, as shown in the picture._
<br>
<br>
<img src="/others/show3.png"/>
<br>
<br>
<br>
### 4.注意事项（Precautions）

###### （1）头像
头像如果显示不了是因为网络问题，使用国外网络即可显示

###### （2）报错
项目有时候报500或者加载模块慢都是网络的问题，使用国外网络即可解决

###### （3）build问题 （build problem）
项目中存在许多类型检查的逃避声明，主要是由于开发人员在更换电脑后，运行 yarn build 时频繁遇到类型错误，但是项目本身没有问题，所以开发人员不得不选择使用逃避类型检查的方式来运行项目。

_The project contains many type checking escape declarations, mainly because the development team encountered type errors frequently when running yarn build, but the project itself was not affected. Therefore, the development team had to resort to using escape type checking to run the project._

###### （4）对话（Conversation）

进入项目后首页的对话是 __通用模型__，调用 __面具__ 和 __快捷指令__ 后就可以和情绪助手对话了。项目中的 __发现__ 模块中还有个画图功能，可以自行导入对应的api使用。

### 5.开发人员（Developers）
狸猫科技 _Lihuacat Technology_

感谢燕京理工学院 __陈炜导师__ 的指导
_Thanks to __Mentor Chen Wei__ from Yanjing University of Science and Technology for the guidance._
<br>
<br>

### 6.项目展示（Project Display）
<img src="/others/show4.png"/>

<img src="/others/show5.png"/>

<img src="/others/show6.png"/>
