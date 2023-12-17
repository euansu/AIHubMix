<div align="center">
<img src="./images/logo.png" alt="icon" width="50px"/>
  
<h1 align="center">AI Hub Mix</h1>

支持 GPT-4 / GPT-4-1106-preview / GPT-4-vision-preview
GPT-3.5 / GPT-3.5-Turbo / GPT-3.5-Turbo-16K  </br>
Embeddings / DALL·E / Whisper 

**负载均衡无需代理 大陆直联官方半价**

[快速开始](https://aihubmix.com/) / [API说明文档](https://zltb2uon31.feishu.cn/wiki/VSYzwt3mki9t0Rk3xFjcss8Gnuh) / [详细见模型支持]( https://zltb2uon31.feishu.cn/wiki/FffXwmLQSifRN4kUxHHcXOCHnud) 

[点击加客服微信](https://zltb2uon31.feishu.cn/docx/Wq6AdmGotowLpYxAmN7cadv8npQ)

</div>

## 站点地址
### https://aihubmix.com/

备用地址： https://orisound.cn/

## 计费模式
与官方 API 扣费规则保持一致，充值后额度一直有效，用完为止。我们价格是官方的五折, 3.5 元等于 1 美元

价格说明：目前是 17.5 元人民币购买 5 美元的额度，这 5 美元官方能用多少 token 你就能用多少 token 。

## AI Hubmix
其设计初衷就是要让用户能够更简单、更经济地接入 OpenAI 的强大 API 功能。通过 AI Hubmix ，用户无需直接申请和管理 OpenAI API 的密钥，他们可以通过我们优化的管道，得到与直接调用 OpenAI 服务完全一致的体验。提供 API ，首页有详细的使用方式，可以用本站部署的 WebUI ，也可以用自己习惯的客户端。

## AI Hubmix 的优势： 
1. 我们的 API 调用费用仅为 OpenAI 官方标价的一半，得益于我们美国合作方的官方批发通道，大幅降低用户的成本开销。
2. 我们接受支付宝作为支付选项，简化支付流程，便于用户的接入和使用。
3. 我们的 API 密钥池中不仅包括了 OpenAI 服务，还包括了微软 Azure 通道，以支持无限速的请求处理，增加你系统的稳定性。

## 原理介绍
aihubmix 是一个 OpenAI API 反代服务，它可以让用户直接调用 OpenAI 的人工智能 API ，而无需自行申请 OpenAI API 的额度。在用户调用 API 时，orisound 会将请求转发至自己的 open ai api key 账号池中，然后再通过 OpenAI 的官方 API 接口将请求发送至 OpenAI 的服务器进行处理。

aihubmix 的账号池包含多个 OpenAI API 账号，每个账号都具有一定的 API 请求配额。当一个账号的 API 请求配额用完时，orisound 会自动切换到另一个账号，以确保 API 的可靠性和稳定性。同时，aihubmix 还具有高并发处理能力，可以在用户高并发请求时，保持 API 响应速度和稳定性。

## 支持模型
GPT-3.5 ，GPT-4 ，dallE ，gpt-4-1106-preview ，gpt-4-vision-preview 等；[详细见模型支持]( https://zltb2uon31.feishu.cn/wiki/FffXwmLQSifRN4kUxHHcXOCHnud)

## 购买方式

支持支付宝

付款后自动发送兑换码至下单时填写的邮箱，购买网页也会弹出兑换码。我们也会随时人肉跟进，遇到任何问题直接联系我们

P.S.
需要官方 openAI 带 credits 账号的朋友，也可以联系客服
