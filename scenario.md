# 客户端场景示例
## 参数说明
| **参数名称** | **说明**                                                                 | **示例值**                                      |
|--------------|--------------------------------------------------------------------------|-------------------------------------------------|
| **URL**      | API的请求地址，用于指定调用的接口。                                       | `https://api.deepseek.com/v1/chat/completions` `https://api.deepseek.com/v1`|
| **模型ID**   | 指定调用的模型名称，用于确定API调用的具体功能。                           | `deepseek-ai/DeepSeek-R1` `deepseek-ai/DeepSeek-V3`                      |
| **API Key**  | 用于验证用户身份的密钥，确保只有授权用户可以访问API服务。                 | |


## 域名链接说明
- 请注意：不同客户端可能根据其功能需求选择不同的URL链接，请严格按照客户端的说明填写信息。

| **客户端类型** | **URL链接**                       | **说明**                                                                 |
|----------------|----------------------------------|--------------------------------------------------------------------------|
| 通用API调用    | `https://deepseek.modelverse.cn/v1` | 基础API接口，适用于通用功能调用，可能需要根据具体功能指定更多参数。       |
| 聊天功能调用   | `https://deepseek.modelverse.cn/v1/chat/completions` | 专门用于聊天功能的API接口，针对对话生成等任务优化，参数和返回结果更聚焦于聊天场景。 |

## 常见客户端举例
## 1.在 Chatbox 中使用

### 1.1关于ChatBox
Chatbox 是一个流行的大语言模型的全平台聊天客户端，特点是功能强大、安装简单。你可以用它接入各种大语言模型，然后在任何设备（电脑、手机、网页）上和 AI 聊天。

### 1.2 在 Chatbox 中使用 DeepSeek 模型
### 第一步：获取 API Key
如何获取api_key值，请点击[API列表](https://console.ucloud.cn/uapi/detail?id=GetUMInferService)，无需填写参数，点击「发送请求」即可根据模型名称选择你需要的API Key。
![](https://www-s.ucloud.cn/2025/02/d51820006284a8c28160dc669c505987_1739523878908.png)

### 第二步：
