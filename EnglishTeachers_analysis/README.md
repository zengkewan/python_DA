## 爬取英语外籍老师与本土老师招聘数据
项目主要爬取2019-08-15外籍人员招聘网站JobLEADChina上的外籍英语老师招聘数据960条，万行教师人才网上的英语老师招聘数据976条，并分析中外英语教师的招聘状况

### 主要的文件为：

* jobleadchina.py：爬取外籍人员招聘网站JobLEADChina上的外籍英语老师招聘数据代码
* local_english_teacher.py：爬取万行教师人才网上的英语老师招聘数据代码
* ET_analysis.ipynb：Jupyter notebook代码，对外教教师的招聘状况进行分析

#### 数据
* JobLEADChina数据：jobleadchina.csv
* 万行教师人才网招聘数据：外语培训.csv

## 分析总结
我们逐一回答开始提出的问题：

1. 外教的中国老师的工资差的别如何？
   * 中教的工资集中分布在五千到一万多一点，外教的工资分布在一万出头到两万出头
   * 外教的工资总体均值为16348.3元，中教的工资总体均值为7777.7元，外教是中教的2倍多
2. 市场对外教的经验和学历需求如何？
   * 相似的经验水平下，外教的平均工资大概是中教的2倍左右
   * 相似的学历水平下，外教的平均工资大概是中教的2倍左右
   * 对外教经验需求比例：对Entry Level/入门级的需求比例最大，达到了45.7%，总体来说对相对年轻、有些许经验的外教需求量大(超过九成)
   * 对外教学历需求比例：对Bachelor/本科以上的需求比例最大，达到了74.8%，加上学历不限的23.5%，已经达到了98%
3. 哪些城市对外教的需求多？
   * 北京以441个职位遥遥领先
   * 北上广深杭占据前五，其余也都是知名大城市
   * 在对外教需求最多的10个城市中，外教的平均薪酬都在中教的2倍左右
4. 哪些类型的机构在招聘外教？
   * 对外教需求前五的单位类型中，排第一的是培训机构
   *　学校给的平均工资是最高的，达18599.7，这里面很多都是价格昂贵的国际语言学校，对教师的学历和资质要求相对高一些。
   * 而培训机构给的工资却是最低的，对外教的学历和资质要求都比较宽松。

究其原因，价格跟稀缺性成正比，外教在国内供不应求，一是现在学生或者学生家长对于英语口语的需求越来越高，二是很多外国人才开始认识中国。
当越来越多的外国人了解我们国家并且愿意来当外教的时候，供不应求的状况便会产生变化。