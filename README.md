#医药管理信息系统
医药管理信息系统

概述
项目背景：设计本系统，模拟医药超市的部分管理功能。<br>
业务描述：药品由专门的采购人员从医药经销商处购进医药超市，并将药品信息记录入库，顾客从超市购买药品需填写相关个人信息，每次售药需登记经办人（医药超市员工，即销售人员）的信息，以及所售药品的信息。<br>
开发环境：window10,mysql5.8, Eclipse Jee Neon<br>
<br>
功能模块<br>
1．“信息查询”功能模块<br>
1）查询顾客信息<br>
2）查询经办人信息<br>
3）查询药品信息<br>
4）查询订单信息<br>
注：信息查询可基于单条件查询也可基于多条件复合查询。<br>
2．“信息录入”功能模块<br>
1）录入顾客信息<br>
2）录入经办人信息<br>
3）录入药品信息<br>
4）录入订单信息<br>
注：信息录入时，需要考虑数据信息的完整性、有效性等。<br>
3．“信息删除”功能模块<br>
1）删除顾客信息<br>
2）删除经办人信息<br>
3）删除药品信息<br>
4）删除订单信息<br>
注：可单条记录删除，也可批量删除，执行该项操作时需要考虑删除所需的约束条件（如：为顾客提供服务的经办人信息不能删除，顾客已购买的药品信息不能删除）。<br>
4．“信息修改”功能模块<br>
1）修改顾客信息<br>
2）修改经办人信息<br>
3）修改药品信息<br>
注：进行修改操作时，需要保证数据的一致性<br>
5．“信息浏览”功能模块<br>
1）浏览顾客信息<br>
2）浏览经办人信息<br>
3）浏览药品信息<br>
4）浏览订单信息<br>
注：通过系统提供的相关界面对client、agency、medicine等数据表中的内容进行浏览。<br>
6．“数据报表”功能模块<br>
1）顾客信息报表<br>
2）经办人信息报表<br>
3）药品信息报表<br>
4）订单信息报表<br>
注：按照一定的格式在相应的窗口界面上显示顾客、经办人、药品、订单等信息，并提供通过打印机打印输出的功能。<br>
7．用户管理与用户登陆功能模块<br>
系统可根据需要添加、删除用户，并可对已有的用户信息进行修改操作；在添加新用户时，可定义其操作权限（查询、更新、浏览、报表等权限）；用户密码可进行随时修改；各种不同身份的用户登陆系统后，可享有不同的系统操作权限。<br>
