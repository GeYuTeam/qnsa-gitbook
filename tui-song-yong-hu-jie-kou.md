# 推送用户接口

---

**简要描述：**

```
    去哪上岸平台用户注册并完善资料，申请平台产品订单后，会调用该接口为合作平台推送用户
```

**请求URL：**

```
    平台方提供
```

**请求方式：**

```
    POST

    Content-Type：application/json;charset=utf-8
```

**参数：**

| 参数名 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| userId | 是 | String | 用户id |
| realName | 是 | String | 姓名 |
| idNo | 是 | String | 身份证号码 |
| mobile | 是 | String | 手机号 |
| wechatNo | 是 | String | 微信号 |
| qqNo | 是 | String | qq号 |
| education | 是 | String | 学历: 硕士及以上 本科 大专 中专/高中及以下 |
| regionCode | 是 | String | 区域 |
| livingAddress | 是 | String | 居住地址 |
| ifSocialSecurity | 是 | String | 是否缴纳社保: 否 是 |
| contactName | 是 | String | 紧急联系人姓名 |
| contactRelationship | 是 | String | 紧急联系人关系: 配偶 父母 兄弟姐妹 子女 同事 同学 朋友 |
| contactPhone | 是 | String | 紧急联系人电话 |

**返回示例：**

{

"status": "1",

"msg": "推送成功"

}

**返回参数说明：**

| 参数名 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| status | 是 | String | 状态：1-成功，0-失败 |
| msg | 是 | String | 返回描述 |



