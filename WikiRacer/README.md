# cs106L assignment1&2 WikiRacer
The class version is 2021 fall. Download form [Snme Github Page](https://github.com/snme)
And I'm not Standford Student, this assignment is running on my own Tencent cloud server. 


### What have done
1. assignment 1 has completed, use fstream and operator(<< >>) to load the date from .txt file
2. assignment 2 has completed step by step.


### Diference from the original version
Because of some DNS problem in Tencent cloud, instead of going to Wikipedia, I changed it to detailedpedia.com to test my project. 

If you have finished your code, but the process just hang out for a long time, it may because you cant download the html page. So you can use `wget` to test if it successfully connect to the wiki page.

Because the detailedpedia has different grammer on page link, I modify "delim" in function findWikiLinks. 

If you can `wget` the html resource from wiki page, just stick with the original file and feel free to use my code to do your test.