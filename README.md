## 平台简介

>  闲鹿工作流是一款基于 RuoYi 4.x + Activiti 6.x + Spring Boot 2.x + Thymeleaf 3.x 的开源工作流管理系统~体验地址：http://47.96.25.96 
>
> 作为技术小菜鸟的我，一直对学习 Activiti 工作流框架求之不得，断断续续入门入了三次。这次能够写出这个项目主要归功于 ☕🐇 的[《Activiti 实战》](https://github.com/henryyan/activiti-in-action-codes)。这本书给予了我很大的帮助。最后但仍然重要的，我要感谢[若依框架](http://www.ruoyi.vip/)，她让我实现快速集成工作流 WEB 应用。—— from 一只闲鹿
>
> 参考资料👇
>
> 1. 若依框架: [http://www.ruoyi.vip](http://www.ruoyi.vip/)
> 2. Activiti User Guide: <https://www.activiti.org/userguide/index.html#springSpringBoot>
> 3. XBoot: [http://xboot.exrick.cn](http://xboot.exrick.cn/)



## 内置功能

v1.0

1.  新增流程 demo2：请假会签，支持请假列表、新增暂存、编辑、删除；提交申请 (含选择会签参与人)、表单数据、我的待办 (申请详情、审批、调整申请、销假)、我的已办。
2.  新增流程 demo1：请假业务，支持请假列表、新增暂存、编辑、删除；提交申请、表单数据、我的待办 (申请详情、审批、调整申请、销假)、我的已办。
3.  新增流程通用接口：审批历史和进度查看。
4.  新增流程用户组功能，支持流程用户组列表、新增、编辑、删除和导出。
5.  新增流程用户功能，支持流程用户列表、新增、编辑、删除和导出。
6.  新增流程定义功能，支持流程定义部署、列表、删除和导出。
7.  新增在线绘图功能，支持拖拽预览、在线绘图、下载 BPMN 文件和 SVG 文件。
## 在线体验
> 流程管理账号：admin / admin123
>
> 请假流程测试账号
>
> 普通员工：chengxy / 123456
>
> 部门领导：axianlu / 123456
>
> 人事：rensm / 123456

演示地址：http://47.96.25.96  (服务器太渣，时常宕机，推荐运行本地 demo)



## 演示图

<table>
    <tr>
        <td><img src="screenshot/main.png"/></td>
        <td><img src="screenshot/online.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/define.png"/></td>
        <td><img src="screenshot/user.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/useradd.png"/></td>
        <td><img src="screenshot/group.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/groupadd.png"/></td>
        <td><img src="screenshot/list.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/add.png"/></td>
        <td><img src="screenshot/detail.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/history.png"/></td>
        <td><img src="screenshot/process.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/todo.png"/></td>
        <td><img src="screenshot/done.png"/></td>
    </tr>
    <tr>
        <td><img src="screenshot/process2.png"/></td>
        <td><img src="screenshot/select.png"/></td>
    </tr>
</table>




## 闲鹿工作流交流群

QQ群：794711759。

![闲鹿工作流交流群](ruoyi-admin/src/main/resources/static/img/qr_code.png)
