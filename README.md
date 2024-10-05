**目录**

* [g1 简介](#_label0)
* [工作原理](#_label1)
* [提示策略](#_label2)
* [关键特点](#_label3)
* [用户界面](#_label4)
* [Groq API](#_label5)
* [Groq API调用限制](#_label6)
* [Streamlit 页面示例](#_label7)
 



---



[Top](#_labelTop)## g1 简介



g1 是一个开源项目，利用 Llama 3\.1 70b 模型在 Groq 硬件上实现类似 OpenAI o1 的推理链能力。项目通过精心设计的提示策略引导语言模型进行逐步推理，解决了传统语言模型在逻辑推理方面的不足。
[Top](#_labelTop):[豆荚加速器](https://yirou.org)## 工作原理


* 利用动态推理链，逐步引导 Llama 3\.1 模型完成复杂逻辑问题
* 模型按步骤进行推理，每步都有明确的标题和内容
* 确保推理过程可视化和结构化


[Top](#_labelTop)## 提示策略


* 要求模型使用至少三种不同方法解决问题
* 探索多种可能性，提高解决问题的准确率


[Top](#_labelTop)## 关键特点


1. 推理过程透明度高
2. 用户可查看每步推理的标题和内容
3. 增强用户对模型的信任
4. 促进语言模型技术的进一步发展


[Top](#_labelTop)## 用户界面


* 使用 Streamlit 构建友好的交互界面
* 方便用户体验 g1 的推理能力


# 一键整合包


下载链接：https://pan.quark.cn/s/f22c34995982
使用方法：
1. 解压下载的文件
2. 修改 start\_streamlit.bat 脚本中的 API
3. 运行脚本


[Top](#_labelTop)## Groq API


获取 Groq API key：https://console.groq.com/keys
注意：
* Groq 提供的 API 允许开发者使用其服务来推理运行在 Groq LPU 上的大型语言模型
* API 是免费的，与 OpenAI API 兼容
* 开发者可轻松将 Groq 的推理服务集成到应用程序中


[Top](#_labelTop)## Groq API调用限制


![](https://yunyingmenghai.feishu.cn/space/api/box/stream/download/asynccode/?code=NjdiYWVlZjcwMDg1MzMyNzU5ZGU4YTQ3MDNlYmM3MWJfcDBFeHo5Q1hEM1N5MUFuYWhycUxZOHZJdGF1N2hjWmpfVG9rZW46WHhhOGJLZjNxb2FmTkV4OWQ5QWNuRDhIbmtlXzE3Mjc5MjQ2MzU6MTcyNzkyODIzNV9WNA)
[Top](#_labelTop)## Streamlit 页面示例


 
![](https://yunyingmenghai.feishu.cn/space/api/box/stream/download/asynccode/?code=NDQzZjRhYzNmNzUzMjM4NDk0NmI4MzMzNWNmODMyMjdfVFYyYlFySVN6dmZZNUNucFlOQW5pWDJrblJFSWRTcktfVG9rZW46VzRZMGJKaURsb2xWNDh4RVZxTWNoZkt3bmNWXzE3Mjc5MjQ2MzU6MTcyNzkyODIzNV9WNA)
项目地址：https://github.com/bklieger\-groq/g1


