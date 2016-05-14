BookRecommend<br>
图书推荐系统，依托豆瓣的图书和评分信息，使用基于user的推荐算法，实现推荐<br><br>

1：环境说明<br>
Mysql 5.6 + python 2.7 + django 1.8 + MySQLdb<br><br>

2：文件夹说明<br>
bookrecommend：是项目综合展示的目录，是一个django的工程，使用时，只需在该目录下打开cmd，运行manage.py runserver 即可<br>
数据集：里边是项目所需要的数据集<br>
        books.csv:书本的相关信息<br>
		users.csv:用户的相关信息<br>
		uid_score_bid.csv:用户给书本的打分信息<br>
数据库备份：使用时在数据中新建一个bookrecommend数据库，导入sql文件即可<br>
算法原型：协同过滤基于items的推荐算法<br><br>

3：版本说明，在版本1中界面简单，且功能单一，在后续的第二代版本更新中，出现了较大的变化，主要功能包括
（1）：“猜你喜欢”，即用户推荐模块，依旧是基于用户的协同过滤算法<br>
（2）：“新书速递”，即向用户展示最近出版的图书，是对用户的新书推荐<br>
（3）：“hot 榜”，即向用户展示最热门的图书，是对用户的热门推荐<br>
（4）：“用户推荐”，向用户推荐相似度最高的k个用户<br><br>

4：爬取数据部分代码和第二版本的数据集暂时不提供，有需要的话联系邮箱：thinkgamer_gyt@gmail.com<br>


