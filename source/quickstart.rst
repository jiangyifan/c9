快速开始
-------------------------

操作简介
=========================

C9 有类似outlook的界面， 
最上方是工具条，用户可以通常工具条按钮快速启动某一功能。中间左边是功能导航 , 右边是一个Tab, 用于显示同时打开的多个界面

常用图标
^^^^^^^^^^^^^^^^^^^^^^
.. image:: /images/database_add.png
	:align: left
通常用于新建记录

.. image:: /images/database_edit.png
	:align: left
通常用于编辑记录

.. image:: /images/database_delete.png
	:align: left
通常用于删除/移除记录

.. image:: /images/database_refresh.png
	:align: left
通常用于刷新记录

通常单据流程
^^^^^^^^^^^^^^^^^^^^^^^

所有单据通常均有如下流程

1. 创建新单据, 通常可以从工具栏按钮快速打开新单据窗口或从导航中选择相应的菜单,再选择新建按钮
2. 确认单据 - 该单据进入流程
3. 审核单据(根据流程设定,有时没有该步骤)
4. 执行单据, 执行出库,生成凭证之类的实际操作通常在此步骤完成

通常,在3或4,流程审核者均可以选择退回,此时创建者或删除单据或重新编辑后继续进入2步骤


定义部门结构 
=========================

*注意* 仅允许一顶级部门

C9 允许你创建多级的部门结构,  如果单据的部门有不同(比方说单据创建部门和单据仓库的部门不一致),系统将独立对部门进行核算


定义用户和角色 
=========================

参考 :doc:`admin-user`

参考 :ref:`admin-role`



工作流授权
=========================

初始化基础数据
=========================


创建单据并执行
=========================


查看报表
=========================




