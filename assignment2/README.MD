# The Analysis of Jianshu Lifestyle Articles
Please see the assignment2 via Jupyter Notebook Viewer 

(Due to the Github website could not present data completely): 

https://nbviewer.jupyter.org/github/clairelau0108/python-data-assignments/blob/master/assignment2/Jianshu%20Analysis.ipynb
## Data Source
https://www.jianshu.com/c/f6b4ca4bb891
## Data Volume
450 rows × 8 columns

In order to analyse better, I scrape the website again. The dataset is different from assignment 1 due to the articles on the website update continuously.
## Data Analysis
* title - use wordcloud to analyse the high-frequency words
* word counts - use seaborn to calculate and compare word counts between different articles
* the publish date of articles - use matplotlib to present the articles' posting frequency
## License
CC 4.0
## Drawbacks and Problems
* The dataset is not rich enough.
* I scrape a lot of information, such as headline, abstract, website, word, view, like. But it is hard to classify them since the information is scattered. It does not like the case of OPENRICE which is easy to classify information. Therefore, it will be hard for me to do data analysis and find some interesting story.
* With the development of Internet, there are a lot of cyberwords appeared. However,the jieba module have not update its word bank frequently. Therefore, the popular word '双十一'could not be identified by jieba.
## Reference
[CityU Hall2 IT Team Workshop](https://cityu-hall2.github.io/)

[week-09 open book](https://github.com/hupili/python-for-data-and-media-communication-gitbook/blob/master/notes-week-09.md)

[Analysis of top 200 online novels](https://nbviewer.jupyter.org/github/DaisyZhongDai/hkbu-big-data-media/blob/master/homework3/Top%20200%20online%20novels.ipynb)

[用Python进行时间序列可视化](https://blog.csdn.net/hustqb/article/details/80717055)
