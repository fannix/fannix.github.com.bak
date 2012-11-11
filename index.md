---
layout: page
title: About Me
tagline: 
---
Welcome to my homepage!

My name is Xinfan Meng (蒙新泛). I am a PhD student in Peking University. You can contact me via "@".join(["mxf3306", "gmail.com"]).

My research interests include: natural language processing, machine learning and sentiment analysis.

I use Python, C++ and R to develop.

##My Projects
My github page is here: [https://github.com/fannix](https://github.com/fannix).

I am a contributor of [scikit-learn](http://scikit-learn.org/stable/) and [NLTK](http://nltk.org/);
scikit-learn is the best machine learning package in Python,
and NLTK is the best natural language process toolkit in Python.
If you don't believe, try them yourself!



##My Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

##Publications

<ol>
<li><b>Detecting opinionated sentences by extracting context information.</b>  NTCIR-7.Xinfan Meng and Houfeng Wang. <a href="http://research.nii.ac.jp/ntcir/workshop/OnlineProceedings7/pdf/NTCIR7/C2/MOAT/12-NTCIR7-MOAT-MengX.pdf">link </a> </li>

<li><b>Mining user reviews: from specification to summarization.</b> ACL 2009. Xinfan Meng and Houfeng Wang. <a href="http://aclweb.org/anthology-new/P/P09/P09-2045.pdf">link </a></li>

<li><b>基于多模态学习的情感评级.</b> COAE 2009. 徐戈, 蒙新泛 and 王厚峰</li>
<li><b>主客观识别中的上下文因素的研究.</b> 中国计算机语言学研究前沿进展 (2007-2009), 2009. 蒙新泛 and 王厚峰. </li>

<li><b>Build Chinese emotion lexicons using a graph-based algorithm and multiple resources.</b> COLING 2010. Ge Xu, Xinfan Meng, and Houfeng Wang.<a href="http://aclweb.org/anthology-new/C/C10/C10-1136.pdf">link </a></li>

<li> <b>Cross-Lingual mixture model for sentiment classification.</b> ACL 2012. Xinfan Meng, Furu Wei, Xiaohua Liu, Ming Zhou, and Houfeng Wang.</li>

<li><b>Entity-centric topic-oriented opinion summarization in twitter.</b> KDD 2012. Xinfan Meng, Furu Wei, Xiaohua Liu, Ming Zhou, and Houfeng Wang. </li>

<li><b> Lost in Translations? Building Sentiment Lexicons Using Context Based Machine Translation </b> COLING 2012. Xinfan Meng, Furu Wei, Ge Xu, Longkai Zhang, Xiaohua Liu, Ming Zhou, and Houfeng Wang. </li>

<li><b>Constructing Chinese Abbreviation Dictionary: A Stacked Approach.</b> COLING 2012. Longkai Zhang, Sujian Li, Houfeng Wang, Ni Sun, and Xinfan Meng. </li>

<li><b> 采用无标注语料的动词和形容词主观性评级</b> 软件学报. 徐戈, 蒙新泛 and 王厚峰</li>
</ol>
