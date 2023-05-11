# hanhan-plugin

## 安装

> 下载插件或者复制插件里面的代码，然后放在example文件夹内，然后安装依赖

## 安装依赖

因为买家秀用到了`axios`，所以要安装这个依赖，在云崽根目录执行`pnpm install axios -w`，如果你之前装过，可以跳过

安装完依赖之后，重启机器人，就可以食用了

## nav

发送`nav`查看功能
> 憨憨小功能：
>
> (#)(兽语|猫语|喵语|狗语|动物语)加(解)密
>
> (#)兽语帮助
>
> (#)mt
>
> (#)买家秀
> 
> (#)随机ai 
>
> (#)今天是几号
>
> (#)历史上的今天
>
> (#)ping (ip/域名)
>
> (#)摩斯加(解)密
>
> (#)url编(解)码
>
> (#)base64编(解)码

## 功能详情
### 兽语加(解)密
可以发送`兽语帮助`查看相关帮助

### mt

随机返回一张美腿图片

### 买家秀

随机返回一张淘宝买家秀图片，有的很辣眼睛

### 随机ai

随机返回一张ai图片

### 今天是几号

> 返回示例：
> 公元2023年03月27日
>
> 农历癸卯年闰二月初六
> 兔年
>
> 节气：春分后
### 历史上的今天
返回10条历史上的今天的新闻
### ping ip/域名
> 返回示例：
>
> 网址：baidu.com
>
> ip地址：110.242.68.66
>
> 节点：河北省保定市顺平县 联通
> 
> 最小延迟：25.457ms
> 
> 最大延迟：25.556ms
> 
> 平均延迟：25.500ms
>
> 数据包数：5
> 
> 接受数据包：5
> 
> 丢包率：0%
> 
> 总耗时：4005ms

### 摩斯加(解)密

> 示例：
> 加密：憨憨	-->	--....--.-.-.../--....--.-.-...
>
> 解密：--....--.-.-.../--....--.-.-...	-->	憨憨

### url编(解)码

> 示例：
> 编码：憨憨	-->	%E6%86%A8%E6%86%A8
>
> 解码：%E6%86%A8%E6%86%A8	-->	憨憨

### base64编(解)码

> 示例：
> 编码：憨憨	-->	5oao5oao
>
> 解码：5oao5oao	-->	憨憨

## 说明

> 调用接口可以实现很简单的的无用小功能，有手就能写，你杠就是你对
>
> 因为是部分功能是调用的接口，接口寄了功能也就寄了，可以给我提issues，我能换接口我就换，找不到我就下架功能。
