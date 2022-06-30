# communityRepairSystem
毕业设计-基于微信小程序的小区报修系统
后端开发使用了Springboot，mybatis（还有一点点mybatis-plus）
前端在管理界面使用了VUE，客户端使用的是微信开发平台原生
数据库使用的是mysql

配置：
  待更新

实现功能：
  居民：报修，查看订单，查看通知，投诉，查看投诉，查看回复
  维修员：查看待处理订单，接单/拒单，维修完成后确定修复，查看所有历史订单，查看通知
  管理员：小区，小区居民，维修员，维修员请假，管理员的管理，订单转派，查看和回复投诉，发送通知
  
未实现功能：
  登录，写死了
  消息通知，如有待处理订单几个，没显示
  维修员请假是否同意的状态更改，不稳定
  
可改进：
  追踪订单并发送提醒
