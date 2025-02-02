AI Image Description Generator
================

**[English](./README.md)** | **[中文](./README_zh.md)**

**AI说图解图** 精准提取图片中的主要元素，解读图片创作目的；可用于科研、艺术创作中图文互搜领域.  

* 它是基于 **ERNIE 3.5** 或 **GEMINI-PRO-1.5** API;
* 支持7种语言;
* 集成**clerk.com**用户管理平台;
* 它是基于Next.js构建的全栈 web 应用解决方案;

截图与演示
----------------

![AI Image Description Generator Screenshot 1](./public/assets/screenshot-2.png "Screenshot 1")
![AI Image Description Generator Screenshot 2](./public/assets/screenshot-1.png "Screenshot 2")

DEMO: [www.imagedescriptiongenerator.xyz](https://imagedescriptiongenerator.xyz/)

快速开始
----------------

步骤1. 安装Node.js 18.17以上版本.  
  
步骤2. 运行next.js服务

```sh
cd <project_path>
npm install
npm run dev
```

步骤3. 打开浏览器, 访问 **<http://localhost:3000>**

官方网站
----------------

* [www.imagedescriptiongenerator.xyz](https://imagedescriptiongenerator.xyz/)

目录结构
----------------

```text
root      // next.js 项目
├─ public   
├─ src
	├─ app  //功能页面
    ├─ components     // next.js 自定义组件
    ├─ dictionaries   // 这里增加新的语言支持,JSON文件
    ├─ lib            // ernie和gemini api服务实现 
```

其它
----------------

***⭐ 如果您喜欢这个项目，请加一颗星 ⭐***
