# taobao-sdk-golang

### 注意
请替换自己的appkey、appsecret

### 用法示例见example/main.go文件
```
/**
 * 淘宝SDK，go语言实现版
 * 用法示例 :
 */ /*

	var reqParams map[string]interface{}
	reqParams = make(map[string]interface{})
	reqParams["platform"] = 1
	reqParams["q"] = "游戏机"
	reqParams["page_size"] = 2
	reqParams["page_no"] = 1
	reqParams["pid"] = "mm_xxxx"
	sdk := taobao.NewSDK("tttt", "eeee", "http://gw.api.taobao.com/router/rest")
	respMap, err := sdk.Execute("taobao.tbk.item.coupon.get", reqParams)
	log.Println("err", err)
	log.Println("respMap", respMap)

*/
```
