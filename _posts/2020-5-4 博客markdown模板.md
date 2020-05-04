<!-- 写注释用的代码，不会显示 -->
<!-- 习惯了markdown之后感觉不错 -->
# 一级标题

> 引用
<!-- 记得换行 -->

## 二级标题
&emsp;&emsp;正文，前面用两组代码实现首行空格。
<!-- 一个&emsp;等于一个中文字 -->

### 三级标题

*一个星号写斜体；*
**两个星号写粗体；**
三个星号是分割线
<!-- 不知道又粗又斜怎么弄 -->

### 改变字号

<font size=4>我是4号字</font>
<font size=6>我是6号字</font>
<!-- <></>成对出现，是html语言 -->
<p>段落</p>
插图
<p align="center">
  <img src="https://2pt2m1389nao1lh6xkkaly2w-wpengine.netdna-ssl.com/wp-content/uploads/sites/45/2019/05/Su_Shang_255x187.jpg?raw=true" alt="Photo" style="width: 450px;"/>
</p>
<p align="left">
  <img src="https://2pt2m1389nao1lh6xkkaly2w-wpengine.netdna-ssl.com/wp-content/uploads/sites/45/2019/05/Su_Shang_255x187.jpg?raw=true" alt="Photo" style="width: 450px;"/>
</p>
<p align="right">
  <img src="https://2pt2m1389nao1lh6xkkaly2w-wpengine.netdna-ssl.com/wp-content/uploads/sites/45/2019/05/Su_Shang_255x187.jpg?raw=true" alt="Photo" style="width: 450px;"/>
</p>
<p>
  <img src="https://2pt2m1389nao1lh6xkkaly2w-wpengine.netdna-ssl.com/wp-content/uploads/sites/45/2019/05/Su_Shang_255x187.jpg?raw=true" alt="Photo" style="width: 450px;"/>
</p>
<!-- 看来不指名对齐方式的话，是默认靠左 -->

## 精简版
<img src="https://2pt2m1389nao1lh6xkkaly2w-wpengine.netdna-ssl.com/wp-content/uploads/sites/45/2019/05/Su_Shang_255x187.jpg" />
<img src="https://sushang-thu.github.io/images/profile3.jpg" />

## 插入代码

单行用单个`包裹代码，大段或多行用```置于首末行。

```
#PBS -l walltime=20:00:00
#PBS -l mem=200gb
#PBS -l nodes=1:ppn=8
#PBS -M shang.su@vai.org
#PBS -m abe

#setup environment
source /home/shang.su/miniconda3/etc/profile.d/conda.sh
conda activate bioinfo
```

## 表格
表格还是算了，还不如截个图。

## 参考
[1] [献给写作者的 Markdown 新手指南](https://www.jianshu.com/p/q81rer)
