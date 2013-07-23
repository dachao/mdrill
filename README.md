<h1>项目简介</h1>
1.mdrill是阿里妈妈-adhoc-海量数据多维自助即席查询平台下的一个子项目。<br>
2.mdrill旨在帮助用户在几秒到几十秒的时间内，分析百亿级别的任意维度组合的数据。<br>
3.mdrill是一个分布式的在线分析查询系统，基于hadoop,lucene,solr,jstorm等开源系统作为实现，基于SQL的查询语法。 mdrill是一个能够对大量数据进行分布式处理的软件框架。mdrill是快速的高性能的，他的底层因使用了索引、列式存储、以及内存cache等技术，使得数据扫描的速度大为增加。mdrill是分布式的，它以并行的方式工作，通过并行处理加快处理速度。<br>
4.mdrill在adhoc项目中，mdrill使用了10台机器，存储了400亿的数据，每次扫描30亿的行数，响应时间在20秒~120秒左右(取决不同的查询条件)。<br>
<h1> 发行日志</h1>
 2013.7.24 version 0.18-beta  <a href="https://github.com/alibaba/mdrill/blob/master/release/0.18-beta/alimama-adhoc.tar.gz?raw=true" target="_blank">下载</a> <a href="https://github.com/alibaba/mdrill/blob/master/release/0.18-beta/alimama-adhoc-core.zip?raw=true" target="_blank">源码下载</a> <br>

<h1>资源列表</h1>
<ul>
<li><a href="https://github.com/alibaba/mdrill/wiki/info" target="_blank">mdrill介绍</a></li>
<li><a href="https://github.com/alibaba/mdrill/blob/master/doc/INSTALL.docx?raw=true" target="_blank">安装部署</a></li>
<li><a href="https://github.com/alibaba/mdrill/blob/master/doc/MSql.docx?raw=true" target="_blank">sql使用手册</a></li>
</ul>

<h1>mdrill Core contributors</h1>
<ul>
<li>子落、含光、士远、木晗、逸客、张壮、凌凝</li>
</ul>
<h1>jstorm Core contributors</h1>
<ul>
<li>纪君祥、子落、丙吉、陈均</li>
</ul>


<h1>其他</h1>
mdrill技术交流群:171465049<br>
