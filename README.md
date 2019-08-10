# ItemRecord-AE5
## 总体介绍
1. 管理部队组织结构,直接使用管理平台现有的部门管理即可.
2. 管理登录用户所属部门,每个用户自动拥有所属部门及其所有自部门的官兵资金预警数据查看权限,直接使用管理平台现有的用户管理即可.
3. 官兵基础数据管理,用于按指定格式导入官兵的部门名称,姓名,身份证号后4位,银行卡号后4位,支持在页面单个或多个的增删改操作,支持一个官兵多个银行卡号,视为多条记录.
4. 资金预警规则管理,目前先开发资金流动时间非法,金额超限,次数超限三个规则,需要一个单独的页面对时间,金额,次数进行配置.后期可能有同一对方账户相关规则.
5. 获取官兵账户明细,每日结束定时按官兵账户请求农行接口,获取账户明细,这些账户明细是保密信息,虽然允许长期存放在数据库中,但是要考虑安全性问题.
6. 资金预警,根据查询条件中的部门,日期区间,规则类型等,查询违反规则的资金流动数据,只显示部门名称,姓名,身份证号后4位,银行卡号后4位,违反规则类型.
7. 出现未读资金预警应该有显眼的提示,点击进入页面后提示消失.

## 特殊业务逻辑

## 问题记录
### 开发阶段

### 测试阶段
