##This is the task list of the event "ISCAS & openEuler Community Open Source Promotion Plan - Summer 2020"

----

# 开源软件供应链点亮计划2020，SODA Foundation 任务列表

## 项目一
---
1. 项目标题：
开发nbp项目中的在线扩容功能
2. 项目描述：
nbp能通过api，controller和dock进行卷的创建，但随着业务的深入，数据量会逐渐增大，数据盘的容量会变得不能满足需求，需要进行扩容。请在nbp中实现卷的在线扩容功能。
3. 项目难度：
中
4. 项目社区导师：
刘羽
5. 导师联系方式：
ThisIsClark@163.com
6. 项目产出要求：
   - 完成nbp，api，controller和dock的部署，能通过nbp创建卷
   - 使nbp插件支持在线扩容
7. 项目技术要求：
   - 能使用go语言进行开发
   - Kubernetes 的使用
   - Kubernetes CSI插件的开发
   - 基本的 Linux 命令
   - 基本的 Git 命令
   - 基本的存储系统知识

8. 相关的开源软件仓库列表：
   - https://github.com/sodafoundation/nbp
   - https://github.com/sodafoundation/api
   - https://github.com/sodafoundation/controller
   - https://github.com/sodafoundation/dock

## 项目二
---
1. 项目标题：
实现driver作为plugin加载
2. 项目描述：
当前所有driver都会被编译到运行包中，程序启动时不管某款driver是否需要都会被加载进来，但实际上对于用户来说，并不是所有的driver都是需要的，加载额外的driver会给程序带来不必要的负担。
Go 1.8新增了plugin package，请使用这个机制，使程序启动时根据配置只以插件形式加载对应的driver
3. 项目难度：
高
4. 项目社区导师：
刘羽
5. 导师联系方式：
ThisIsClark@163.com
6. 项目产出要求：
   - 完成api，controller和dock的部署，能通过命令行创建卷
   - 通过go的plugin机制，使得程序运行时可以根据需求加载指定driver
7. 项目技术要求：
   - 能使用go语言进行开发
   - 基本的 Linux 命令
   - 基本的 Git 命令
   - 基本的存储系统知识

8. 相关的开源软件仓库列表：
   - https://github.com/sodafoundation/api
   - https://github.com/sodafoundation/controller
   - https://github.com/sodafoundation/dock

## 项目三
---
1. 项目标题：
开发nbp项目中的卷克隆功能
2. 项目描述：
为了更好的管理和保护数据，许多存储系统提供创建卷的克隆功能，Kubernetes也于v1.15引入了对卷克隆的支持。
目前nbp，api，controller和dock均未支持卷克隆，请进行相应开发使其支持卷克隆功能。
3. 项目难度：
中
4. 项目社区导师：
刘羽
5. 导师联系方式：
ThisIsClark@163.com
6. 项目产出要求：
   - 完成nbp，api，controller和dock的部署，能通过nbp创建卷
   - 使nbp插件支持卷克隆功能，能对接入dock的存储后端上的卷进行克隆
7. 项目技术要求：
   - 能使用go语言进行开发
   - Kubernetes 的使用
   - Kubernetes CSI插件的开发
   - 基本的 Linux 命令
   - 基本的 Git 命令
   - 基本的存储系统知识

8. 相关的开源软件仓库列表：
   - https://github.com/sodafoundation/nbp
   - https://github.com/sodafoundation/api
   - https://github.com/sodafoundation/controller
   - https://github.com/sodafoundation/dock

## 项目四
---
1. 项目标题：
引入Sanity作为nbp测试框架
2. 项目描述：
nbp通过kubernetes和CSI插件进行存储设备的管理，请使用Sanity进行CSI插件基本功能的测试
3. 项目难度：
低
4. 项目社区导师：
刘羽
5. 导师联系方式：
ThisIsClark@163.com
6. 项目产出要求：
使用Sanity完成nbp基本功能的测试
7. 项目技术要求：
   - 能使用go语言进行开发
   - Kubernetes 的使用
   - Kubernetes CSI插件的开发
   - 基本的 Linux 命令
   - 基本的 Git 命令
   - 基本的存储系统知识

8. 相关的开源软件仓库列表：
   - https://github.com/sodafoundation/nbp
   - https://github.com/sodafoundation/api
   - https://github.com/sodafoundation/controller
   - https://github.com/sodafoundation/dock
