# work-weixin-msg-sever-api

使用企业微信给自己微信发送消息的API，基于vercel

## 发送方式
get

## 参数

| 参数      | 类型  | 必选   | 描述               |
|---------|-----|------|------------------|
| id      | str | true | 企业微信公司id         |
| secert  | str | true | 企业微信应用的应用secert  |
| agentId | int | true | 企业微信应用的应用agentId |
| msg     | str | true | 需要发送的内容          |