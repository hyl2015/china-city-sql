# 全国行政区域地址库

> 最新版本全国行政区域划分mysql版本，从腾讯地图获取到的数据，经过处理后的mysql版本sql文件，方便建立地址关联信息

如果有需要，可以从[腾讯地图api](http://apis.map.qq.com/ws/district/v1/list?key=CI7BZ-VIPKI-7VWGO-5HEZ4-NOEQ6-6KFOB) 重新获取

上面的链接提供的是我自己的key，如果已经失效则可以在腾讯开放平台创建
## 简单说明
* address_type 表示 地址类型 0-国家 1-省份 2-市 3-区
* address_code 区号
* province_id 所属的省份id，增加的冗余数据，方便某系操作
