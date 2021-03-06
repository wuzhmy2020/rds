# 创建手动备份<a name="rds_09_0028"></a>

## 操作场景<a name="zh-cn_topic_0171122845_section387888031450"></a>

华为云关系型数据库服务支持对运行正常的主实例创建手动备份，用户可以通过手动备份恢复数据，从而保证数据可靠性。

>![](public_sys-resources/icon-note.gif) **说明：**   
>当数据库实例被删除时，华为云关系型数据库实例的自动备份将被同步删除，手动备份不会被删除。  
>账户余额大于等于0元，才可创建手动备份。  

## 方式一<a name="zh-cn_topic_0171122845_section3535102285710"></a>

1.  登录管理控制台。
2.  单击管理控制台左上角的![](figures/Region灰色图标.png)，选择区域和项目。
3.  选择“数据库  \>  云数据库 RDS“。进入云数据库 RDS信息页面。
4.  在“实例管理“页面，选择指定的实例，在操作列选择“更多  \>  创建备份“。
5.  在创建备份弹出框中，命名该备份，并添加描述，单击“确定”，提交备份创建，单击“取消”，取消创建。

    -   备份名称的长度在4\~64个字符之间，必须以字母开头，区分大小写，可以包含字母、数字、中划线或者下划线，不能包含其他特殊字符。
    -   备份描述不能超过256个字符，且不能包含回车和\>!<"&'=特殊字符。
    -   手动备份创建过程中，状态显示为“创建中”，此过程所需时间由数据量大小决定。

    页面长时间未刷新，可单击页面右上![](figures/refresh-34.png)刷新页面，查看实例是否备份完成。若实例状态为正常，备份完成，执行[6](#zh-cn_topic_0171122845_li9129133519114)。

6.  <a name="zh-cn_topic_0171122845_li9129133519114"></a>手动备份创建成功后，用户可在“备份管理”页面，对其进行查看并管理。

    也可在“实例管理“页面，单击实例名称，在左侧导航栏，单击“备份恢复“，对其进行查看并管理。


## 方式二<a name="zh-cn_topic_0171122845_section56713052173915"></a>

1.  登录管理控制台。
2.  单击管理控制台左上角的![](figures/Region灰色图标.png)，选择区域和项目。
3.  选择“数据库  \>  云数据库 RDS“。进入云数据库 RDS信息页面。
4.  在“实例管理“页面，选择指定的实例，单击实例名称。
5.  在左侧导航栏中选择“备份恢复“，单击“创建备份“，命名该备份，并添加描述，单击“确定”，提交备份创建，单击“取消”，取消创建。
    -   备份名称的长度在4\~64个字符之间，必须以字母开头，区分大小写，可以包含字母、数字、中划线或者下划线，不能包含其他特殊字符。
    -   备份描述不能超过256个字符，且不能包含回车和\>!<"&'=特殊字符。
    -   手动备份创建过程中，状态显示为“备份中”，此过程所需时间由数据量大小决定。

6.  手动备份创建成功后，用户可在“备份管理”页面，对其进行查看并管理。

    也可在“实例管理“页面，单击实例名称，在左侧导航栏中选择“备份恢复“，对其进行查看并管理。


