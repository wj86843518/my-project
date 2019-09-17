# my-project

#search(器材查询)
Index.html (器材查询)
Search.html(器材查询2、搜索)
GoodsDetail1.html(器材查询3)
GoodsDetail2.html(物品详情)


#零星实验
#teacher
Index.html(演示列表)
WriteBorrowTicket.html(填写借用单、实验演示、申请中)
AddEquipment.html(搜索结果2、搜索结果3、搜索结果4)
Applying.html(申请中)
ReadyFinish.html(准备完成)
Guihuan.html(归还  蓝湖UI没有，可以忽略)
Using.html(使用中  蓝湖UI没有，可以忽略)
Tuihui.html(退回  蓝湖UI没有，可以忽略)
Readying.html(准备中  蓝湖UI没有，可以忽略)

#admin(管理员)
Index.html(管理员首页)
WaitReceive.html(待接收  八种状态通用)
EquipmentList.html(器材列表)

#演示实验
#teacher
Index.html(演示列表、演示列表_左划删除)
NewApply.html(新建申请、准备中)
SelectExperiment.html(选择实验室、搜索结果)
Experiment.html(加速度探究实验室1)
AddEquipment.html(搜索结果2、搜索结果3、搜索结果4)
Guihuan.html(已归还)
Appraisal.html(器材评价)
Using.html(使用中)
ReadyFinsh.html(准备完成)

#admin(管理员)
Index.html(管理员首页)
WaitReceive.html(待接收)
Readying.html(准备中)
Readying1.html(准备中1)
ReadyFinish.html(准备完成)
Using.html(使用中、使用中2)
BadState.html(损坏情况)

#common EquipmentList.html(器材列表)

#学生实验
#teacher
Index.html(学生实验申请)
演示实验 ==》 teacher ==》 NewApply.html(新建申请、新建申请1)(复用页面)
演示实验 ==》 teacher ==》 SelectExperiment.html(选择实验室、搜索结果)(复用页面)
演示实验 ==》 teacher ==》 Experiment.html(加速度探究实验室1) (复用页面)
演示实验 ==》 teacher ==》 AddEquipment.html(搜索结果2、搜索结果3、搜索结果4) (复用页面)
Arrangement.html(新建申请2、新建申请3、新建申请4)
BadState.html(损坏情况)

#admin(管理员)
Index.html(管理员首页)
WaitReceive.html(申请中)
EquipmentList.html(器材列表)
Arrangement1.html(实验安排、实验安排拷贝、弹框设置安排地点)
Arrangement2.html(新建申请2拷贝3、新建申请2拷贝4)
学生实验 ==》 teacher =》 Arrangement.html(进行中) (复用页面)
演示实验 ==》 admin ==》 BadState.html(损坏情况)(复用页面)


移动端修改：
在assets ==》 style ==》 ui-style.css 替换原来的文件
在search ==》 Index.html ==》 把样式表替换原来的样式


后端工程 ：backEnd
入口：Index.html

实验设置：basicSetting ==》LaboratorySetting.html
实验器材大类设置：basicSetting ==》TypeSetting.html
实验品存放地点设置：basicSetting ==》LocationSetting.html
导入实验室器材数据：basicSetting ==》ImportData.html

物品查询：messageSearch ==> GoodsSearch.html
使用日志：messageSearch ==> UseLog.html
评价：messageSearch ==> Appraise.html
实验日志：messageSearch ==> ExperimentLog.html

实验室管理：experimentalManagement ==》 ExperimentalManagement.html