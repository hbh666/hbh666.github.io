hexo new "文章标题"

hexo s #本地查看效果

hexo clean && hexo g -d
#生成静态网页到public，并把public/推送到Github Pages仓库main分支

两台电脑协作标准流程：
1.拉取：git pull

2.新建:hexo new "笔记“

3.本地预览：hexo s

4.发布：hexo clean && hexo generate && hexo deploy
备份源码：git add .
git commit -m "xxx"
git push origin hexo