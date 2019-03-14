# 1.1 平台接入说明

使用分贝通开放平台，首先需要获取相应的授权信息。请联系您的销售代表或相关人员，确定已经在分贝通开通企业管理后台，并已经录入企业授权负责人。

## - 必要信息

同时，需要提供以下信息：

- 需要接入方提供公司基本信息，公司名称、系统域名、公司资质等；
- 接入方调用分贝通开放平台的服务器IP地址；
- 如需消息通知，还请提供接受消息回调的URL地址。

接入方企业在获得分贝通授权后，会获得相应的企业id（app_id）和企业key（app_key），以及企业的签名密钥（sign_key）。这些信息会在进行鉴权的时候使用，以识别用户身份，请妥善保管。

|序号|术语|是否必需|说明|
|:--:|:--:|:--:|:---|
|1|app_id|是|识别接入公司的id|
|2|app_key|是|用于和app_id一起获取授权认证的密钥|
|3|sign_key|否|用于要求签名的接口调用，详见具体接口文档|

## - 接口地址