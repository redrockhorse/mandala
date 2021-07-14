# database specification
## 数据库开发规范
#### 参考:
https://github.com/Highflyer/MySQL_DESIGN_SPEC
https://blog.csdn.net/zwhfyy/article/details/82462533
1. 命名规范 \
**[force]** 库名/表名/字段名,禁止使用数据库保留字,常被误用的有password,name,data, \
如USER不能用于表名、列名等，但是USER_NAME可以用于列名，USER_INFO也可以用于表名。 \
参考:https://dev.mysql.com/doc/refman/5.7/en/keywords.html \
**[force]** 字母全部小写 \
**[force]** 只能使用英文字母、下划线、数字进行命名，首位字符必须是英文字母 
**[force]** 命名中多个单词间采用下划线分隔，以便阅读同时方便某些工具对数据库对象的映射。如xxx_xxx_xxx，但不限于三段式。
**[force]** 库名无前缀,表名前缀tb_，表空间前缀ts_,主键前缀pk_,外键前缀fk_,普通索引idx_ \
**[force]** 管理后台系统表前缀tb_adm_,内容发布系统表tb_cms_,工作流系统表tb_wf_
**[force]** 库名、表名、字段名禁止超过32个字符
2. 开发规范 \
**[force]** 不准使用存储过程/触发器 \
**[force]** 表字符集使用utf8mb4字符集，校验字符集使用utf8mb4_general_ci

