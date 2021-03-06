### 首页-搜索
- 用例名称
  >- 搜索
- 范围
  >- 首页
- 级别
  >- 用户目标
- 主要参与人员
  >- 顾客
- 涉众及其关注点
  >- 顾客: 能够快速，准确的找到目标店铺。并且能够有推荐店铺以及搜索历史记录
- 前置条件
  >- 顾客输入信息合理
- 后置条件
  >- 文本检测与匹配。数据库查询。
- 主成功场景
  >- 1.顾客输入搜索的信息
  >- 2.根据输入的信息进行匹配
  >- 3.显示匹配的结果，且结果按照一定的条件排序
- 扩展
  >- 无匹配项时，提示”未找到相应的结果“
- 发生频率
  >- 可能会不断发生
- 未决问题
  >- 匹配的关联程度
### 首页-扫码 
- 用例名称
  >- 扫码
- 范围
  >- 首页
- 主要参与人员
  >- 顾客
- 前置条件
  >- 获取摄像头权限
- 后置条件
  >- 二维码识别。数据库查询
- 简要说明
  >- 顾客使用扫码功能扫码二维码后，进入店铺
### 首页-进入店铺 
- 用例名称
  >- 进入店铺
- 范围
  >- 首页
- 主要参与人员
  >- 顾客
- 前置条件
  >- 地理位置获取。根据位置获取店铺
- 后置条件
  >- 数据库查询
- 简要说明
  >- 顾客点击店铺项后，进入店铺点餐页
### 首页-付款
- 用例名称
  >- 付款
- 简要说明
  >- 顾客出示付款条形码，店铺扫描后进行支付操作
### 首页-查看消息
- 用例名称
  >- 查看消息
- 简要说明
  >- 顾客点击消息，查看通知
### 扫码页-扫码 
- 用例名称
  >- 扫码
- 范围
  >- 扫码页
- 主要参与人员
  >- 顾客
- 前置条件
  >- 获取手机相机的摄像头权限
- 后置条件
  >- 识别二维码，查询店铺信息数据库
- 简要说明
  >- 顾客进入扫码界面使用扫码功能扫描二维码后，进入相对应的店铺
### 扫码页-进入店铺
- 用例名称
  >- 进入店铺
- 简要说明
  >- 根据顾客扫描二维码后从店铺管理系统查询反馈回来的店铺信息，进入相对应的店铺点餐页
### 店铺点餐页-去结算 
- 用例名称
  >- 去结算
- 范围
  >- 店铺点餐页
- 主要参与人员
  >- 顾客
- 前置条件
  >- 购物车不为空
- 后置条件
  >- 有网络，后端执行成功
- 简要说明
  >- 顾客点击该按钮，跳转到结算页面
### 店铺点餐页-返回
- 用例名称
  >- 返回
- 简要说明
  >- 顾客返回到主页或搜索结果页
### 店铺点餐页-品种导航
- 用例名称
  >- 品种导航
- 简要说明
  >- 顾客触摸左侧的菜式品种快速导航到该品种菜单列
### 店铺点餐页-点餐
- 用例名称
  >- 点餐
- 简要说明
  >- 顾客触摸菜品上的+按钮，将菜品添加到购物车中
### 店铺点餐页-添加购物车
- 用例名称
  >- 添加购物车
- 简要说明
  >- 顾客点击购物车可以增加减少菜品的数量，或者清空购物车
### 订单页-查看订单详情
- 用例名称  
  >- 查看订单详情    
- 范围  
  >- 付款页  
- 主要参与人员  
  >- 顾客  
- 前置条件  
  >- 用户已经选择菜品  
- 后置条件  
  >- 调用支付接口
- 简要说明  
  >- 顾客确认已点的菜品种类，数量等信息，准备进行支付 
### 订单页-查看订单状态
- 用例名称  
  >- 查看订单状态
- 简要说明  
  >- 查看支付步骤及相应支付状态
### 个人信息页-管理钱包 
- 用例名称
  >- 管理钱包
- 范围
  >- 个人页
- 主要参与人员
  >- 顾客
- 前置条件
  >- 绑定银行卡
- 后置条件
  >- 设置付款密码
- 简要说明
  >- 顾客可以点击我的钱包进行绑定或解绑银行卡
### 个人信息页-查看个人信息
- 用例名称
  >- 查看个人信息
- 简要说明
  >- 顾客查看、编辑自己的信息 
### 个人信息页-查看我的收藏
- 用例名称
  >- 查看我的收藏
- 简要说明
  >- 顾客可以查看自己已收藏的店铺并进入
### 个人信息页-管理优惠券
- 用例名称
  >- 管理优惠券
- 简要说明
  >- 顾客查看自己的优惠券
### 个人信息页-查看个人足迹
- 用例名称
  >- 查看个人足迹
- 简要说明
  >- 顾客查看自己去过的店铺历史记录
### 订单状态页-用户评分
- 用例名称
  >- 用户评分
- 范围
  >- 订单页
- 主要参与人员
  >- 顾客
- 前置条件
  >- 用户下单购买成功
- 后置条件
  >- 后台记录用户的评分
- 简要说明
  >- 顾客下单成功后可以在订单页进行评分
### 订单状态页-进入店铺
- 用例名称
  >- 进入店铺
- 简要说明
  >- 顾客在订单页可以选择进入购买过的该店铺，浏览其他商品的信息
### 订单状态页-进入订单详情
- 用例名称
  >- 进入订单详情
- 简要说明
  >- 顾客在订单页点击进入订单的详细信息，查看订单的状态，以及订该单详细信息