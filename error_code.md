# 错误码

{{indexmenu_n>11}}

## 1）短信发送错误码

| **错误码**     | **错误提示及说明**          | **处理措施**                                                                                                                                                    |
| ----------- | -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 18001       | 请求参数有缺失              | 检查请求参数是否有缺失                                                                                                                                                 |
| 18000、18002 | 请求参数格式有误或请求JSON解析错误  | 检查请求参数格式是否有误                                                                                                                                                |
| 18003       | 请求参数无效               | 检查请求参数是否有问题                                                                                                                                                 |
| 18004、18007 | API或服务异常             | 联系[技术支持](https://www.ucloud.cn/site/service.html)                                                                                                           |
| 18013       | 当前账号/项目中的短信剩余量不足     | 先检查账号是否有短信余量，若不足，需[重新购买](https://console.ucloud.cn/usms?package_type=0&purpose=1&buy_amount=10)；若有余量，则联系联系[技术支持](https://www.ucloud.cn/site/service.html)处理 |
| 18014       | 提交的部分手机号码无效          | 剔除无效手机号码                                                                                                                                                    |
| 18016       | 当前账号/项目未申请短信签名       | 需先申请短信签名                                                                                                                                                    |
| 18017       | 当前短信模板不存在或未通过审核      | 需先申请短信模板 或 联系[技术支持](https://www.ucloud.cn/site/service.html)加速审核进度                                                                                          |
| 18018       | 短信模板参数与短信模板不匹配       | 检查模板参数是否有误 或 是否与模板匹配                                                                                                                                        |
| 18019       | 单次提交的手机号码超过1000个拦截发送 | 单次提交的手机号码数需在1000内                                                                                                                                           |

## 2）短信状态回执错误码

短信发送状态回执错误码可通过调用[获取短信发送回执信息](https://docs.ucloud.cn/api/usms-api/get_usms_send_receipt)
获取