# reptile

#参考内容：https://zhuanlan.zhihu.com/p/28680797
##所有代码都基于这边文章进行修改，以适合windows系统运行

#在windows系统安装ChromeDrive的时候，只有32位的可以下载
#下载后要在C盘Windows文件夹里面创立一个【ChromeDrive】的文件夹，把下载的32位exe放进去，并且添加该路径到path里面


#代码有两个地方需要修改
##第一个是要把所有的【./output/rawfile/raw_result.txt”的“./”改成【C:/】
##第二个是要把【with open("./output/rawfile/raw_result.txt", 'w') 】改成【 with open("C:/output/rawfile/noscript_meta.txt", 'w',encoding='utf-8')】
