### 共享出行APP API V1.20 概览

| 功能 | 查看详情 |
| -------- |  ----|
|  接口说明   |   [view](接口使用说明.md)    | 
|  文档书写规范   | [view](文档书写规范.md)    | 
|  接口返回码清单   | [view](返回码清单.md)  | 


### 基础接口

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  获取accessToken   |  user/accesstoken [user/accesstoken](#user-content-123)    |  [view](details/user/accesstoken.md)    | 
|  获取版本信息   |  app/getappversions     |  [view](details/app/getappversions.md)    | 



### 用户相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  用户注册   |  member/register     |  [view](details/member/register.md)    | 
|  用户登录   |  member/login     |  [view](details/member/login.md)    | 
|  忘记密码，密码重置   |  member/forgetpass     |  [view](details/member/forgetpass.md)    | 
|  修改登录密码   |  member/updateloginpass     |  [view](details/member/updateloginpass.md)    | 
|  修改手机号   |  member/updatemobile     |  [view](details/member/updatemobile.md)    | 
|  设置支付密码   |  member/setpaypassword     |  [view](details/member/setpaypassword.md)    | 
|  修改支付密码   |  member/updatepaypassword     |  [view](details/member/updatepaypassword.md)    | 
|  忘记支付密码，密码重置   |  member/forgetpaypass     |  [view](details/member/forgetpaypass.md)    | 
|  用户信息   |  member/memberinfo     |  [view](details/member/memberinfo.md)    | 



### 车辆相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  车辆列表   |  car/list     |  [view](details/car/list.md)    | 
|  车辆品牌列表   |  car/brandlist     |  [view](details/car/brandlist.md)    | 
|  车辆热门品牌列表   |  car/hotbrandlist     |  [view](details/car/hotbrandlist.md)    | 
|  车辆车型列表   |  car/modellist     |  [view](details/car/modellist.md)    | 
|  车辆热门车型列表   |  car/hotmodellist     |  [view](details/car/hotmodellist.md)    | 
|  车辆筛选信息   |  car/screen     |  [view](details/car/screen.md)    | 
|  地图车辆列表   |  car/carnearby     |  [view](details/car/carnearby.md)    | 
|  车辆详情   |  car/view     |  [view](details/car/view.md)    | 
|  车主设置分享   |  ownercenter/changesharestatus     |  [view](details/car/changesharestatus.md)    | 
|  车主设置租金价格   |  ownercenter/updaterentmembermoney     |  [view](details/car/updaterentmembermoney.md)    | 
|  车主长租车辆   |  ownercenter/ownercar     |  [view](details/car/ownercar.md)    | 
|  车主设置油费方式   |  car/updateoilcalway     |  [view](details/car/updateoilcalway.md)    | 
|  下单油费计算方式   |  car/caroilcalway     |  [view](details/car/caroilcalway.md)    | 
|  订单油费方式列表   |  order/caroilcalway     |  [view](details/order/caroilcalway.md)    | 



### 订单相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  租客订单列表   |  order/listr     |  [view](details/order/listr.md)    | 
|  车主订单列表   |  order/listc     |  [view](details/order/listc.md)    | 
|  租车下单   |  order/addorder     |  [view](details/order/addorder.md)    | 
|  订单详详情   |  order/view     |  [view](details/order/view.md)    | 
|  租客或车主拍照列表   |  order/listorderimg     |  [view](details/order/listorderimg.md)    | 
|  租客或车主订单拍照上传   |  order/addorderimg     |  [view](details/order/addorderimg.md)    | 
|  车主同意拒绝   |  order/audit     |  [view](details/order/audit.md)    | 
|  费用调整页面详情   |  costadjust/view     |  [view](details/costadjust/view.md)    | 
|  费用调整原因列表   |  costadjust/resonList     |  [view](details/costadjust/resonList.md)    | 
|  费用调整发起请求   |  costadjust/adjustcontain     |  [view](details/costadjust/adjustcontain.md)    | 
|  费用调整反馈提交   |  costadjust/feedback     |  [view](details/costadjust/feedback.md)    | 
|  订单油费方式更改   |  order/chooseoilcalway     |  [view](details/order/chooseoilcalway.md)    | 
|  车辆当前位置-车辆经纬度   |  car/currentlocation     |  [view](details/car/currentlocation.md)    | 



### 认证相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  租客认证之前   |  authentication/authenticationbefore     |  [view](details/authentication/authenticationbefore.md)    | 
|  图片上传   |  upload/uploadadd     |  [view](details/upload/uploadadd.md)    | 
|  身份证或驾照认证提交   |  authentication/authenticationsubmit     |  [view](details/authentication/authenticationsubmit.md)    | 



### 资金相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  余额明细列表   |  money/accountlist     |  [view](details/money/accountlist.md)    | 



### 设备管理相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  添加设备信息   |  equipmentinfo/addequipmentinfo     |  [view](details/equipmentinfo/addequipmentinfo.md)    | 



### 消息推送

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  消息推送   |  appinfo/push     |  [view](details/appinfo/push.md)    | 


### 消息中心

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  消息列表   |  messagecenter/list     |  [view](details/messagecenter/list.md)    | 
|  查看消息   |  messagecenter/view     |  [view](details/messagecenter/view.md)    | 
|  删除消息   |  messagecenter/delete     |  [view](details/messagecenter/delete.md)    | 



### 短信相关

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  发送短信   |  user/smscode     |  [view](details/user/smscode.md)    | 
|  验证短信验证码   |  user/verifysmscode     |  [view](details/user/verifysmscode.md)    | 



### <a name="123">客服相关</a>

| 接口功能 | 接口地址 |查看详情 |
| -------- |----- |----- | 
|  客服电话   |  customerservice/tel     |  [view](details/customerservice/tel.md)    | 
