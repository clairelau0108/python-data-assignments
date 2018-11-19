# Jianshu Dataset
## Topic
### **The observation of lifestyle via the UGC website-Jianshu**

Lifestyle is one of the most important thing to see people’s life quality. Moreover, with the development of electronic markets, such as Alibaba, Xiaohongshu, it is significant for us to do some study regarding people’s lifestyle, which can have a better understanding of consumer insights and make profits.
## Data Source
This dataset contains some new articles regarding lifestyle on Jianshu theme website: 
https://www.jianshu.com/c/f6b4ca4bb891
## Data Fields
* headline - e.g. 手把手教你打造颜值超高的温馨书桌
* nickname - e.g. 筱厨君
* abstract – e.g. 似乎从7月份以来，就没正儿八经地出去玩过，所以这一次，趁着周末，心血来潮跟着室友去啦一趟绍兴...
* website – e.g. https://www.jianshu.com/p/3b2dd9be9be6
* time – e.g. 2018.11.05 22:03
* word – e.g. 字数 2005
* view – e.g. 阅读 4
* like – e.g. 喜欢0
## Data Volume
140 rows × 8 columns
## License
CC 4.0
## Obstacles & Solution
1.	**Scroll the page.** 
Being different from other websites which are page turning, Jianshu is the website that has vertical infinite scrolling. So the codes of pages are changing every time. After asked my friend for help, I found that the XHR of Chrome DevTools can help me find the website when scrolling down the page. When I found the websites, it is the same as page turning.
2.	**Data Fields Information.**
On the theme page, the articles only have some parts of information I need, but other information, such as time, word, view and likes, I have to grab them via clicking into the article. So I wrote a circulation about the websites of all articles. Of course, the speed of collecting data will be lower than other common pages because python have to grab information from websites by 2 steps.
