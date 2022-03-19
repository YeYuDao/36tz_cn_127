# 36tz_cn_127
Nginx体系化深度精讲，从青铜到王者的飞跃
Nginx体系化深度精讲，从青铜到王者的飞跃
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fd1912e090418be05400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 Nginx开门见山 

#### 结合《2019年Q3季度的互联网吸引力人才报告》与招聘网站岗位需求，从不同视角，不同维度分析Nginx“江湖”地位，让小伙伴清楚无论是大中小企业还是互联网公司，抑或是初中高级前端、后端、运维甚至是实习生岗位都是在招聘中有明确要求的。...
1-1 形神兼具：体系化修炼Nginx【从广度到深度，从青铜到王者】 (18:42)


### 第2章 Nginx初体验 

#### 本章介绍了Nginx诞生的历史背景，重点列出其在企业级环境中的应用场景，Nginx高并发的根源所在，最后利用rpm简单部署一个Nginx。
2-1 课程结构概述 (06:55)

2-2 Nginx概述 (09:23)

2-3 Nginx缘起历史 (05:07)

2-4 Nginx主流企业场景 (08:26)

2-5 Nginx核心优势 (06:41)

2-6 安装第一个rpm包Nginx (16:06)


### 第3章 前方高能-Nginx进程结构与热部署 

#### 从Nginx进程结构说起，引入信号量机制，并利用信号量对Nginx进程管理；讲解热部署完整步骤、模块化机制等，通过本章学习，小伙伴们可动手编译安装定制化Nginx，可对线上WEB业务进行热升级，可以配置三种形式(多网卡、端口、域名、)虚拟主机。 ...
3-1 Nginx的进程结构 (06:35)

3-2 Linux的信号量管理机制 (07:23)

3-3 利用信号量管理Nginx (18:33)

3-4 配置文件重载的原理真相 (06:11)

3-5 Nginx的热部署 (08:07)

3-6 Nginx热部署完整步骤演示 (09:49)

3-7 Nginx模块化设计机制 (10:15)

3-8 Nginx编译安装的配置参数 (05:12)

3-9 定制编译安装第一个Nginx-上 (14:21)

3-10 定制编译安装第一个Nginx-下 (08:33)

3-11 Nginx配置文件结构-上 (14:40)

3-12 Nginx配置文件结构-下 (14:38)

3-13 虚拟主机的分类 (03:29)

3-14 基于多网卡的虚拟主机实现 (18:22)

3-15 基于端口的虚拟主机实现-上 (10:27)

3-16 基于端口的虚拟主机实现-下 (07:26)

3-17 基于域名的虚拟主机实现 (15:35)


### 第4章 核心指令-Nginx基础应用

#### 对配置文件main段核心参数进行讲解；对server_name、location指令进行了重点讲解；重点针对易混淆知识点做了特别说明，例如root和alias的区别、location中URL后面的/；通过本章的学习，小伙伴们将收获：熟练使用location指令来部署WEB业务。 ...
4-1 配置文件main段核心参数用法-上 (20:51)

4-2 配置文件main段核心参数用法-下 (18:25)

4-3 配置文件events段核心参数用法 (17:27)

4-4 server_name指令用法 (13:44)

4-5 server_name指令用法优先级 (19:48)

4-6 root和alias的区别 (12:15)

4-7 location的基础用法 (09:39)

4-8 location指令中匹配规则的优先级 (11:23)

4-9 深入理解location中URL结尾的反斜线 (11:07)

4-10 stub_status模块用法 (08:43)


### 第5章 HTTP核心模块-Nginx应用进阶

#### 案例实践驱动式学习，如:限制连接数的limit_conn模块、限制请求速率的limit_req模块、限制IP访问access模块、限制特定用户访问auth_basic模块、URL重写的rewrite模块；本章收获：对业务特定URL进行重写，对业务中模块进行限速，限制用户访问等。 ...
5-1 再谈connection和request (05:30)

5-2 对connection做限制的limig_conn模块 (17:20)

5-3 对request处理速率做限制的limit_req模块 (20:19)

5-4 限制特定IP或网段访问的access模块 (08:48)

5-5 限制特定用户访问的auth_basic模块 (16:28)

5-6 基于HTTP响应状态码做权限控制的auth_request模块 (20:47)

5-7 rewrite模块中的return指令 (15:08)

5-8 rewrite模块中的rewrite指令 (12:33)

5-9 return和rewrite指令执行顺序 (05:36)

5-10 rewrite模块中if指令 (18:08)

5-11 autoindex模块用法 (10:18)

5-12 Nginx变量的分类 (06:25)

5-13 TCP连接相关变量 (07:51)

5-14 发送HTTP请求变量-上 (17:30)

5-15 发送HTTP请求变量-下 (07:38)

5-16 处理HTTP请求变量 (08:16)


### 第6章 场景实践-反向代理【企业案例|焦点效应】

#### 从动静分离说起，引入反向代理，介绍反向代理协议；重点：反向代理模块upstream用法、配置Nginx实现应用服务的反向代理；通关本章将收获：如何利用Nginx对应用服务进行负载均衡，更重要深入细节，帮助小伙伴们技术实力的提升。 ...
6-1 反向代理基础原理 (07:36)

6-2 动静分离 (08:33)

6-3 使用Nginx作为反向代理时支持的协议 (03:29)

6-4 用于定义上游服务的upstream模块 (06:25)

6-5 upstream模块指令用法详解 (12:35)

6-6 配置一个可用的上游应用服务器 (07:39)

6-7 配置nginx反向代理实例 (12:51)

6-8 proxy_poass指令用法常见误区 (11:56)

6-9 代理场景下Nginx接收用户请求包体的处理方式 (23:01)

6-10 代理场景下Nginx如何更改发往上游的用户请求-上 (26:43)

6-11 代理场景下Nginx如何更改发往上游的用户请求-下 (08:10)

6-12 代理场景下Nginx与上游服务建立连接细节 (06:46)


### 第7章 场景实践-负载均衡【企业案例|沃尔森法则】

#### 本章对轮询算法、hash算法、ip_hash、最少连接数等负载均衡算法做了阐述，动手配置实现对多台应用服务的负载均衡，对上游服务出现故障时如何容错进行讲解。本章收获：对WEB业务扩容实现多台服务器负载均衡，打造一个高可用高可靠性的WEB系统。 ...
7-1 负载均衡基础 (06:15)

7-2 配置实现Nginx对上游服务负载均衡 (12:52)

7-3 负载均衡算法-哈希算法 (12:22)

7-4 负载均衡算法-ip_hash算法 (04:48)

7-5 负载均衡算法-最少连接数算法 (08:57)

7-6 负载均衡场景下Nginx针对上游服务器返回异常时的容错机制-上 (07:41)

7-7 负载均衡场景下Nginx针对上游服务器返回异常时的容错机制-中 (11:39)

7-8 负载均衡场景下Nginx针对上游服务器返回异常时的容错机制-下 (11:45)


### 第8章 场景实践-缓存及HTTPS【企业案例|黑洞效应】

#### 讲解缓存指令用法，实现对上游应用服务响应内容进行缓存;缓存失效时降低上游应用服务压力方法;引入缓存清除的第三方模块;讲解在Nginx上配置https服务。本章收获:掌握Nginx缓存功能；定制对WEB业的缓存；将线上业务配置成加密的https服务。 ...
8-1 缓存基础 (08:35)

8-2 缓存相关指令用法 (12:15)

8-3 缓存用法配置示例 (16:12)

8-4 配置Nginx不缓存上游服务特定内容 (08:18)

8-5 缓存失效降低上游压力机制一-合并源请求 (06:23)

8-6 缓存失效降低上游压力机制二-启用陈旧缓存 (11:03)

8-7 第三方清除模块ngx_cache_purge介绍 (03:20)

8-8 ngx_cache_purge用法配置示例 (12:13)

8-9 https原理基础 (07:22)

8-10 https如何解决信息被窃听的问题 (16:15)

8-11 https如何解决报文被篡改以及身份伪装问题 (08:55)

8-12 配置私有CA服务器 (11:43)

8-13 组织机构向CA申请证书及CA签发证书 (12:33)

8-14 配置Nginx为https服务器 (16:12)


### 第9章 深入Nginx架构，重塑思维

#### 本章挺进Nginx架构，探究Nginx灵魂内核，目的是帮助小伙伴重塑思维。将探讨Nginx的架构，包括Nginx的事件处理模型，多路IO服用的优势，连接池等内容，助力小伙伴们更好的使用Nginx服务于工作中的方方面面。
9-1 Nginx高可用基础 (10:48)

9-2 虚拟路由冗余协议VRRP原理 (15:39)

9-3 KeepAlived软件架构 (10:10)

9-4 使用KeepAlived配置实现虚IP在多服务器节点漂移-上 (20:19)

9-5 使用KeepAlived配置实现虚IP在多服务器节点漂移-中 (14:54)

9-6 使用KeepAlived配置实现虚IP在多服务器节点漂移-下 (12:51)

9-7 KeepAlived+Nginx高可用原理 (10:42)

9-8 KeepAlived+Nginx高可用配置示例 (22:01)


### 第10章 Nginx性能优化，提升B格

#### 本章探讨深入优化Nginx组件性能的各种企业场景，设计系统底层的TCP协议优化、磁盘IO优化等，同时也会介绍nginx自身模块的优化问题，帮助小伙伴们更好的掌握优化方法论，凭实力制胜，立于不败之地。
10-1 性能优化基础 (13:00)

10-2 提升Nginx利用CPU的效率 (19:05)

10-3 TCP三次握手和四次挥手 (18:16)

10-4 TCP建立连接优化 (26:40)

10-5 启用TCP的Fast Open功能 (10:06)


[下载地址](http://www.36tz.cn "下载地址")
