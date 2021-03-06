# 配置中心

confcenter（配置中心）是为用友云上运行的分布式应用提供配置文件管理功能的通用平台，该平台提供分布式环境下应用配置文件的分发与一致性检验功能等，让应用配置简便、快捷、准确。

## 功能简介


<br>
![](image/1.png)


通过一个统一的配置中心实现管理多种应用、同一应用的多个实例、同一应用的多种环境（Online/Test/Stage/Dev）等多种配置模式。实现配置在应用的统一修改，实时生效。提供配置文件修改历史记录等常用功能。并且结合用友云权限系统实现用户对配置文件的权限控制。方便用户对配置文件的管理。

## 主要特征


- 实现对分布式应用配置文件的统一管理
- 实现对应用不同环境（Online/Test/Stage/Dev）配置文件的管理
- 配置变化后线上应用状态的实时更新
- 简单的引入方式，单jar包依赖，提供注解式编程和无侵入引入方式
- 与用友云配合提供对普通应用配置文件的管理能力
- 配置文件内容的日常维护功能  


<center> 
传统配置文件管理
![](image/confserver3.png)


配置中心管理配置文件
![](image/2.png)


</center> 


### 配置文件统一分发
配置文件统一分发是由配置中心服务器端为使用指定配置文件的多个上线应用实例统一的推送配置文件。使用配置中心管理配置文件与传统管理配置文件的方法相比最大的好处就是极大地简化了用户的操作，让应用配置或者变更配置文件内容便捷化、可视化。此外配置统一分发还能够保持配置文件的一致性，防止相同的线上应用配置出现差异

### 配置文件实时更新
配置中心实时更新能力是上线应用能够快速感知配置文件变化的能力。配置文件变化后变更内容将被实时引入到运行态的应用代码，使用户在配置中心的改变能够迅速的反馈到运行态的线上应用，做到应用实例的零操作配置更新。

### 配置文件权限控制
以应用为单位，结合开发者中心用户系统进行权限控制。管理员能够对下级用户自由授权，管理不同人员对配置文件的控制权限。

![](image/confserver4.png)
