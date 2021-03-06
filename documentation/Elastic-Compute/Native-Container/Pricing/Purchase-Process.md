
# 购买流程

**容器实例购买限制**

 1. 每个用户在每个地域均可创建20台容器实例，若您需要开通更多实例，可通过工单提出提升配额，京东云将根据您的实际需求进行评估后为您提升配额。
 2. 容器实例暂不支持配置调整
 3. 单台实例只允许绑定1个公网IP
 4. 单台实例数据盘至多挂载7块云硬盘

**云硬盘方法及限制**

购买方法： 

系统盘：只支持跟实例一起购买

系统盘文件系统格式支持xfs或ext4，创建容器时将根据已选择的文件系统格式对容器的系统盘进行格式化

系统盘的挂载目录为根目录“/”且不可修改

目前系统盘必须跟随容器删除

数据盘：支持随实例一起购买或单独购买： 

随实例一起购买

请参考创建容器实例

单独购买

容器实例只支持创建时关联数据盘

仅支持xfs或ext4格式的已有云盘作为容器的数据盘，添加其他文件系统格式的云硬盘将导致创建失败

请参考创建云硬盘

购买硬盘限制 

每个用户在每个地域均可创建20块云硬盘，若您需要创建更多云硬盘，可通过工单提出升额申请，京东云将根据您的实际需求进行评估后为您提升限额。

系统盘目前只支持SSD盘。

单台实例数据盘允许至多挂载7块云硬盘。

仅包年包月计费的云硬盘支持扩容


**购买公网IP方法及限制**
购买方法

公网IP支持随实例一起购买或单独购买：

随实例一起购买

请参考创建容器实例

单独购买

请参考创建公网IP

弹性公网IP限制：

每个用户在每个地域均可申请10个公网IP，若您需要申请更多公网IP，可通过工单提出升额申请，京东云将根据您的实际需求进行评估后为您提升配额。

单台实例只允许绑定一个公网IP。

购买公网IP带宽为上行带宽，即出带宽。

一个实例可进行多次绑定/解绑公网IP操作。如果想为已绑定公网IP的实例更换公网IP，必须先与当前绑定的公网IP解绑，之后再行绑定新的公网IP。

包年包月计费的公网IP支持上调带宽；按配置及按用量计费的公网IP支持上调或下调带宽。


**操作步骤：**

一、入口一：官网产品介绍页

打开京东云官网

选择产品-弹性计算-原生容器

进入原生容器产品介绍页，点击立即购买

二、入口二：控制台

登录京东云控制台

选择弹性计算-原生容器

进入容器实例，点击创建