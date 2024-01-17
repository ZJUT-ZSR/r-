Placement_Data_Full_Class.csv：                 
	sl_no：这里即是指学生编号                
	gender：学生性别                     
	ssc_p：这里就是指中学课程均分              
	ssc_b：这里可以理解为中学是中央直属或者地方归属     
	hsc_p：这里指高中课程学习状况              
	hsc_b：高中为中央直属或者地方归属            
	hsc_s：高中的专业方向                  
	degree_p：本科课程平均成绩                 
	degree_t：本科毕业学位类别                 
	workex：有无工作经验                   
	etest_p：由大学进行的就业能力测评             
	specialisation：获得MBA学位的专业方向               
	mba_p：读MBA课程平均成绩                 
	status： 获取MBA学位后就业状况               
	salary： 就业薪水    

code.R:R文件，实现的功能如下
	数据清洗
	绘制各个离散特征与就业状况的分布图
	双向表卡方检验
	类别变量转换为factor
	factor转化为数值变量
	特性选择
	SVM randomForest Lasso
