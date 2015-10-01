# TheoreticalAssignment1
理论课第一次作业
理论课第一次作业（Theoretical Assignment1）
#####注意：
老师在课堂上留的作业有变，之前的作业作废，变为此次的作业说明。如果哪位同学在10.1号已经做完，请与助教联系，无需重做，我们将对你的作业单独打分。
#####作业描述：
1. 自建一个Excel文件，将所有之前爬取下来的成绩单直接用鼠标键盘选取复制进这个excel文件中，采用Excel的“另存为”的方法，把Excel文件转化为“txt”文件。（一级加分项：直接用Jsoup对原有HTML进行解析实现读取及后续操作；二级加分项：直接通过Java读取excel文件而非txt文件。）
2. 写一个程序，读取之前操作的txt或excel文件。对所有课程根据分数多少进行从高到低的降序排列，并依次计算加权平均分、综合加权GPA这两项数据。输出重新排名的成绩单以及所计算出的剩余两项数据到txt文件中。（加分项：输出excel文件(.xls)）
#####程序接口规范要求：
1. 如果是带GUI界面的程序（加分项），需要将程序主接口放置在MainGUI类的main函数下。
2. 如果是不带GUI界面的程序，则最终生成结果的函数需要被定义于MainOutPut类的方法public void processScoreTable(File input)下。（input即为所读取的excel或txt文件）
#####要求：
1. 独立完成，严禁抄袭，一旦被查重系统MOSS判定为抄袭并无法做出合理解释者，第一次予以警告并记此次作业0分。若再被发现，直接挂科。
2. 最终请将你所写的Java代码以及爬取结果一同打包至.zip压缩包中，命名格式：学号-姓名-TheoreticalAssignment1。
3. 所有作业请提交到Github上TheoreticalAssignment1 repository下的submit-homework文件夹下，所有提交至其他地方的作业视作无效。
4. 请按照接口说明编写程序，不符合接口规范的程序将会被扣分。
5. Deadline：10月8日 0:00（有加分），最终截止日期：10月12日 0:00
