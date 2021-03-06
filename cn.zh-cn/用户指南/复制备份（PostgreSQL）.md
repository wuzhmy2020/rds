# 复制备份<a name="rds_09_0032"></a>

## 操作场景<a name="rds_08_0009_section4332314314536"></a>

华为云关系型数据库服务支持复制自动和手动备份，制作一个不同名的拷贝。

**限制条件：**

只支持在同一region下复制并使用备份，暂不支持跨region操作。

账户余额大于等于0元，才可复制备份。

**备份保留策略：**

-   如果删除实例，该实例的自动备份将会被同步删除。
-   如果开启了实例的[自动备份策略](设置自动备份策略.md)，当实例的自动备份保留期结束，该实例的自动备份也将会被同步删除。
-   如果需要长期保留自动备份，您可以复制该自动备份生成一个手动备份，该手动备份在您删除它之前将会一直保留。
-   如果手动备份所使用的空间超过您的默认存储空间，则可能会增加华为云关系型数据库存储成本。

## 操作步骤<a name="rds_08_0009_section56693485162629"></a>

1.  登录管理控制台。
2.  单击管理控制台左上角的![](figures/Region灰色图标.png)，选择区域和项目。
3.  选择“数据库  \>  云数据库 RDS“。进入云数据库 RDS信息页面。
4.  在“实例管理“页面，单击实例名称，进入“基本信息”页面，在左侧导航栏，单击“备份恢复“，选择目标备份，单击操作列中的“复制“。

    您也可以在左侧导航栏，单击“备份管理”，在“备份管理”页面，选择目标备份，单击操作列中的“复制“。

5.  填写新备份名称和描述，单击“确定”。
    -   备份名称的长度在4\~64个字符之间，必须以字母开头，区分大小写，可以包含字母、数字、中划线或者下划线，不能包含其他特殊字符。
    -   备份描述不能超过256个字符，不能包含\>!<"&'=特殊字符。

6.  新备份创建成功后，用户可在“备份管理”页面，查看并管理自己的备份。

