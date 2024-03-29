基础数据
-----------

地区
=======================

属性
^^^^^^^^^^^^^^^^^^^^^^^^^^^
* 地区 - 地区名称， 同级地区名称应该不能重复
* 备注 - 可选

搜索地区
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

输入地区名称或拼音首字母，点击搜索图标

新增地区
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

*如果需要增加下级地区，请先选择要增加下级地区的地区*

1. 点击 新增 图标
2. 输入地区属性 
3. 点击 保存

编辑地区
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. 选择要编辑的地区
2. 双击或点击编辑
3. 点击 保存

删除地区
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
*已使用的地区不能删除*

1. 点击要删除的地区
2. 点击删除按钮
3. 确认

商业伙伴
=======================
商业伙伴是C9 重要的基础数据之一

C9 不区分客户或供应商，而是统一称之为商业伙伴

商业伙伴可选一个价格体系, 在销售单中，如果销售价格小于该价格体系，则系统会用颜色予以警告

当前，系统按地区显示合作伙伴，选择相应的地区则显示该地区及下级地区(如果存在)的商业伙伴, 当前一旦选择某一地区，要回到全部地区请重新关闭窗口(todo)

属性 
^^^^^^^^^^^^^^^^^^^^^^^
* 名称 - 商业伙伴名称, 通常是公司名称, 必须输入
* 简称 - 商业伙伴简称, 通常是公司简称
* 地区 - 商业伙伴所在地区
* 信用额度 - 小于该额度的应收款不算超额, 必须输入
* 信贷期 - 在当前时间n天内的应收款不会超期, 必须输入
* 价格体系 - 可选 A/B/C
* 联系人
* 联系电话
* 传真
* 公司地址
* 邮编
* 电子邮件
* 网址
* 现金银行 - 开户行或账号
* 税号 
* 关闭 - 该合作伙伴是否已经不使用 
* 手机
* 备注

搜索商业伙伴 
^^^^^^^^^^^^^^^^^^^^^^^^
输入商业伙伴名称或其拼音首字母，点击查询按钮

可以用左侧的地区来缩小查询范围 

新增商业伙伴 
^^^^^^^^^^^^^^^^^^^^
如果选择了某一地区，则新建时自动填写地区属性

1. 点击新建按钮
2. 填写 商业伙伴 属性 
3. 点击保存

编辑商业伙伴 
^^^^^^^^^^^^^^^^^^^^^^^^^
1. 选择要编辑的商业伙伴 
2. 修改 商业伙伴 属性
3. 点击 保存


删除商业伙伴 
^^^^^^^^^^^^^^^^^^^^^^^^^^^
已经使用的商业伙伴不能删除

1. 选择要删除的商业伙伴
2. 点击 删除 按钮
3. 确认

品牌
=======================
通过品牌对产品分类, 可不使用该功能

属性 
^^^^^^^^^^^^^^^^^^^
* 品牌 - 品牌名称, 必须输入 

搜索 品牌
^^^^^^^^^^^^^^^^^^^^^^^^^

输入品牌名称或名称的拼音首字母, 点击搜索按钮

新建 品牌
^^^^^^^^^^^^^^^
*如果在新建时选择了某一品牌，则新记录自动成为选择品牌的下级品牌*

1. 点击新建按钮
2. 输入 品牌 属性
3. 点击 保存

编辑 品牌
^^^^^^^^^^^^^^^^
1. 选择要编辑的品牌
2. 双击或点击编辑按钮
3. 点击 保存

删除 品牌
^^^^^^^^^^^^^^^^^^^^
*如果品牌已经使用，则不能删除*
1. 选择要删除的品牌
2. 点击删除按钮
3. 确认


货品类型
===================================
对产品进行分类，重要

属性 
^^^^^^^^^^^^^^^^^^^^^^
* 货品类型 - 货品类型名称, 必须输入 
* 隶属 - 上级货品类型
* 描述 - 货品类型详细描述
* 备注

搜索 货品类型
^^^^^^^^^^^^^^^^^^^^^^^
输入货品类型名称或名称的拼音首字母，点击搜索按钮

新建 货品类型
^^^^^^^^^^^^^^^^^^^^^^
在新建 货品类型时， 可先选择上级货品类型，系统会自动填写隶属 属性，如果是顶级货品类型，可保持隶属为空白

1. 点击新建按钮
2. 输入货品类型属性
3. 保存

编辑 货品类型
^^^^^^^^^^^^^^^^^^^^^^^^

1. 选择货品类型
2. 双击或点击编辑按钮
3. 修改 货品类型 属性
4. 保存

删除 货品类型
^^^^^^^^^^^^^^^^^^^^^^^^^
*已使用的货品类型不能删除*

1. 选择要删除的货品类型
2. 点击删除按钮
3. 确认


产品信息
=========================

产品信息左边为产品类型,右边为产品,选择某一产品类型,右边则显示该产品类型及下级产品类型的产品.如果选择根节点,则显示所有产品

属性
^^^^^^^^^^^^^^^^^^^^^^^^
* 名称 - 产品名称，必须输入
* 货品类型 - 必须输入
* 品牌 - 必须输入
* 核算类型 - 隶属核算类型
* 参考售价A
* 参考售价B
* 参考售价C
* 强制条码 - 该产品必须扫描条码
* 条码 - 产品条码
* 条码2 - 产品条码,如果存在第二个条码的话
* 条码3 - 产品条码，如果存在第三个条码的话
* 每箱数量 
* 备注

搜索产品
^^^^^^^^^^^^^^^^^
输入产品名称或名称拼音首字母缩写,点击查询按钮

新建产品
^^^^^^^^^^^^^^^
1. 点击新建,如果事先选择产品类型,则自动填写货品类型属性 todo
2. 输入 产品 属性
3. 点击 保存

编辑产品
^^^^^^^^^^^^^^^^
1. 选择要编辑的产品
2. 双击或点击编辑按钮
3. 修改 产品 属性
4. 点击保存

删除产品
^^^^^^^^^^^^^^^^^
*如果产品已经使用,则不能删除*

1. 选择要删除的产品
2. 点击删除按钮
3. 确认

仓库 
========================

属性
^^^^^^^^^^^^^^^^^^^^^
* 名称 - 仓库名称,必须输入
* 成本核算方法 - 当前未用
* 隶属部门 - 必须输入
* 最高限额 - 当前未用
* 使用调拨价 - 当前未用
* 位置
* 备注

搜索 仓库
^^^^^^^^^^^^^^^^^^^^
输入仓库名称或名称拼音的首字母,点击搜索按钮

新建 仓库
^^^^^^^^^^^^^^^^^
1. 点击新建按钮
2. 输入仓库属性
3. 点击保存按钮

编辑 仓库
^^^^^^^^^^^^^^^^^
1. 选择要要编辑的仓库
2. 双击或点击编辑按钮
3. 修改仓库属性
4. 点击保存按钮

删除 仓库
^^^^^^^^^^^^^^^^^



货币
==========================

当前不使用

账户 
===============================
现金银行提供了一种对现金和银行账号管理方式

属性
^^^^^^^^^^^^
* 名称 - 必须输入
* 类别 - 必须选择
* 部门 - 必须选择

搜索账户
^^^^^^^^^^^^^^^^
输入账户名称或名称拼音首字母, 点击搜索按钮

新建账户
^^^^^^^^^^^^^
1. 点击新建按钮
2. 输入账户属性
3. 点击保存

编辑账户
^^^^^^^^^^^^^^
1. 选择要编辑的账户
2. 双击或点击编辑按钮
3. 修改账户属性
4. 点击保存

删除账户
^^^^^^^^^^^^^^^^^
*如果账户已经使用,则不能删除*

1. 选择要删除的账户
2. 点击删除按钮
3. 确认

科目
=================================

属性
^^^^^^^^^^^^^^^
* 科目代码
* 名称
* 隶属 - 上级科目
* 助记码 - 自动生成
* 内部代码 - 系统内部使用,不要修改
* 借/贷

搜索科目
^^^^^^^^^^^^^^^^
输入科目代码/名称/名称拼音首字母, 点击搜索按钮

新建科目
^^^^^^^^^^^^^^^^
1. 选择相应的上级科目节点, 第一级科目选择根节点
2. 点击 新建 按钮
3. 输入 科目 属性
4. 保存


编辑科目
^^^^^^^^^^^^^^^^
1. 选择要编辑的科目
2. 双击或点击编辑按钮
3. 修改科目属性
4. 保存

删除科目
^^^^^^^^^^^^^^^^^
1. 选择要删除的科目
2. 点击删除
3. 确认

部门
=================================

在此界面，用户只能看到授权的部门

部门属性 
^^^^^^^^^^^^^^^^^^^^^
* 名称 - 部门名称
* 代码 - 系统自动生成的惟一性标识，用于工作流

搜索部门
^^^^^^^^^^^^^^^^^^^^
输入部门名称或部门名称拼音首字母，点击搜索按钮

新增部门
^^^^^^^^^^^^^^^^^^^^^^

新增部门必须先选择上级部门，然后 

1. 点击新建按钮
2. 输入部门属性
3. 点击保存

编辑部门 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. 选择要编辑的部门
2. 双击或点击编辑
3. 输入部门属性
4. 点击保存

删除部门
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

仅未使用的部门可删除 

1. 选择要删除的部门
2. 点击删除 按钮
3. 确认

员工类型
====================================

员工类型用于员工的分类, 不重要，可不使用

属性 
^^^^^^^^^^^^^^^^^^^
* 员工类型

搜索
^^^^^^^^^^^^^^^^^^^^^^^^
输入员工类型或其拼音首字母，点击搜索按钮

新增员工类型
^^^^^^^^^^^^^^^^^^^^^
1. 点击新增按钮
2. 输入员工类型属性
3. 点击保存

编辑员工类型
^^^^^^^^^^^^^^^^^^^^^^^^
1. 选择员工类型
2. 双击或点击编辑按钮
3. 输入员工类型属性 
4. 点击保存

删除员工类型
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
1. 选择员工类型
2. 点击 删除 按钮
3. 确认

收入支出
====================================
也称为收支类型, 重要

属性 
^^^^^^^^^^^^^^^^^^^^

* 名称 - 收支类型名称 
* 方向 - 收入还是支出
* 合计科目 - 对应的科目
* 备注 - 可选输入

搜索收支类型
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
输入收支类型名称或名称的拼音首字母，点击搜索图标

新建收支类型
^^^^^^^^^^^^^^^^^^^^^^^^^^
1. 点击新建按钮
2. 输入收支类型属性 
3. 点击保存

编辑收支类型
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
1. 选择要编辑的收支类型
2. 双击或点击编辑按钮
3. 修改 收支类型 属性 
4. 点击保存

删除收支类型
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
*已经使用的收支类型不能删除*

1. 选择要删除的收支类型
2. 点击删除按钮
3. 确认



核算模块 
====================================
从另一角度统计数据

属性
^^^^^^^^^^^^
* 名称 - 核算模块名称
* 备注 
* 助记码 - todo 移除

搜索核算模块
^^^^^^^^^^^^^^^^^
输入核算模块 名称或名称拼音首字母, 点击搜索按钮

新增 核算模块
^^^^^^^^^^^^^^^^
1. 点击新建按钮
2. 输入核算模块属性
3. 点击保存

编辑 核算模块
^^^^^^^^^^^^^^^^^^^^^^
1. 选择要编辑的核算模块
2. 双击或点击编辑
3. 修改核算模块属性
4. 点击保存

删除 核算模块
^^^^^^^^^^^^^^^^^^^^^^^
*如果核算模块已经被使用,则不能删除*

1. 选择要删除的 核算模块
2. 点击删除按钮
3. 确认