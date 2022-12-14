# Dataset-of-Pedestrian-Dead-Reckoning
2022秋高级机器学习第一次作业
-
>PDR-小组数据共享计划
* 加入共享计划的小组可以使用其他小组收集的数据  
* 请及时维护自己上传的数据集文件


### 成员id
为防止数据集名称重复，为每个上传数据集的成员分配唯一id
 成员姓名  | id  | 成员姓名  | id | 成员姓名  | id  
---- | ----- | ---- | ----- | ---- | ----- 
xxx  | 00 | lth  | 06 | cyz | 12
shn  | 01 | cmj  | 07 | qk  | 13
shy  | 02 | zyl  | 08 | wzc | 14    
lqf  | 03 | fsj  | 09 | mcz | 15    
rwq  | 04 | myw  | 10 | wyd | 16
xyh  | 05 | yr   | 11 | hyh | 17
  
 
### 更新!!! 22/11/24  
发现部分同学上传的数据集不是以50Hz频率收集的，请相关成员及时将异常数据集撤回，谢谢配合！


### 更新 22/11/22
拿手机走路时，摆臂与否对传感器数据特征影响很大。  
原有的“ Hand-Walk-...”很难再划分，因此希望大家在新上传的数据集中区分是否摆臂  
新增的数据集命名示例如下：  
* HandSwing-Walk-00-001（xxx收集的第1个在手中摆臂走路的数据集）  
* HandStay-Walk-00-001（xxx收集的第1个看手机走路的数据集） 
  

### 数据集命名方法  
为方便代码读取，请将每个数据集命名为“手机位置-人的姿态-id-序号”如  
* Hand-Walk-01-001（在手中--走路--shn收集的第1个在手中走路的数据集）  
* Bag-Run-03-010（在包里--跑步--lqf收集的第10个在包里跑步的数据集）  
* Pocket-Ride-02-001（在兜里--骑车--shy收集的第1个在兜里骑车的数据集）  
* Hand-Pace-00-001（在手中--走走停停--xxx收集的第1个在手中走走停停的数据集）
* Hand-Circle-00-001（在手中--绕圈--xxx收集的第1个在手中绕圈的数据集）

### 测量注意事项  
* 每次收集请从静止状态开始，时长大于3min，频率设为50Hz
* 如果手机没有气压计，可以不勾选“压力传感器”
* 为收集准确的GPS标记，请务必在室外进行收集
* 请选择CSV(Comma, demical point)数据格式导出
* 记得要将导出后的zip文件解压缩，否则是无法上传到仓库的
