# Graphite-
之前和同事翻译的一本书，对于从事系统监控领域的同事可以参考
# 购买连接
https://item.jd.com/12727811.html
# 目录如下
## 第 1 章　什么是 Graphite
什么是时序数据
时序数据库
存储注意事项
优先操作
Graphite 的发展历程
是什么让 Graphite 与众不同
简单的指标格式
绘图 API
快速原型制作
丰富的统计函数库
链式函数
案例研究：谁在生产环境中使用 Graphite
Booking．com
GitHub
Etsy
Electronic Arts
我为什么会选择 Graphite
## 第 2 章　监控惯例
监控三要素
故障检测
告警
容量规划
重新审视轮询/拉取模型
拉取模型
推模型
Graphite 适合监控领域吗
可组合的监控系统
遥测技术
指标路由
聚合
状态引擎
通知路由
存储引擎
可视化
总结
## 第 3 章　 Graphite 组件
Carbon
carbon-cache
carbon-relay
carbon-aggregator
过滤指标
内部统计数据
网络安全注意事项
Whisper
如何创建 Whisper 文件
保留策略和存档
Whisper 归档规则
计算 Whisper 文件的大小
解析 Whisper 文件
哪个归档处理我的查询
聚合方法
xFilesFactor
规划命名空间
性能考量
Graphite Web
Django 框架
Web 服务器
数据库
Memcached
事件
后端存储
总结
基本安装
垂直扩展
水平扩展
多站点复制
最后一点想法
## 第 4 章　构建你的第一个 Graphite 服务器
Synthesize 快速入门
Graphite 安装在哪里
安装包是否适用于我的操作系统发行版
有哪些安装方法
我应该使用 virtualenv 吗
有效使用 sudo
依赖项
从源码安装
准备你的 Web 数据库
配置 Carbon
carbon．conf
storage-schemas．conf
storage-aggregation．conf
最后一些准备工作
启动你的 Carbon 守护进程
配置 Graphite Web
local_settings．py
配置 Apache
验证你的 Graphite 安装
Carbon 统计
向 Carbon 提供新数据
构建你的第一张图表
## 第 5 章　 Graphite 用户界面
查找指标
浏览导航树
使用搜索功能
使用自动补全功能更智能地工作
通配符
Graphite Composer 窗口
嵌入式图表
工具栏
选择最近的数据
刷新图表
选择时间范围
导出短链接
从 URL 加载图表
保存我的图表
从我的图表中删除图表
“图表选项”菜单
添加图表标题
隐藏图例
隐藏坐标轴和网格
使用图表模板
线型图模式
面积图和堆叠图
调整 Y 轴
“图表数据”对话框
到底什么是目标
构建 Carbon 性能图表
分享你的工作
## 第 6 章　渲染 API
使用函数
从基础函数开始
数学与统计转换
过滤和排序
基于通配符分组
数据平滑和预测
调整指标标签
备用的输出格式
## 第 7 章　仪表盘
为什么需要仪表盘
Graphite 仪表盘
第三方仪表盘
Grafana
Tasseo
Dusk
自定义开发
Dashing
Rickshaw 和 D3．js
总结
## 第 8 章　定位 Graphite 性能问题
首要的，也是最基本的
故障诊断工具箱
生成指标和基准测试
CPU 利用率
磁盘性能
网络
检查指标
配置设置
Carbon
Graphite Web
日志
Carbon
Graphite Web
内核消息
失败场景
磁盘已满
CPU 饱和度
渲染问题
更上一层楼
## 第 9 章　扩展 Graphite
是什么让扩展 Graphite 变得“困难”
Peter 的 Graphite 故事
开端
受欢迎的痛苦
扫清下一个障碍
试试，再试试
资源最大化
避免停机
共享 Web 数据库
双向扩展
最后的一些想法
总结
## 附录 A 　 Carbon 和 Graphite Web 的内部统计
